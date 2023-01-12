## Airlock Digital
Airlock Digital enables you to easily create and manage secure application whitelists in dynamically changing computing environments. Unlike signature based file blocking (black listing) such as antivirus, Airlock only allows files it has been instructed to trust, to run. 

This package contains a parser, three dashboards. 

Within the dashboard there are multiple searches/queries that can be used to visualise data ingested from Airlock Digital.

Imperva creates the following comprehensive and detailed logs:
- Security logs
- Access logs

Log integration mode recommended for this package:

[TBA]

For more information on how Airlock Digital can provide valuable data for your security operations please visit [https://www.imperva.com/](https://www.airlockdigital.com/)

## Release Notes

v0.1.0 
- Initial creation

## Package Contents
## Parsers
- Imperva_ApplicationSecurity_CloudWebApplicationFirewall_cef

## Dashboards
- Account Overview
- Search
- WAF Overview

## Use Case:
- SecOps

## Technology Vendor:
Imperva

## Support
Package creator doesn't currently offer support for this package.

## Dependencies
The package uses logs from the following log type: CEF

Please make sure unencrypted CEF is selected when configuring the log forwarding from Imperva.

Package uses 2 files for country code matching and severity level which included within the package.

## Installation
The preferred option for sending logs from Imperva to LogScale is to choose Amazon S3 (available under 'Account Management' in the Imperva CWAF Console). 
Log Shipping from S3 to LogScale can be done in multiple ways, please see the LogScale documentation to ensure the right option is selected for you.

Please ensure logs are using the package parser 'cef' and the correct LogScale token is chosen.

