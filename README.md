# Quadratic Equations Solver

Script ```pre-commit``` launch unittests from tests.py when you commit changes to [GitHub](https://github.com). \
If tests OK - commit accepted. If not - commit rejected

# How to install

1. Put ```pre-commit``` to hooks folder in project. Command: ```mv pre-commit .git/hooks/```. 
2. Give permissions to execute. Command: ```chmod +x .git/hooks/pre-commit```(Alternatively add ```sudo``` before command)

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


# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
