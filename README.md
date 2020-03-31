# awsctx

## Overview
This is the context switch helper for `aws sts assume-role`

## Usage
``` $ source awsctx -h
This is the context switch helper for awscli.

usage:
  awsctx            : show context list or use peco to filter context

  awsctx -h         : show this message

$ source awsctx
- a filter using peco -
Input authenticator's code> xxxxxx
Assume role success to <account name>/<role name>
```

## Install(Recommended)
```
$ git clone https://github.com/m3y/awsctx.git
$ alias awsctx="source /path/to/awsctx/awsctx"
```

## Dependencies
- [awscli v2](https://docs.aws.amazon.com/ja_jp/cli/latest/userguide/install-cliv2-mac.html)
- [peco](https://github.com/peco/peco)
