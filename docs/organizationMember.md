# organization-member

An organization member is an individual with access to an organization.

## Actions

### `createOrUpdate`

`heroku.organizations({organization_name}).members().createOrUpdate({attributes}, {callback});`

Method | Path
--- | ---
PUT | /organizations/{organization_name}/members

### `delete`

`heroku.organizations({organization_name}).members({app_email_or_id}).delete({callback});`

Method | Path
--- | ---
DELETE | /organizations/{organization_name}/members/{app_email_or_id}

### `list`

`heroku.organizations({organization_name}).members().list({callback});`

Method | Path
--- | ---
GET | /organizations/{organization_name}/members

