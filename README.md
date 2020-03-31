# arctx

## Overview
This is the context switch helper for `aws sts assume-role`

## Usage
``` $ source arctx -h
This is the context switch helper for 'aws sts assume-role'

usage:
  arctx            : show context list or use peco to filter context

  arctx -h         : show this message

$ source arctx
- a filter using peco -
Input authenticator's code> xxxxxx
Assume role success to <account name>/<role name>
```

## Install(Recommended)
```
$ git clone https://github.com/m3y/arctx.git
$ alias arctx="source /path/to/arctx/arctx"
```

## Dependencies
- [awscli v2](https://docs.aws.amazon.com/ja_jp/cli/latest/userguide/install-cliv2-mac.html)
- [peco](https://github.com/peco/peco)


----
Inspired by [kubectx](https://github.com/ahmetb/kubectx)
