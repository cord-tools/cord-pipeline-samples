# cord-pipeline-samples

This repository contains example files for the different features and use cases of Cord Tools Pipelines.

Please refer to [Cord Help](https://help.cord.tools/cord/Cord-Pipes-User-Documentation.1657209225.html) for further details and complete documentation.

## cord.yml

Cord Tools Pipelines requires a configuration file at the root of your repository. It will search for a file with one of the following names, stopping at the first file found.

1. cord.yml
2. cord.yaml
3. aemcloud.yml (deprecated)
4. aemccloud.yaml (deprecated)

You can find examples of both [cord.yml](cord.yml) and the [deprecated aemcloud.yml](deprecated/aemcloud.yml) in this repository for reference.


## Features

Cord Pipelines offers a set of features that will enhance your CI/CD experience by allowing you to control how and when pipelines are executed.

* [Branch Filtering](branch-filtering/cord.yml)
* [Manual Triggering](manual-trigger/cord.yml)
* [Cache configuration](cache/cord.yml)
* [Environment variables](environment-variables/cord.yml)


## Pipes

Pipes are out-of-the-box steps which will boost the effectiveness of your pipelines with minimal configuration. You can use these built-in steps to leverage other features included in Cord Tools, such as: On Demand Environments, automated deploys, and more.

* [On demand environments](pipes/on-demand-environment/cord.yml)
* [Automated deploys](pipes/deploy/cord.yml)

## Changes from previous releases

Previous iterations of this toolchain supported a single `build` step that was used to build, test and deploy code. We are migrating away from that to allow users to use multi-step/multi-stage pipelines that provide more flexibility, visibility and control over their paritcular CI/CD processes.