[![Gem Version](https://badge.fury.io/rb/ruby-ipfs-api.svg)](https://badge.fury.io/rb/ruby-ipfs-api)
[![Build Status](https://travis-ci.org/tbenett/ruby-ipfs-api.svg?branch=master)](https://travis-ci.org/tbenett/ruby-ipfs-api)
[![Coverage Status](https://coveralls.io/repos/github/tbenett/ruby-ipfs-api/badge.svg?branch=master)](https://coveralls.io/github/tbenett/ruby-ipfs-api?branch=master)

# ipfs-api

> A client library for the IPFS HTTP API, implemented in Ruby.

Summary:

Make sure the Ipfs daemon is running, otherwise
the client will not be able to connect.

You'll get an error `Ipfs::UnreachableDaemon` and the program
execution will stop if daemon is not present.

The client will make a persistent connection to the API.

To access the library from your source file:

```ruby
require 'ipfs_api'
```

> TODO: use a configuration file and/or environment variables to specify the http api url.
Those are hard-coded at the moment :(

## Ipfs::File

This class is intended to manipulate files through Ipfs.

Methods are documented [here](https://www.rubydoc.info/gems/ruby-ipfs-api/Ipfs/File)
