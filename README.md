# python-playwright-e2e-tests Project
E2E automated tests created using Playwright with Python.
Test in web store: https://www.demoblaze.com
 
# Test Configurartion

- Clone project `git clone ..`
- Install `pip install pytest-playwright`
- Install `playwright install`
    - or `pip install playwright`


# Run tests

- Run all tests: 
    - `pytest`
    - or: `python -m pytest`
- Run:
    - Specific test: `pytest tests/test_demoblaze.py`
    - Specific test in headed mode: `pytest tests/test_demoblaze.py --headed`
    - Specific file with Tracing for debugging: `pytest --tracing on tests/test_demoblaze.py`
    - Specific file with Tracing for debugging in headed mode: `pytest --tracing on tests/test_demoblaze.py --headed`


NOTE: Test for Demoblaze website was recorded using Playwright Codegen
- `python -m playwright codegen`

