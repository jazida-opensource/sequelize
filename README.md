# Sequelize

[![npm version](https://badgen.net/npm/v/sequelize)](https://www.npmjs.com/package/sequelize)
[![Build Status](https://github.com/sequelize/sequelize/workflows/CI/badge.svg)](https://github.com/sequelize/sequelize/actions?query=workflow%3ACI)

<!-- [![codecov](https://badgen.net/codecov/c/github/sequelize/sequelize/main?icon=codecov)](https://codecov.io/gh/sequelize/sequelize) -->

[![npm downloads](https://badgen.net/npm/dm/sequelize)](https://www.npmjs.com/package/sequelize)
[![Merged PRs](https://badgen.net/github/merged-prs/sequelize/sequelize)](https://github.com/sequelize/sequelize)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

Sequelize is a promise-based [Node.js](https://nodejs.org/en/about/) [ORM tool](https://en.wikipedia.org/wiki/Object-relational_mapping) for [Postgres](https://en.wikipedia.org/wiki/PostgreSQL), [MySQL](https://en.wikipedia.org/wiki/MySQL), [MariaDB](https://en.wikipedia.org/wiki/MariaDB), [SQLite](https://en.wikipedia.org/wiki/SQLite) and [Microsoft SQL Server](https://en.wikipedia.org/wiki/Microsoft_SQL_Server). It features solid transaction support, relations, eager and lazy loading, read replication and more.

Sequelize follows [Semantic Versioning](http://semver.org) and supports Node v10 and above.

New to Sequelize? Take a look at the [Tutorials and Guides](https://sequelize.org/master). You might also be interested in the [API Reference](https://sequelize.org/master/identifiers).



### Fork notes

- Fixed mssql error: `The column 'Id' was specified multiple times for 'Table'.`
  - Issue: https://github.com/sequelize/sequelize/issues/11700
  - Pull request: https://github.com/jazida-opensource/sequelize/pull/1
    
    Would you like to contribute? Read [our contribution guidelines](https://github.com/sequelize/sequelize/blob/main/CONTRIBUTING.md) to know more. There are many ways to help.



### v6 Release

You can find the detailed changelog [here](https://github.com/sequelize/sequelize/blob/main/docs/manual/other-topics/upgrade-to-v6.md).

## Note: Looking for maintainers!

Recently, a bigger part of the former core maintainers (thanks to all your hard work!) have been rather busy. Hence, the available time to look after our beloved ORM has been shrinking and shrinking drastically, generating a great chance for you:

We are looking for more core maintainers who are interested in improving/fixing our TypeScript typings, improving the documentation, organizing issues, reviewing PRs, streamlining the overall code base and planning the future roadmap.

If that sounds interesting to you, please reach out to us on [our Slack channel](https://sequelize.slack.com/) by sending a direct message to *Pedro A P B*. If you don't have access, get yourself an invite automatically via [this link](http://sequelize-slack.herokuapp.com/). We are looking forward to meet you!

## Installation

```sh
$ npm i sequelize # This will install v6

# And one of the following:
$ npm i pg pg-hstore # Postgres
$ npm i mysql2
$ npm i mariadb
$ npm i sqlite3
$ npm i tedious # Microsoft SQL Server
```

## Documentation

- [v6 Documentation](https://sequelize.org/master)
- [v5/v4/v3 Documentation](https://sequelize.org)
- [Contributing](https://github.com/sequelize/sequelize/blob/main/CONTRIBUTING.md)

## Responsible disclosure

If you have security issues to report, please refer to our [Responsible Disclosure Policy](https://github.com/sequelize/sequelize/blob/main/SECURITY.md) for more details.

## Resources

- [Changelog](https://github.com/sequelize/sequelize/releases)
- [Slack Inviter](http://sequelize-slack.herokuapp.com/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/sequelize.js)

### Tools

- [CLI](https://github.com/sequelize/cli)
- [With TypeScript](https://sequelize.org/master/manual/typescript.html)
- [Enhanced TypeScript with decorators](https://github.com/RobinBuschmann/sequelize-typescript)
- [For GraphQL](https://github.com/mickhansen/graphql-sequelize)
- [For CockroachDB](https://github.com/cockroachdb/sequelize-cockroachdb)
- [Plugins](https://sequelize.org/master/manual/resources.html)

### Translations

- [English](https://sequelize.org/master) (OFFICIAL)
- [中文文档](https://github.com/demopark/sequelize-docs-Zh-CN) (UNOFFICIAL)

