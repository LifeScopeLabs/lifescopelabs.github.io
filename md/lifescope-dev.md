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
    "api_key": "[KEY]"
  },
  "mongodb": {
    "address": "mongodb://[user]:[password]@[url]/live?ssl=true&replicaSet=[lifescope-shards]authSource=admin"
  }
}
~~~

## How to debug:

In Chrome go to: [chrome://inspect/#devices](chrome://inspect/#devices)

Configure > Target: lifescope-api.glitch.me:3001

## GraphQL Playground web interface for API

Example on glitch:
[https://lifescope-api.glitch.me/gql-p/](https://lifescope-api.glitch.me/gql-p/)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTc1MDIzNTAyMCwtMTQ5MDIxNTgzMCwtMT
k2NzIzNjI3OCwtMTg0MTE3MzI2XX0=
-->