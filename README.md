# GitHub Actions Contexts

[![Dump Contexts](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml/badge.svg)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml)

Dumps GitHub Actions contexts for debugging and exploring undocumented fields to be used in advanced GitHub Actions workflows.

Uses my [GitHub-Actions Reusable Workflows Library](https://github.com/HariSekhon/GitHub-Actions) where there is much more interesting and advanced stuff.

## Specific Contexts

Available context information changes depending on the context that triggered the workflow, so you will likely need to check and compare these more specific context dumps:

[![Dump Contexts Push](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=push)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apush) - [Push Contexts](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apush)

[![Dump Contexts Pull Request](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=pull_request)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apull_request) - [Pull Request Contexts](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apull_request)

[![Dump Contexts Workflow Dispatch](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=workflow_dispatch)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aworkflow_dispatch) - [Workflow Dispatch Contexts (Manual trigger)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aworkflow_dispatch)

[![Dump Contexts Schedule](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=schedule)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aschedule) - [Schedule Contexts](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aschedule)


#### GitHub Documentation

https://docs.github.com/en/actions/learn-github-actions/contexts#example-printing-context-information-to-the-log
