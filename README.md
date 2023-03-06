# RAP_DEMO_01
RAP-Tutorial 01: https://github.com/miltonchandradas/rapdemo

RAP-Tutorial

https://www.youtube.com/watch?v=m1VmXo0HHkY&t=23s
https://github.com/miltonchandradas/rapdemo

Objekte im VID-200

0. Package 									    ZJM_DEMO_JM1
1. Tabelle 							    		zrap_uxteam_5551
2. Interface View 							ZI_UXTEAM_5551
3. Consumption View 						ZC_UXTEAM_5551
4. Metadata extension						ZC_UXTEAM_5551
5. Business Object							The Interface View is already marked as root
											          The Consumption View is already marked as root
6. Behavior Definitions definieren 
	 Behavior Definition für InterfaceView	ZI_UXTEAM_5551(managed)
7. Behavior Definitions implementieren 		zbp_i_uxteam_5551
8. Behavior Projections definieren  			ZC_UXTEAM_5551
9. Service Definition		          				Z_EXPOSE_UXTEAM_5551
10. Service Binding							          ZUI_UXTEAM_V2_5551

## Application Details
|               |
| ------------- |
|**Generation Date and Time**<br>Thu Dec 22 2022 15:25:10 GMT+0000 (Coordinated Universal Time)|
|**App Generator**<br>@sap/generator-fiori-elements|
|**App Generator Version**<br>1.8.3|
|**Generation Platform**<br>SAP Business Application Studio|
|**Template Used**<br>List Report Page V2|
|**Service Type**<br>SAP System (ABAP On Premise)|
|**Service URL**<br>http://vid:44300/sap/opu/odata/sap/ZUI_UXTEAM_V2_5551
|**Module Name**<br>zrap_demo_jm1|
|**Application Title**<br>Demo APP RAP JM1|
|**Namespace**<br>de.varelmann.rapjm1|
|**UI5 Theme**<br>sap_fiori_3|
|**UI5 Version**<br>1.84.29|
|**Enable Code Assist Libraries**<br>False|
|**Enable TypeScript**<br>False|
|**Add Eslint configuration**<br>False|
|**Main Entity**<br>UXTeam|

## zrap_demo_jm1

A Fiori (RAP) application.

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


