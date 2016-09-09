# ZendDebugger for Mac OS X

ZendDebugger.so 
- PHP 5.5
- PHP 7.0

You can request specific version that you need

## Installation

1. Download the Zend Debugger
2. Copy the file to your Web server in a location that is accessible by the Web server.
3. Add the following lines at the end of your php.ini file:

```ini
[Zend Debugger]
zend_extension=<full_path_to_zend_debugger_extension>
zend_debugger.allow_hosts=<allow_hosts (e.g. 127.0.0.1)>
zend_debugger.expose_remotely=allowed_hosts
```

4. Restart your web server
