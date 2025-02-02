---
type: docs
title: "rad bicep publish CLI reference"
linkTitle: "rad bicep publish"
slug: rad_bicep_publish
url: /reference/cli/rad_bicep_publish/
description: "Details on the rad bicep publish Radius CLI command"
---
## rad bicep publish

Publish a Bicep file to an OCI registry.

### Synopsis

Publish a Bicep file to an OCI registry.
This command compiles and publishes a local Bicep file to a remote Open Container Initiative (OCI) registry, such as Azure Container Registry, Docker Hub, or GitHub Container Registry, to later be used as a Bicep registry or for Radius Recipes.
Before publishing, it is expected the user runs docker login (or similar command) and has the proper permission to push to the target OCI registry.
For more information on Bicep modules visit https://learn.microsoft.com/azure/azure-resource-manager/bicep/modules
		

```
rad bicep publish [flags]
```

### Examples

```

# Publish a Bicep file to an Azure container registry
rad bicep publish --file ./redis-test.bicep --target br:myregistry.azurecr.io/redis-test:v1
		
```

### Options

```
      --file string     path to the local Bicep file, relative to the current working directory.
  -h, --help            help for publish
      --target string   remote OCI registry path, in the format 'br:HOST/PATH:TAG'.
```

### Options inherited from parent commands

```
      --config string   config file (default "$HOME/.rad/config.yaml")
  -o, --output string   output format (supported formats are json, table) (default "table")
```

### SEE ALSO

* [rad bicep]({{< ref rad_bicep.md >}})	 - Manage bicep compiler

