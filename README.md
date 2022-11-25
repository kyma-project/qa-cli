# Kyma QA CLI

## Overview
The Kyma QA CLI is a command line tool which facilitates quality-related activities for the Kyma developers during the software development life-cycle. It provides a set of commands and flags for:
* measuring code quality metrics
* identifying potential problematic code fragments
* assess compliance with the quality baselines

It will also provide integration with the Quality Dashboard API and publish the quality metrics for further trend analysis and visualisation.

## Prerequisites
The tool is a standalone application designed for MacOS and Linux systems.

## Installation
The application will be available via Homebrew. 

## Usage
Once you have installed the CLI, you can use its commands and flags to run the codebase analysis over the codebase.

For the commands and flags to work, they must follow this syntax:

```sh
kyma-qa {COMMAND} {FLAGS}
```

* **{COMMAND}** specifies the operation to be performed, such as test coverage assessment, etc.
* **{FLAGS}** specifies optional flags you can use to enrich your command.

## Development
### Build from Sources

Alternatively, you can also build the Kyma CLI from the sources:

To clone the Kyma CLI repository, run:
```sh
mkdir -p $GOPATH/src/github.com/kyma-project/
git clone git@github.com:kyma-project/qa-cli.git $GOPATH/src/github.com/kyma-project/
```
