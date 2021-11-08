# <p align="center" width="100%"> <img src="./logo.png" width="250" height="250"> </p> 
# <p align="center" width="100%"> Sage People API OIH Connector </p>

## Description

A generated OIH connector for the Sage People API API (version 4.8).

Generated from: https://{domain}/services/apexrest/spapi/v4<br/>
Generated at: 2021-11-08T16:59:04+01:00

## API Description

The Sage People API provides a means to extract data from the Sage People application.<br/>
<br/>
# Authorization<br/>
<br/>
You need a bearer token to authenticate with Sage People API, see the Get Started section for more information.<br/>
<br/>
# Headers<br/>
<br/>
Requests to Sage People API need the following header: `Accept: application/json`<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>
<br/>
&nbsp;<br/>

## Authorization

Supported authorization schemes:
- Bearer Token

## Actions

### Get Employee by Id
> Retrieve a single employee<br/>

*Tags:* `Employee`

#### Input Parameters
* `employeeId` - _required_ - Required parameter to identify an employee<br/>

### Add Pay Details
> Add new pay details for a single employee<br/>

*Tags:* `Employee`

#### Input Parameters
* `employeeId` - _required_ - Required parameter to identify an employee<br/>

## License

: sage-people<br/>
                    <br/>

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
