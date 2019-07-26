# ![LOGO](logo.png) groupalarm E-Mail API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm E-Mail API API (version 1.15.0).

Generated from: https://app.groupalarm.com/api/v1/email<br/>
Generated at: 2019-07-26T13:59:34+03:00

## API Description

The e-mail service implements all e-mail functions for GroupAlarm<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### List
> Returns all configured alarm-notification email adresses of an user<br/>

*Tags:* `email`

#### Input Parameters
* `owner_id` - _required_ - ID of an user<br/>
* `organization_id` - _optional_ - requesting organization, not required if user accesses his own resources<br/>

### Create
> Creates an email configuration<br/>

*Tags:* `email`

#### Input Parameters
* `organization_id` - _optional_ - requesting organization, not required if user accesses his own resources<br/>

### GetDisabledOrganization
> Returns whether the given organization has disabled this way of alarming or not<br/>

*Tags:* `organizations`

#### Input Parameters
* `organization_id` - _required_ - requesting organization<br/>

### SetDisabledOrganization
> Sets whether the given organization has this way of alarming disabled or not<br/>

*Tags:* `organizations`

#### Input Parameters
* `organization_id` - _required_ - requesting organization<br/>

### Get
> Creates an email configuration<br/>

*Tags:* `email`

#### Input Parameters
* `emailID` - _required_ - ID of an email configuration<br/>
* `organization_id` - _optional_ - requesting organization, not required if user accesses his own resources<br/>

### Update
> Updates an email configuration<br/>

*Tags:* `email`

#### Input Parameters
* `emailID` - _required_ - ID of an email configuration<br/>
* `organization_id` - _optional_ - requesting organization, not required if user accesses his own resources<br/>

### Delete
> Deletes an email configuration<br/>

*Tags:* `email`

#### Input Parameters
* `emailID` - _required_ - ID of an email configuration<br/>
* `organization_id` - _optional_ - requesting organization, not required if user accesses his own resources<br/>

## License

**flow**ground :- Telekom iPaaS / groupalarm-e-mail-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
