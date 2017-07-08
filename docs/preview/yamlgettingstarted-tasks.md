# YAML getting started - Tasks (internal only, public preview soon)

```yaml
steps:
  - task: Npm@1 # @1 indicates the task version
    name: npm install
    inputs:
      command: install
  - task: Npm@1
    name: npm test
    inputs:
      command: test
```
