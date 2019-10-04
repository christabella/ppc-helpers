Tools for connecting to Aalto's scientific computing resources
==============================================================

## `fuk`: Kill all processes listening on a port
Usage: `fuk PORT`

## `panko`: Connect to Paniikki computer with lowest load

## `connect-best`: Connect to Maari computer with lowest load

## `get-load[-all]`: Show Maari computers by load
Run on kosh, shows all Maari-A/B computers with no users,
ordered by their CPU load. Example:
```
ppc-helpers/get-load
```

If you want to see all computers and their users, try:

```
ppc-helpers/get-load-all
```

If you have difficulties accessing Maari computers from kosh,
try to renew your Kerberos tickets first:

```
kinit
```

See the course web page for more information:
http://ppc.cs.aalto.fi/

## More information
- https://buildmedia.readthedocs.org/media/pdf/aalto-scicomp/latest/aalto-scicomp.pdf
- https://scicomp.aalto.fi/aalto/paniikki.html
- https://scicomp.aalto.fi/aalto/remoteaccess.html
