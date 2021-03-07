# debuglog

DebugLog.IO client to get real-time logs right in your console!
https://debuglog.io

Also an example implementation for DebugLog.IO API usage.

## Installation

This module needs to be installed globally so use the `-g` flag when installing:

```
npm install -g debuglog.io-client
```

## Usage

```
$ debuglog 

Usage: debuglog --account <account> --device <deviceudid> --apikey <key> [options]


  Options:

    -V, --version                 output the version number
    -a, --account <account>       account to connect
    -k, --apikey <key>            API key to connect
    -s, --server <serveraddress>  optional DebugLog.IO server address.
    -p, --port <portnumber>       optional port number for DebugLog.IO server.
    -d, --device <deviceudid>     device UDID to connect
    -v, --verbose                 enable verbose logging
    -h, --help                    output usage information

```

## License

MIT