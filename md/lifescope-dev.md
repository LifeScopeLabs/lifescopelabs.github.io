# LIFESCOPE Contributor Quickstart

## [Join the developer team](https://lifescope.io/open-source/)

# Developer Setup

## Change your host file
 
 Add the following aliases.
```
127.0.0.1     app.lifescope.io api.lifescope.io xr.lifescope.io static.lifescope.io
```

## Install and run NGINX  

Config in lifescope-api
```
brew install nginx
sudo nginx -p . -c nginx.conf
```
  
## Add Config Files to API, ETL, APP

Add node config files for production variables. 

Such as: 

/config/dev.json  
or
/config/prod.json

~~~
{
  "bitscoop": {
    "api_key": "[key]"
  },
  "mongodb": {
    "address": "mongodb://[user]:[password]@[url]/live?ssl=true&replicaSet=[lifescope-shards]authSource=admin"
  }
}
~~~

## How to debug:

### Run/Prod

NODE_ENV=prod yarn start

### Debug

NODE_ENV=prod yarn debug
NODE_ENV=dev babel-node server.js --inspect-brk=localhost:3333

In Chrome go to: [chrome://inspect/#devices](chrome://inspect/#devices)

Configure > Target: apl.lifescope.io:3333

## GraphQL Playground web interface for API

Example on glitch:
[https://apl.lifescope.io:3333/gql-p/](https://apl.lifescope.io:3333/gql-p/)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI1OTg2MjAzOCwtNjg5NDM2MTYxLDg1ND
g0ODE0NiwxMDE2MzQzODYzLC0xNDkwMjE1ODMwLC0xOTY3MjM2
Mjc4LC0xODQxMTczMjZdfQ==
-->