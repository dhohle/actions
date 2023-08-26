# actions

## Getting Started

- Event
  - Pull Request
  - Push (branch)
  - Issue
    - Created
    - Closed
    - ...

An event triggers a `workflow`, each workflow needs to have at least one `job`. Each job has one or multiple `step`s.
A step can be either and `action` (not the same as a `GitHub action`) or a `shell command`.  
Each job is related to one runner (e.g. different jobs run on different runners)  
Steps cannot run in parallel.  
GitHub hosted runners come in `Ubuntu`, `Windows`, or `Mac`

## Workflow Syntax
GitHub actions are stored in the root dir (don't know whether that is mandatory) in the `.github` folder.

Workflows need to be saved under `.github/workflows`

Find publicly available [GitHub Actions](https://github.com/marketplace?type=actions)
```
```