# GitHub Actions Contexts

[![GitHub stars](https://img.shields.io/github/stars/KhulnaSoft/DevX-Actions/tree/master/Contexts?logo=github)](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/KhulnaSoft/DevX-Actions/tree/master/Contexts?logo=github)](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/network)
[![License](https://img.shields.io/github/license/KhulnaSoft/DevX-Actions/tree/master/Contexts)](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/blob/master/LICENSE)
[![My LinkedIn](https://img.shields.io/badge/LinkedIn%20Profile-KhulnaSoft-blue?logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIGZpbGw9IiNmZmZmZmYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+TGlua2VkSW48L3RpdGxlPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPgo=)](https://www.linkedin.com/in/KhulnaSoft/)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/KhulnaSoft/DevX-Actions/tree/master/Contexts?logo=github)](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/commits/master)

[![Dump Contexts](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml/badge.svg)](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml)
[![Markdown](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/markdown.yaml/badge.svg)](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/markdown.yaml)

Dumps GitHub Actions contexts for debugging and exploring undocumented fields to be used in advanced GitHub Actions
workflows.

Uses my [GitHub-Actions Reusable Workflows Library](https://github.com/KhulnaSoft/GitHub-Actions)
where there is much more interesting and advanced stuff.

## Specific Contexts

Available context information changes depending on the context that triggered the workflow,
so you will likely need to check and compare these more specific context dumps:

[![Dump Contexts Push](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=push)](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apush) -
[Push Contexts](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apush)

[![Dump Contexts Pull Request](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=pull_request&branch=branch_to_trigger_run)](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apull_request) -
[Pull Request Contexts](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml?query=event%3Apull_request)

[![Dump Contexts Workflow Dispatch](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=workflow_dispatch)](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aworkflow_dispatch) -
[Workflow Dispatch Contexts (Manual trigger)](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aworkflow_dispatch)

[![Dump Contexts Schedule](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml/badge.svg?event=schedule)](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aschedule) -
[Schedule Contexts](https://github.com/KhulnaSoft/DevX-Actions/tree/master/Contexts/actions/workflows/dump_contexts.yaml?query=event%3Aschedule)

### GitHub Documentation

<https://docs.github.com/en/actions/learn-github-actions/contexts#example-printing-context-information-to-the-log>

## More Core Repos

<!-- OTHER_REPOS_START -->

### Knowledge

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Knowledge-Base&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Knowledge-Base)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Diagrams-as-Code&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Diagrams-as-Code)

<!--

Not support on GitHub Markdown:

<iframe src="https://raw.githubusercontent.com/KhulnaSoft/KhulnaSoft/main/knowledge.md" width="100%" height="500px"></iframe>

Does nothing:

<embed src="https://raw.githubusercontent.com/KhulnaSoft/KhulnaSoft/main/knowledge.md" width="100%" height="500px" />

-->

### DevOps Code

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=DevOps-Bash-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/DevOps-Bash-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=DevOps-Python-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/DevOps-Python-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=DevOps-Perl-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/DevOps-Perl-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=DevOps-Golang-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/DevOps-Golang-tools)

<!--
[![Gist Card](https://github-readme-stats.vercel.app/api/gist?id=f8f551332440f1ca8897ff010e363e03)](https://gist.github.com/KhulnaSoft/f8f551332440f1ca8897ff010e363e03)
-->

### Containerization

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Kubernetes-configs&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Kubernetes-configs)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Dockerfiles&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Dockerfiles)

### CI/CD

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=GitHub-Actions&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/GitHub-Actions)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Jenkins&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Jenkins)

### DBA - SQL

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=SQL-scripts&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/SQL-scripts)

### DevOps Reloaded

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Nagios-Plugins&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Nagios-Plugins)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=HAProxy-configs&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/HAProxy-configs)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Terraform&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Terraform)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Packer-templates&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Packer-templates)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Nagios-Plugin-Kafka&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Nagios-Plugin-Kafka)

### Templates

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Templates&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Templates)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Template-repo&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Template-repo)

### Misc

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Spotify-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Spotify-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=KhulnaSoft&repo=Spotify-playlists&theme=ambient_gradient&description_lines_count=3)](https://github.com/KhulnaSoft/Spotify-playlists)

The rest of my original source repos are
[here](https://github.com/KhulnaSoft?tab=repositories&q=&type=source&language=&sort=stargazers).

Pre-built Docker images are available on my [DockerHub](https://hub.docker.com/u/khulnasoft/).

<!-- 1x1 pixel counter to record hits -->
![](https://hit.yhype.me/github/profile?user_id=2211051)

<!-- OTHER_REPOS_END -->
