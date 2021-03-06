---
date: 2018-08-13T10:55:34Z
title: "jx repository"
slug: jx_repository
url: /commands/jx_repository/
---
## jx repository

Opens the web page for the current git repository in a browser

### Synopsis

Opens the web page for the current git repository in a browser 

You can use the '--url' argument to just display the URL without opening it

```
jx repository [flags]
```

### Examples

```
  # Open the git repository in a browser
  jx repo
  
  # Print the URL of the git repository
  jx repo -u
```

### Options

```
  -b, --batch-mode             In batch mode the command never prompts for user input
      --headless               Enable headless operation if using browser automation
  -h, --help                   help for repository
      --install-dependencies   Should any required dependencies be installed automatically
      --no-brew                Disables the use of brew on MacOS to install or upgrade command line dependencies
  -u, --url                    Only displays and the URL and does not open the browser
      --verbose                Enable verbose logging
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X

###### Auto generated by spf13/cobra on 13-Aug-2018
