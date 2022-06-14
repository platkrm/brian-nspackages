# simplns

## Description
Simple namespace blueprint

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] simplns`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree simplns`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init simplns
kpt live apply simplns --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
