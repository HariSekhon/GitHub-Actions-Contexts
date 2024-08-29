# GitHub Actions Contexts

[![GitHub stars](https://img.shields.io/github/stars/HariSekhon/GitHub-Actions-Contexts?logo=github)](https://github.com/HariSekhon/GitHub-Actions-Contexts/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/HariSekhon/GitHub-Actions-Contexts?logo=github)](https://github.com/HariSekhon/GitHub-Actions-Contexts/network)
[![License](https://img.shields.io/github/license/HariSekhon/GitHub-Actions-Contexts)](https://github.com/HariSekhon/GitHub-Actions-Contexts/blob/master/LICENSE)
[![My LinkedIn](https://img.shields.io/badge/LinkedIn%20Profile-HariSekhon-blue?logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIGZpbGw9IiNmZmZmZmYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+TGlua2VkSW48L3RpdGxlPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPgo=)](https://www.linkedin.com/in/HariSekhon/)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/HariSekhon/GitHub-Actions-Contexts?logo=github)](https://github.com/HariSekhon/GitHub-Actions-Contexts/commits/master)

[![Dump Contexts](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml/badge.svg)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml)

Dumps GitHub Actions contexts for debugging and exploring undocumented fields to be used in advanced GitHub Actions workflows.

Uses my [GitHub-Actions Reusable Workflows Library](https://github.com/HariSekhon/GitHub-Actions) where there is much more interesting and advanced stuff.

## Specific Contexts

Available context information changes depending on the context that triggered the workflow, so you will likely need to check and compare these more specific context dumps:

[![Dump Contexts Push](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=push)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apush) - [Push Contexts](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apush)

[![Dump Contexts Pull Request](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=pull_request&branch=branch_to_trigger_run)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apull_request) - [Pull Request Contexts](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apull_request)

[![Dump Contexts Workflow Dispatch](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=workflow_dispatch)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aworkflow_dispatch) - [Workflow Dispatch Contexts (Manual trigger)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aworkflow_dispatch)

[![Dump Contexts Schedule](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=schedule)](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aschedule) - [Schedule Contexts](https://github.com/HariSekhon/GitHub-Actions-Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aschedule)


#### GitHub Documentation

https://docs.github.com/en/actions/learn-github-actions/contexts#example-printing-context-information-to-the-log
