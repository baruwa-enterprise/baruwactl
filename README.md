# baruwactl

## A command line tool for the Baruwa REST API

[![Build Status](https://travis-ci.org/baruwa-enterprise/baruwactl.svg?branch=master)](https://travis-ci.org/baruwa-enterprise/baruwactl)
[![codecov](https://codecov.io/gh/baruwa-enterprise/baruwactl/branch/master/graph/badge.svg)](https://codecov.io/gh/baruwa-enterprise/baruwactl)
[![Go Report Card](https://goreportcard.com/badge/github.com/baruwa-enterprise/baruwactl)](https://goreportcard.com/report/github.com/baruwa-enterprise/baruwactl)
[![GoDoc](https://godoc.org/github.com/baruwa-enterprise/baruwactl?status.svg)](https://godoc.org/github.com/baruwa-enterprise/baruwactl)
[![MPLv2 License](https://img.shields.io/badge/license-MPLv2-blue.svg?style=flat-square)](https://www.mozilla.org/MPL/2.0/)

This tool provides commandline access to manage a [Baruwa](https://www.baruwa.com/)
server using the [REST API](https://www.baruwa.com/docs/api/). It is built using the
[Baruwa Golang bindings](https://github.com/baruwa-enterprise/baruwa-go).

```
Usage: baruwactl -k -s COMMAND [arg...]

A cmdline client for the Baruwa REST API.
                     
Options:             
  -k, --api-token    Baruwa API OAUTH Token (env $BARUWA_API_TOKEN)
  -s, --server-url   Baruwa server url (env $BARUWA_API_SERVER)
                     
Commands:            
  user               manage user accounts
  users              list user accounts
  domain             manage domains
  domains            list domains
  organization       manage organizations
  organizations      list organizations
  systemstatus       show system status
                     
Run 'baruwactl COMMAND --help' for more information on a command.
```

## Requirements

* Golang 1.10.x or higher

## Installation

```console
$ go get github.com/baruwa-enterprise/baruwactl
```

## Testing

``make test``

## Contributing

1. Fork it (https://github.com/baruwa-enterprise/baruwactl/fork)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


## License

All code is licensed under the
[MPLv2 License](https://github.com/baruwa-enterprise/baruwactl/blob/master/LICENSE).
