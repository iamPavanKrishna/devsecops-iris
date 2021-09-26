# Dev-Sec-Ops Assignment
---
### Pavan krishna's Forked repository


[![codecov](https://codecov.io/gh/iamPavanKrishna/devsecops-iris/branch/master/graph/badge.svg?token=0KZ5ZTABV9)](https://codecov.io/gh/iamPavanKrishna/devsecops-iris)

This repository contains code which demonstrates Dev-Sec-Ops using a `FastAPI` application which predicts the flower class using the IRIS dataset (https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)

## Running Instructions
- Create a fork of the repo using the `fork` button.
- Clone your fork using `git clone https://www.github.com/<your-username>/mlops-iris.git`
- Install dependencies using `pip3 install -r requirements.txt`
- Run application using `python3 main.py`
- Run tests using `pytest`

## CI/CD
- `unittest`: Run the python unit tests using pytest
- `codecoverage`: Analyze code quality using codecov and upload results
- `container-security`: Scan docker image using anchore and upload SARIF report artifact
- `upload_zip`: Package code and upload as artifact


## Assignment Tasks
- Fix badge to show coverage for your repo. (hint: find correct link for badge from codecov.io)
- Add OS to matrix strategy along with PYTHON to test with different operating systems like `ubuntu-latest`, `windows-latest`  etc.
- Improve code coverage and bring it above 95%
- Make a visualisation for sarif report using any tool. upload screenshot, image, html or pdf. Add it to the reports/ folder. 

## Submission
- Link to github repository as a comment on the submission (olympus portal). [uploading .txt is optional]