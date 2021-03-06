# Invitation Manager for the IO App

## Environment variables

Those are all Environment variables needed by the application:

| Variable name       | Description                                                   | type    | default                                            |
|---------------------|---------------------------------------------------------------|---------|----------------------------------------------------|
| IO_IM_DEFAULT_LOGGER_LEVEL   | The log level used for Winston logger                         | loglevel | info                                              |
| IO_IM_PROCESSING_INTERVAL_S | The interval, in seconds, between two processing | number | 3600 |
| IO_IM_GOOGLE_CLIENT_EMAIL | The client email of the google service-account | string | |
| IO_IM_GOOGLE_PRIVATE_KEY_PATH | The path of the google service-account private key | string | |
| IO_IM_GOOGLE_SPREADSHEET_ID | The id of the google spreadsheet where invitations are stored | string | |  
| IO_IM_GOOGLE_BETA_GROUP_KEY | The key of the google beta group | string | |
| IO_IM_APP_STORE_CONNECT_PRIVATE_KEY_ID | The key id of the app store connect account | string | |
| IO_IM_APP_STORE_CONNECT_PRIVATE_KEY_PATH | The path of the app store connect private key | string | |
| IO_IM_APP_STORE_CONNECT_ISSUER_ID | The issuer id of the app store connect account | string | |
| IO_IM_APP_STORE_CONNECT_BETA_GROUP_ID | The id of the testflight beta group | string | |