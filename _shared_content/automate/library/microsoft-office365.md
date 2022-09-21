# Microsoft Office365

![Microsoft Office365](/assets/playbooks/library/microsoft-office365.png){ align=right width=150 }

Microsoft Office 365 is an online service, providing the Microsoft Office Products.

## Configuration

This module accepts no configuration.

## Triggers

### Fetch events from MessageTrace API (deprecated)

Fetch events for MessageTrace API

#### Arguments

| Name      |  Type   |  Description  |
| --------- | ------- | --------------------------- |
| `frequency` | `integer` | Batch frequency in seconds |
| `account_name` | `string` | The account name to use |
| `account_password` | `string` | The password associated with the account |
| `intake_server` | `string` | Server of the intake server (e.g. 'https://intake.sekoia.io') |
| `intake_key` | `string` | Intake key to use when sending events |


### Fetch events from MessageTrace API (OAuth)

Fetch events for MessageTrace API (OAuth)

#### Arguments

| Name      |  Type   |  Description  |
| --------- | ------- | --------------------------- |
| `tenant_id` | `string` | The ID of the corresponding Tenant |
| `client_id` | `string` | The account name to use |
| `client_secret` | `string` | The password associated with the account |
| `frequency` | `integer` | Batch frequency in seconds |
| `intake_server` | `string` | Server of the intake server (e.g. 'https://intake.sekoia.io') |
| `intake_key` | `string` | Intake key to use when sending events |


## Extra

Module **`Microsoft Office365` v2.0.5**