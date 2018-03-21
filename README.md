# ws-proxy
web socket to sip proxy

## Using this project as the basis for a SIP over WS B2BUA

This fork is an attempt to use the project as a back to back UA to allow us to
proxy a WS client towards a WS registrar in order do things like send mobile push
notifications on INVITES etc.

Principle modifications from the original are:
- Per session upstream server
- User authentication towards the upstream mediaServer
- WS transport towards the upstream mediaServer
-
