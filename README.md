# Go authorization proxy for UPS tracking numbers

This API allows you to add authorization to UPS and provide
authorize free API outside (for example for the web pages).

### Authentication data

Provide authorization data as environment variables.

Var name | Description
---|---
UPS_USERNAME | Your UPS user name
UPS_PASSWORD | Your UPS password
UPS_ACCESS_KEY | Access Key generated on UPS devkit page


### How to run?

Install Go and run:

```
UPS_USERNAME="login" UPS_PASSWORD="pass" UPS_ACCESS_KEY="access" go run *.go
