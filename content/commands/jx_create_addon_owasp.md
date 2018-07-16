---
date: 2018-07-16T15:52:02Z
title: "jx create addon owasp"
slug: jx_create_addon_owasp
url: /commands/jx_create_addon_owasp/
---
## jx create addon owasp

Create a owasp addon for dynamic security checks

### Synopsis

Creates the Owasp dyanmic security testing addon

```
jx create addon owasp [flags]
```

### Examples

```
  # Create the kubeless addon in the kubeless namespace
  jx create addon owasp
```

### Options

```
  -l, --backoff-limit int32   The backoff limit: how many times to retry the job before considering it failed) to run in the Job (default 2)
  -h, --help                  help for owasp
  -i, --image string          The OWASP image to use to run the ZA Proxy baseline scan (default "owasp/zap2docker-live:latest")
```

### SEE ALSO

* [jx create addon](/commands/jx_create_addon/)	 - Creates an addon

###### Auto generated by spf13/cobra on 16-Jul-2018