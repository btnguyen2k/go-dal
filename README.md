# godal

[![Go Report Card](https://goreportcard.com/badge/github.com/btnguyen2k/godal)](https://goreportcard.com/report/github.com/btnguyen2k/godal)
[![PkgGoDev](https://pkg.go.dev/badge/github.com/btnguyen2k/godal)](https://pkg.go.dev/github.com/btnguyen2k/godal)
[![Actions Status](https://github.com/btnguyen2k/godal/workflows/godal/badge.svg)](https://github.com/btnguyen2k/godal/actions)
[![codecov](https://codecov.io/gh/btnguyen2k/godal/branch/master/graph/badge.svg?token=0L23UTJHOZ)](https://codecov.io/gh/btnguyen2k/godal)

Generic Database Access Layer library for Go (Golang).

Latest release [v0.2.4](RELEASE-NOTES.md).

## Feature overview

- Interface for generic business object (BO) and data access object (DAO).
- Generic implementation of BO.
- Generic implementation of [MongoDB](https://www.mongodb.com/) DAO.
- Generic implementation of [AWS DynamoDB](https://aws.amazon.com/dynamodb/) DAO.
- Generic implementation of [`database/sql`](https://golang.org/pkg/database/sql/) DAO:
  - MSSQL
  - MySQL
  - Oracle
  - PostgreSQL

## Installation

```go
go get github.com/btnguyen2k/godal
```

## Usage & Documentation

- [GoDoc](https://pkg.go.dev/github.com/btnguyen2k/godal?tab=doc)
- [Examples](examples/)
- [Wiki](https://github.com/btnguyen2k/godal/wiki)


## Contributing

Use [Github issues](https://github.com/btnguyen2k/godal/issues) for bug reports and feature requests.

Contribute by Pull Request:

1. Fork `Godal` on github (https://help.github.com/articles/fork-a-repo/)
2. Create a topic branch (`git checkout -b my_branch`)
3. Implement your change
4. Push to your branch (`git push origin my_branch`)
5. Post a pull request on github (https://help.github.com/articles/creating-a-pull-request/)


## License

MIT - see [LICENSE.md](LICENSE.md).
