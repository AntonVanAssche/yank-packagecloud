# Delete from Packagecloud.io

This action encapsulates the setup to delete any package from PackageCloud.io.


## Inputs
```yaml
inputs:
  package-name:
    description: Name of the package to upload
    required: true
  packagecloud-username:
    description: The username to use on PackageCloud.io
    required: true
  packagecloud-repo:
    description: The repository to user
    required: true
  packagecloud-distrib:
    description: The distribution/version this package is located at
    required: false
  packagecloud-token:
    description: The Token with yank access
    required: true
```
