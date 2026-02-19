# Home folder

Some configuration files to speed the setup of new systems.

Copy these files to your $HOME folder

## Taskfile.yml

For use with [Taskfile](../tools/taskfile/README.md), it contains some tasks for linting and testing python and golang projects.

```
task: Available tasks for this project:
* lint:           Detect project type and run linter
* lint-fix:       Detect project type and run linter
* test:           Run tests on the project
```

## .commitlint.yaml

Used in a pre-commit git hook, you can install using: 

```bash
go install github.com/conventionalcommit/commitlint@latest
```

## .pre-commit.config.yaml

