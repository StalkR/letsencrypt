# Simple Let's Encrypt tool in Go

[![Build Status][1]][2]

Given:

- a list of domains
- a directory where to put the http-01 acme challenges for those domains
- a directory where to save the certificates and keys

It handles everything from creation to update before it expires.
Call it with cron regularly (e.g. weekly) and you are all set.

A temporary account key is created as needed and not saved.

Bugs, comments, questions: create a [new issue][3].

[1]: https://github.com/StalkR/letsencrypt/actions/workflows/build.yml/badge.svg
[2]: https://github.com/StalkR/letsencrypt/actions/workflows/build.yml
[3]: https://github.com/StalkR/letsencrypt/issues/new
