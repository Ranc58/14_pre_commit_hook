# Quadratic Equations Solver

Script ```pre-commit``` launch unittests from tests.py when you commit changes to [GitHub](https://github.com). \
If tests OK - commit accepted. If not - commit rejected

# How to install

Put ```pre-commit``` to ```<ProjectFolder>/.git/hooks/```.

If you want launch it on Linux: \
Give permissions to exeucute. Command: ```chmod +x pre-commit```(Alternatively add ```sudo``` before command)

# Launch examples
Launch example on Linux:
```
$ git add test.py
$ git commit -m 'test'
...
----------------------------------------------------------------------
Ran 4 tests in 0.001s

OK
[master e793b02] 'test'
 1 files changed, 1 insertion(+), 1 deletions(-)
```
Launching on Windows is same

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
