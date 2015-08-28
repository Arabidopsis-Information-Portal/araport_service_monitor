# Araport Service Monitor

Module for monitoring the services which make up the core of the Araport
Platform.

## Services Monitored

The services that this module provides status monitoring of are:

Service   | Method
--------- | ------
Agave     | `agave_status` module
ADAMA     | ADAMA `/status` API
ThaleMine | HTTP check
JBrowse   | HTTP check
WebApollo | HTTP check
Github    | [Github Status API][1]


[1]: https://status.github.com/api
