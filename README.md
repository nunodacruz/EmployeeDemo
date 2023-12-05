# HR Employee Demo
=======
## Application Details
|               |
| ------------- |
|**Generation Date and Time**<br>Mon Dec 04 2023 10:07:08 GMT+0000 (Coordinated Universal Time)|
|**App Generator**<br>@sap/generator-fiori-elements|
|**App Generator Version**<br>1.11.5|
|**Generation Platform**<br>SAP Business Application Studio|
|**Service Type**<br>SAP System (ABAP On Premise)|
|**Service URL**<br>http://saps09.cloud:443/sap/opu/odata/sap/ZNC_TEST_API_HR_SRV
|**Module Name**<br>employeehr|
|**Application Title**<br>Employee Manage|
|**Namespace**<br>nc|
|**UI5 Theme**<br>sap_horizon|
|**UI5 Version**<br>1.114.0|
|**Enable Code Assist Libraries**<br>False|
|**Enable TypeScript**<br>False|
|**Add Eslint configuration**<br>False|
|**Main Entity**<br>ZNC_HR_EMPLOYEE_SSet|

## employeehr

A Fiori application.

### Starting the generated app

-   This app has been generated using the SAP Fiori tools - App Generator, as part of the SAP Fiori tools suite.  In order to launch the generated app, simply run the following from the generated app root folder:

```
    npm start
```

- It is also possible to run the application using mock data that reflects the OData Service URL supplied during application generation.  In order to run the application with Mock Data, run the following from the generated app root folder:

```
    npm run start-mock
```

#### Pre-requisites:

1. Active NodeJS LTS (Long Term Support) version and associated supported NPM version.  (See https://nodejs.org)

## Back-end Details

-   Report ZNC_MODIFY_EMPLOYEE (transaction ZNC_EMPL) displays and changes the data from custom table ZNC_EMPLOYEE_T