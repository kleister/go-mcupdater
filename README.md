# Library for McUpdater

[![Build Status](https://cloud.drone.io/api/badges/kleister/go-mcupdater/status.svg)](https://cloud.drone.io/kleister/go-mcupdater)
[![Join the Matrix chat at https://matrix.to/#/#kleister:matrix.org](https://img.shields.io/badge/matrix-%23kleister%3Amatrix.org-7bc9a4.svg)](https://matrix.to/#/#kleister:matrix.org)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/d499ad4041c945adbd57d5eed0956801)](https://www.codacy.com/app/kleister/go-mcupdater?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=kleister/go-mcupdater&amp;utm_campaign=Badge_Grade)
[![Go Doc](https://godoc.org/github.com/kleister/go-mcupdater?status.svg)](http://godoc.org/github.com/kleister/go-mcupdater)
[![Go Report](http://goreportcard.com/badge/github.com/kleister/go-mcupdater)](http://goreportcard.com/report/github.com/kleister/go-mcupdater)

This repository provides helpers related to Minecraft Updater.


## Development

Make sure you have a working Go environment, for further reference or a guide take a look at the [install instructions](http://golang.org/doc/install.html). This project requires Go >= v1.11 because we are using Go modules. It is also possible to just simply execute the `go get github.com/kleister/go-mcupdater/...` command, but we prefer to use our `Makefile`:

```bash
go get -d github.com/kleister/go-mcupdater/...
cd $GOPATH/src/github.com/kleister/go-mcupdater
make sync gorunpkg clean generate test
```


## Examples

TBD


## Security

If you find a security issue please contact kleister@webhippie.de first.


## Contributing

Fork -> Patch -> Push -> Pull Request


## Authors

* [Thomas Boerger](https://github.com/tboerger)


## License

Apache-2.0


## Copyright

```
Copyright (c) 2018 Thomas Boerger <thomas@webhippie.de>
```
