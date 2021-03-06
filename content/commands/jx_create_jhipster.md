---
date: 2018-08-13T10:55:34Z
title: "jx create jhipster"
slug: jx_create_jhipster
url: /commands/jx_create_jhipster/
---
## jx create jhipster

Create a new JHipster based application and import the generated code into git and Jenkins for CI/CD

### Synopsis

Creates a new JHipster application and then optionally setups CI/CD pipelines and GitOps promotion. 

JHipster is an application generator for gRPC services in Go with a set of tools/libraries. 

This command is expected to be run within your '$GOHOME' directory. e.g. at '$GOHOME/src/github.com/myOrgOrUser/' 

For more documentation about JHipster see: https://www.jhipster.tech/

```
jx create jhipster [flags]
```

### Examples

```
  # Create a JHipster application and be prompted for the folder name
  jx create jhipster
  
  # Create a JHipster application in the myname sub-folder folder
  jx create jhipster myname
```

### Options

```
  -b, --batch-mode                     In batch mode the command never prompts for user input
      --branches string                The branch pattern for branches to trigger CI/CD pipelines on
      --credentials string             The Jenkins credentials name used by the job
      --default-owner string           The default user/organisation used if no user is found for the current git repository being imported (default "someone")
      --dry-run                        Performs local changes to the repo but skips the import into Jenkins X
      --git-api-token string           The git API token to use for creating new git repositories
      --git-provider-url string        The git server URL to create new git repositories inside
      --git-username string            The git username to use for creating new git repositories
      --headless                       Enable headless operation if using browser automation
  -h, --help                           help for jhipster
      --import-commit-message string   Should we override the Jenkinsfile in the project?
      --install-dependencies           Should any required dependencies be installed automatically
      --jenkinsfile string             The name of the Jenkinsfile to use. If not specified then 'Jenkinsfile' will be used
      --list-packs                     list available draft packs
      --name string                    Specify the git repository name to import the project into (if it is not already in one)
      --no-brew                        Disables the use of brew on MacOS to install or upgrade command line dependencies
      --no-draft                       Disable Draft from trying to default a Dockerfile and Helm Chart
      --no-import                      Disable import after the creation
      --no-jenkinsfile                 Disable defaulting a Jenkinsfile if its missing
      --org string                     Specify the git provider organisation to import the project into (if it is not already in one)
  -o, --output-dir string              Directory to output the project to. Defaults to the current directory
      --pack string                    The name of the pack to use
      --verbose                        Enable verbose logging
```

### SEE ALSO

* [jx create](/commands/jx_create/)	 - Create a new resource

###### Auto generated by spf13/cobra on 13-Aug-2018
