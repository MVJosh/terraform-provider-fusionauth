# FusionAuth Provider

This provider is used for setting up [FusionAuth](https://fusionauth.io).

For the rendered provider usage documentation, visit the [Terraform Registry](https://registry.terraform.io/providers/gpsinsight/fusionauth/latest/docs).

## Argument Reference

* `api_key` - (Required) The API Key for the FusionAuth instance
* `host` - (Required) Host for FusionAuth instance

## Resources Available

* API Key
* application
* application/{application_id}/role
* email
* entity
* entity grant
* entity type
* entity type permission
* form
* form field
* group
* generic connector
* key
* imported key
* lambda
* identity provider
    - OpenID Connect
    - Google
    - Apple
    - External JWT
    - Facebook
    - SAML v2
    - Sony PSN
    - Steam
    - Twitch
    - Xbox
* themes
* user
* user action
* webhook
* tenants
