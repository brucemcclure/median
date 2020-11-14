# Median

###### Trello board to keep me on track

Link:

## Overview

---

## Local Install Steps

The app makes use of the venv pip package to create a virtual environment. Therefore the package will need to be installed in order to run the app. There after the install instructions are as below:

- Clone the repo: `git clone `
- Change directory into the repo: `cd demo_app`
- Make sure venv is installed: `pip install venv`
- Create the virtual environment: `python3 -m venv venv`
- Activate the virtual environment: `source venv/bin/activate`
- Install the dependencies from requirments.txt: `pip3 install -r requirements.txt`
- Run the app: `python src/main.py`

---

## CI/CD

The CI/CD pipeline was created using Github Actions. It uses Python3.8, Pip3 and runs on the latest stable version of Ubuntu. The pipeline is started on a push to master.
Once it has pulled from master it installs the dependencies form requirements.txt and then it runs the tests in the tests directory.

---

## Wireframes

#### Missing wire frames

#### {example}

![]()

#### {example}

![]()

#### {example}

![]()

#### {example}

![]()

#### {example}

![]()

#### {example}

![]()

#### {example}

![]()

#### {example}

![]()

#### {example}

![]()

---

## DB Schema

![]()

---

## Endpoint Documentation
