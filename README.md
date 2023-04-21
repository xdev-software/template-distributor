[![Distribution Workflow](https://img.shields.io/github/actions/workflow/status/xdev-software/template-distributor/distribute.yml?branch=master&label=distribution)](https://github.com/xdev-software/template-distributor/actions/workflows/distribute.yml?query=branch%3Amaster)
# Template Distributor

Distributes Templates to Template repos
(as it's not possible to run workflows inside Template Repos)

## Overview
Templates are distributed with the following hierarchy:

* [base-template](https://github.com/xdev-software/base-template)
  * [standard-maven-template](https://github.com/xdev-software/standard-maven-template)
    * [vaadin-addon-template](https://github.com/xdev-software/vaadin-addon-template)
  * [xdev-swing-framework-template](https://github.com/xdev-software/xdev-swing-framework-template)
