# cord-pipeline-samples

Please refer to [Cord Help](https://help.cord.tools/cord/Cord-Pipes-User-Documentation.1657209225.html) for further details and complete documentations.

This repository contains example files for the different features and use cases of the cord tools pipelines.

The configuration file within your repository could be named:

* cord.yml
* cord.yaml
* aemcloud.yml (soon to be deprecated)
* aemccloud.yaml (soon to be deprecated)

Basic example could be find in [cord.yml](cord.yml)


## Features

Cord Pipelines offer a set of features that will enhance your CI experience by allowing you to control how and when pipelines are executed.

* [Branch Filtering](branch-filtering/cord.yml)
* [Manual Triggering](manual-trigger/cord.yml)
* [Cache configuration](cache/cord.yml)
* [Environment variables](environment-variables/cord.yml)


## Pipes

Pipes are builtin out of the box steps that will boost your pipelines with minimum configuration. Allowing users to take advantage of some of the features included in Cord Tools, such as: On Demand Environments, automated deploys, ...

* [On demand environments](pipes/on-demand-environment/cord.yml)
* [Automated deploys](pipes/deploy/cord.yml)

## Migrate for the old build

We initially supported a single `build` step that was used to build, test and deploy your code. On the new cord tools, we are migrating away from that and instead allowing users to have multi-steps (multi-stage) pipelines that provide more visibility and control over the CI/CD process.

* [Decrecated config](deprecated/aemcloud.yml) 