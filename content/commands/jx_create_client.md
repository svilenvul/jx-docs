---
date: 2019-02-28T09:29:45Z
title: "jx create client"
slug: jx_create_client
url: /commands/jx_create_client/
---
## jx create client

Creates clients for Custom Resources

### Synopsis

Generates clients, OpenAPI spec and API docs for custom resources. 

Custom resources are defined using Go structs. 

Available generators include: 

  * jx create client openapi # Generates OpenAPI specs, required to generate API docs and clients other than Go  
  * jx create client docs # Generates API docs from the OpenAPI specs  
  * jx create client go # Generates a Go client directly from custom resources

```
jx create client [flags]
```

### Examples

```
  
```

### Options

```
  -h, --help   help for client
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx create](/commands/jx_create/)	 - Create a new resource
* [jx create client docs](/commands/jx_create_client_docs/)	 - Creates client docs for Custom Resources
* [jx create client go](/commands/jx_create_client_go/)	 - Creates Go client for Custom Resources
* [jx create client openapi](/commands/jx_create_client_openapi/)	 - Creates OpenAPI specs for Custom Resources

###### Auto generated by spf13/cobra on 28-Feb-2019
