# [LIFESCOPE-API](https://github.com/LifeScopeLabs/lifescope-api)

## [Repository](https://github.com/LifeScopeLabs/lifescope-api)

### (development phase, high priority)

The LIFESCOPE API is a universal platform backend. There are two components to the API; a GraphQL-based API for CRUD operations on the LIFESCOPE data schema and a REST API for login/logout/signup and connection OAuth workflow.

# Workflows

## Connection Workflow
 1. Choose a provider and grant permissions
 2. Create an OAuth connection to provider
 3. Approve OAuth permission and complete connection

## Signup Workflow
1. Complete the connection wf with first provider
2. Create a user and a login session

## Login Workflow
1. Complete the connection wf but do not create a new connection
2. Lookup user and create a login session

# API Endpoints
* Exposes objects of the data schema for CRUD operations in GraphQL
* Exposes the connection, signup, and login workflows as GraphQL endpoints

## Providers
* Facebook
* Twitter
* Pinterest
* Dropbox
* Steam
* Reddit
* Spotify
* GitHub
* Instagram
* Google
* **Slice - In Development**
* **FitBit - In Development**

# Data Schema

![gqlschema]

## connections
  * auth
    * status
      * authorized
      * complete
 * enabled
 * endpoint_data
   * XXX
  * frequency
  * last_run
  * permissions
    * ETC...
* provider_id
* provider_name
* remote_connection_id
* status
* user_id

## events

* connection
* contact_interaction_type
* contacts
* content
* context
* created
* datetime
* identifier
* provider
* provider_name
* source
* type
* updated
* user_id

## contacts
* avatar_url
* connection
* created
* handle
* identifier
* name
* provider_name
* remote_id
* updated
* user_id

## content
* connection
* created
* embed_content
* embed_format
* embed_thumbnail
* embedded_format
* identifier
* mimeType
* mimetype
* owner
* provider_name
* remote_id
* tagMasks
* text
* thumbnail
* title
* type
* updated
* url
* user_id


## locations
* connection
* created
* datetime
* estimated
* geo_format
* geolocation
* identifier
* updated
* user_id

## providers
* alt_sources
  * likes
    * description
    * enabled_by_default
    * mapping
    * name
* remote_map_id
* sources
  * todo 

## searches
## sessions
## tags
## things
## users

# Requirements

- Add WSS support for subscriptions
  - https://github.com/apollographql/subscriptions-transport-ws
  - https://github.com/graphql-compose/graphql-compose
   - https://github.com/graphql-compose/graphql-compose-mongoose

# Dependencies

* [graphql-compose](https://github.com/graphql-compose/graphql-compose)
* [graphql-compose-mongoose](https://github.com/graphql-compose/graphql-compose-mongoose)
* Vue/Nuxt

[gqlschema]:https://lifescopelabs.github.io/assets/diagrams/LifeScopeSchema.png
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTQxNTk3MjY0LC0xNTg1MjQ5ODU3XX0=
-->