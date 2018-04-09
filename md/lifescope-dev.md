# LIFESCOPE Developer Setup

How to devlop node repositories.

We suggest using [Glitch](https://glitch.com).

## Change your host file

[https://app.lifescope.io/](https://app.lifescope.io/)		[localhost or glitch]

## Set your environment variables:
 
MONGODB_URI="mongodb://[user]:[password]@[url]/live?ssl=true&replicaSet=[lifescope-shards]authSource=admin"

BITSCOOP_API_KEY="key"

## How to debug:

In Chrome go to: [chrome://inspect/#devices](chrome://inspect/#devices)

Configure > Target: lifescope-api.glitch.me:3001

## GraphQL Playground web interface for API

Example on glitch:
[https://lifescope-api.glitch.me/gql-p/](https://lifescope-api.glitch.me/gql-p/)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5NjcyMzYyNzgsLTE4NDExNzMyNl19
-->