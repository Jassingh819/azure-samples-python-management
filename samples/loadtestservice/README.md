---
page_type: sample
languages:
- python
products:
- azure
description: "These code samples will show you how to manage Consumption using Azure SDK for Python."
urlFragment: loadtestservice
---

# Getting started - Managing Consumption using Azure Python SDK

These code samples will show you how to manage Loganalytics using Azure SDK for Python.

## Features

This project framework provides examples for Azure Loadtest Service. [Read More about Loadtest Service](https://learn.microsoft.com/azure/load-testing/overview-what-is-azure-load-testing)
## Getting Started

### Prerequisites

1. Before we run the samples, we need to make sure we have setup the credentials. Follow the instructions in [register a new application using Azure portal](https://docs.microsoft.com/en-us/azure/active-directory/develop/howto-create-service-principal-portal) to obtain `subscription id`,`client id`,`client secret`, and `application id`

2. Store your credentials an environment variables.
For example, in Linux-based OS, you can do
```bash
export AZURE_TENANT_ID="xxx"
export AZURE_CLIENT_ID="xxx"
export AZURE_CLIENT_SECRET="xxx"
export SUBSCRIPTION_ID="xxx"
```

### Installation

1.  If you don't already have it, [install Python](https://www.python.org/downloads/).

    This sample (and the SDK) is compatible with Python 3.7+.

2.  General recommendation for Python development is to use a Virtual Environment.
    For more information, see https://docs.python.org/3/tutorial/venv.html

    Install and initialize the virtual environment with the "venv" module on Python 3 (you must install [virtualenv](https://pypi.python.org/pypi/virtualenv) for Python 3.7+):

    ```
    python -m venv mytestenv # Might be "python3" or "py -3.7" depending on your Python installation
    cd mytestenv
    source bin/activate      # Linux shell (Bash, ZSH, etc.) only
    ./scripts/activate       # PowerShell only
    ./scripts/activate.bat   # Windows CMD only
    ```
3. Install Loadtestservice Management Library [azure-mgmt-loadtestservice](https://pypi.org/project/azure-mgmt-loadtestservice/) from pypi in the virtual enviornment created.

### Quickstart

1.  Clone the repository.

    ```
    git clone https://github.com/Azure-Samples/azure-samples-python-management.git
    ```

2.  Install the dependencies using pip.

    ```
    cd azure-samples-python-management/samples/loadtestservice
    pip install -r requirements.txt
    ```

## Demo

A demo app is included to show how to use the project.

To run the complete demo, execute `python example.py`

The sample files do not have dependency each other and each file represents an individual end-to-end scenario. Please look at the sample that contains the scenario you are interested in

## Resources

- https://github.com/Azure/azure-sdk-for-python
