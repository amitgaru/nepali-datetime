# CONTRIBUTING

## Guidelines
- fork the project
- clone the forked project
- pip install the nepali_date in editable mode. In the root directory of the project, do `$ pip install -e .`
- Install `pytest` for running tests. ```$ pip install pytest```
- Install `flake8` for code formatting check. ```$ pip install flake8```
- check if all tests are passed by ```$ pytest```
- start contributing
- before pushing the changes, check again if the tests are passed ```$ pytest```
- also check code formatting has any issues `$ flake8 nepali_datetime --max-line-length=120`
- push your code and raise the PR to the `develop` branch

**Note: If you're confused on what to contribute to, you can search for *TODO's* in the code & pick whichever
you're comfortable with.**


## Calendar/Date-related issues
  If you find any date or calendar-related issues, please provide at least two legit sources along with your PR.
  

## Preparing a new release
- Check out from the `master` branch with the name of the branch of the version, like `v1.0.8.3`.
- Update the release version in the `nepali_datetime/__init__.py` file name by updating the variable `__version__`.
- Update the documentation to reflect the release version by rebuilding the documentation inside `docs/` using the command `make html`. Make sure you install all the documentation dependencies before rebuilding it, which is in `docs/requirements.txt`.



#### *** HAPPY CONTRIBUTING! ***
