---
layout: page
title: Tools
---

The following tools will help you adopt the BuildingSync<sup>®</sup> schema.

#### Use Case Selection Tool

[The BuildingSync Use Case Selection Tool](https://selectiontool.buildingsync.net) is a web application allowing users to browse and validate instances of BuildingSync for various use cases. There is no login needed for the website. If you have new use cases that you would like to be added, then contact [info@buildingsync.net](mailto:info@buildingsync.net) with your proposed use case and someone will be in touch with you.

#### File Validation

Currently, there are two methods for file validation: 

1. Download the most recent version of the [schema](../documents/schema) and use a tool an XML authoring tool to validate the XML instances. This method is preferred for developers who are actively working on creating BuildingSync XML instances which are valid.
1. There is an option to add a valid BuildingSync XML to the schema's continuous integration (CI) system. This will allow for the file to be tested during every schema change/pull request to ensure backward compatibility and validity. To add a BuildingSync XML instance to the CI, follow these steps:
	1. If you do not have a Github account, then sign up for one on [Github](https://github.com)
	1. Sign into Github and navigate to [BuildingSync Schema's Github page](https://github.com/buildingsync/schema)
	1. Fork the repository and add new files to the [examples folder](https://github.com/BuildingSync/schema/tree/develop/examples)
	1. Create a pull request which will trigger the validation workflow. If it passes, then the BuildingSync team will accept the pull request. If it does not pass, the BuildingSync team will work with you to understand the issues/use case. Note: The new file will be validated on every commit/change to the BuildingSync schema ensuring that all provided user's files pass successfully and are backward compatible.


