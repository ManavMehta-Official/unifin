# Commit Guide

## Format of commit message
```
[type]: [subject]
```

### 1. Type
`feat` : Feature
`fix` : Bug Fixes
`docs` : Documentation
`style` : Formatting & Linting
`refactor` : Restructuring code without changing external behavior
`test` : Adding tests
`chore` : Maintenance
`init` : Initial Commit
`rearrange` : Files moved, added, deleted
`update` : versions, library compatibilty

### 2. Subject
Summary of the changes made.

Definition:
> The subject line contains a succinct description of the change to the logic.


* Must be present tense.
* Written in imperative
* First letter is not capitalized
* Does not end with `.`

## Examples

```
feat: added navigation component
```

```
docs: added README.md file
```

```
fix: submit button not rendering
```

```
rearrange: data.json moved to constants directory
```