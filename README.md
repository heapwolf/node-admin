# SYNOPSIS
Build simple modular admin interfaces for node

# DESCRIPTION
Out of the box it does the following things.

 - Manage users and permissions
 - Opt-in secure login over HTTP or HTTPS
 - Automaticly reconnect the client to data sources
 - Provide a simple RPC and REST API for creating modules ([`see this example`][0])

# USAGE
Create an executable script that can start the server.

```
#!/usr/bin/env node
require('admin').Server(require('optimist').argv)
```

Install some interface modules into your project
```
$npm install admin-template
```

[0]:https://github.com/hij1nx/admin-template
