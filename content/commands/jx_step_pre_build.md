---
date: 2018-07-05T17:13:11Z
title: "jx step pre build"
slug: jx_step_pre_build
url: /commands/jx_step_pre_build/
---
## jx step pre build

Performs actions before a build happens in a pipeline

### Synopsis

This pipeline step performs pre build actions such as ensuring that a docker registry is available in the cloud

```
jx step pre build [flags]
```

### Examples

```
  jx step post build ${DOCKER_REGISTRY}/someorg/myapp
```

### Options

```
  -h, --help           help for build
  -i, --image string   The image name that is about to be built
```

### SEE ALSO

* [jx step pre](/commands/jx_step_pre/)	 - pre step actions

###### Auto generated by spf13/cobra on 5-Jul-2018