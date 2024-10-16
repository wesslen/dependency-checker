# Dependency Checker

CI/CD pipeline that uses a GitHub action to test Package dependencies of `requirements.txt` and outputs [`pipdeptree`](https://pypi.org/project/pipdeptree/).

To use, modify the `requirements.txt`. Then run the GitHub action using Actions > Manual Dependency Check > Run Workflow > Select what version of Python to test.

This tests dependencies on the `ubuntu-latest` OS.
