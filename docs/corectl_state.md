## corectl state

Explore and manage alternate states

### Synopsis

Explore and manage alternate states

### Options

```
  -h, --help   help for state
```

### Options inherited from parent commands

```
  -a, --app string               Name or identifier of the app
      --certificates string      path/to/folder containing client.pem, client_key.pem and root.pem certificates
  -c, --config string            path/to/config.yml where parameters can be set instead of on the command line
      --context string           Name of the context used when connecting to Qlik Associative Engine
  -e, --engine string            URL to the Qlik Associative Engine (default "localhost:9076")
      --headers stringToString   Http headers to use when connecting to Qlik Associative Engine (default [])
      --json                     Returns output in JSON format if possible, disables verbose and traffic output
      --no-data                  Open app without data
  -t, --traffic                  Log JSON websocket traffic to stdout
      --ttl string               Qlik Associative Engine session time to live in seconds (default "0")
  -v, --verbose                  Log extra information
```

### SEE ALSO

* [corectl](corectl.md)	 - 
* [corectl state add](corectl_state_add.md)	 - Add an alternate states in the current app
* [corectl state ls](corectl_state_ls.md)	 - Print a list of all alternate states in the current app
* [corectl state rm](corectl_state_rm.md)	 - Removes an alternate state in the current app
