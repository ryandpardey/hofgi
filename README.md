# Hofgi: HTTP for Gophers

Package `hofgi` is a [Go][] client library for interacting with
[RESTful APIs][].  Hofgi was forked from the napping library. The purpose is to support multiple formats, at the time of writing namely JSON and XML.


## Status

[![Drone Build Status](https://drone.io/github.com/jmcvetta/napping/status.png)](https://drone.io/github.com/jmcvetta/napping/latest)
[![Travis Build Status](https://travis-ci.org/jmcvetta/napping.png)](https://travis-ci.org/jmcvetta/napping)
[![Coverage Status](https://coveralls.io/repos/jmcvetta/restclient/badge.png)](https://coveralls.io/r/jmcvetta/napping)

Used by, and developed in conjunction with, [Neoism][].


## Installation 

### Requirements

Hofgi requires Go 1.2 or later.


### Development

```
go get github.com/ryandpardey/hofgi
```
## License

This is Free Software, released under the terms of the [GPL v3][].


[Go]:           http://golang.org
[RESTful APIs]: http://en.wikipedia.org/wiki/Representational_state_transfer#RESTful_web_APIs
[Requests]:     http://python-requests.org
[GPL v3]:       http://www.gnu.org/copyleft/gpl.html
[auth-token]:   https://github.com/jmcvetta/napping/blob/master/examples/github_auth_token/github_auth_token.go
[Neoism]:       https://github.com/jmcvetta/neoism
