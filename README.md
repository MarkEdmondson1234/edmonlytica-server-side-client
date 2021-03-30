# Edmonlytica - Server Side Client

Edmonlytica is a proof of concept for making your own digital analytics stream using GTM Server Side and BigQuery.  See the blog post for details:
https://code.markedmondson.me/edmondlytica/

## Dependencies

This is the Client to be imported into GTM Server Side.  It works in conjunction with the Edmonlytica GTM Browser Side Tag and the Edmonlytica GTM Server Side Tag, which need to be installed as well to work.

## Functionality

This collects data at /edmonlytica from the browser side tag, and parses it into the GTM Event format to pass to the GTM Server Side Tag.  It also adds a hashed anonymous ip address to function as a userId/sessionId
