<!--
SPDX-FileCopyrightText: 2020 2019-2020 SAP SE

SPDX-License-Identifier: Apache-2.0
-->

# Python client library for SAP AI Business Services - Document Classification REST API

[![REUSE status](https://api.reuse.software/badge/github.com/SAP/document-classification-client)](https://api.reuse.software/info/github.com/SAP/document-classification-client)

This repository contains the [source code](sap_business_document_processing) of a Python client library to facilitate the use of [SAP AI Business Services - Document Classification](https://help.sap.com/dc) and [SAP AI Business Services - Document Information Extraction](https://help.sap.com/dox). The client library provides two API Client classes that contain convenient methods to access these services and issue calls to the [SAP AI Business Services - Document Classification REST API](https://help.sap.com/viewer/ca60cd2ed44f4261a3ae500234c46f37/SHIP/en-US/c1045a561faf4ba0ae2b0e7713f5e6c4.html) and [SAP AI Business Services - Document Information Extraction REST API](https://help.sap.com/viewer/5fa7265b9ff64d73bac7cec61ee55ae6/SHIP/en-US/ded7d34e60f1422ba2e04e892a7f0e25.html) respectively. In order to be able to use the library you need to [have access to SAP Business Technology Platform](https://www.sap.com/products/cloud-platform/get-started.html).

Please check out the [**usage examples**](./examples), they are very useful to get started with the services.

Please have a look at [**API documentation**](./API.md) in order to use the library.

## Requirements

This library requires properly setup [Python 3](https://www.python.org/downloads/) environment.

## Download and Installation

This Python library should be consumed in the standard way by running

```pip install sap-document-classification-client```

or adding the library as a dependency of your code in `requirements.txt` file.

## Demo usage

#### Document Classification
To try out the Document classification service using the document classification client
library you can also run the two demo links below:
* Try out DC classification using default model [demo](https://mybinder.org/v2/gh/SAP/document-classification-client/main?filepath=examples%2Fclassification_default_model.ipynb)
* Try out DC training and classification using custom model [demo](https://mybinder.org/v2/gh/SAP/document-classification-client/main?filepath=examples%2Ftrain_and_evaluate_custom_model.ipynb)

#### Document Information Extraction
(to be added)

## Known Issues

Please see the [issues section](https://github.com/SAP/document-classification-client/issues).

## How to obtain support

In case you would like to contribute to this project, ask any questions or get support, please open an issue containing the description of your question or planned contribution in GitHub and we will get in touch.
