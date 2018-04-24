# LIFESCOPE Contributor Quickstart

## [Join the developer team](https://lifescope.io/open-source/)

# Developer Setup

## Change your host file
  
```
127.0.0.1     app.lifescope.io api.lifescope.io xr.lifescope.io static.lifescope.io
```

## Add Config Files to approproate libraries

Add node config files for production variables. 
Such as: 

/config/dev.json  
or
/config/prod.json
~~~

{

"bitscoop": {

"api_key": "E870025AA3B544A292E4ADA9D10846E1"

},

"mongodb": {

"address": "mongodb://bitscoop:Demo1234@lifescope-shard-00-00-rjljd.mongodb.net:27017,lifescope-shard-00-01-rjljd.mongodb.net:27017,lifescope-shard-00-02-rjljd.mongodb.net:27017/live?ssl=true&replicaSet=lifescope-shard-0&authSource=admin"

}

} 
{
MONGODB_URI=" "

BITSCOOP_API_KEY="key"
}
~~~

## How to debug:

In Chrome go to: [chrome://inspect/#devices](chrome://inspect/#devices)

Configure > Target: lifescope-api.glitch.me:3001

## GraphQL Playground web interface for API

Example on glitch:
[https://lifescope-api.glitch.me/gql-p/](https://lifescope-api.glitch.me/gql-p/)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3MTMxOTQ1NDMsLTE0OTAyMTU4MzAsLT
E5NjcyMzYyNzgsLTE4NDExNzMyNl19
-->