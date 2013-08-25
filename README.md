MobileSalesTAXRatesLookup
=========================

Cross platform mobile app for sales tax rates lookup. The app has been developed using appery platform.

The main components  for appery project (MobileSalesTAXRatesApperyBackup.zip) are as follows

1. STSServiceCalls.js : Helps make REST service calls (using jquery) from client to Wolterskluwer SalesTaxSaaS(STS)webservices hosted at demo.myspeedtax.com
2. STSMainPageHelper.js : Interacts with the UI and uses into STSServiceCalls.js for  calls to STS.
3. LoginPage :  THe user logs into the application providing STS AccountID, Password and Environment ( DEMO , PROD)
4. MainPage : User can find sales tax using city, state or Zip code.
5. STSConfig : Manage the entity under STS Account to use. Also the user can toggle between DEMO and PROD environment


If you have an android phone , you can use the included apk file to test the app. A dump of Android Eclipse project is
also provided. I havn't opened it up in eclipse as all of my develpment has been done using appery.


NOTES:

1: 
You will need a subscription to Wolterskluwer SalesTaxSaaS before you can test the app.  

You can use the link below to ask for a Demo account

http://tax.cchgroup.com/cforms/taa-contactform.aspx?leadsource=SalesTaxSaaS-SDK&cm_mmc=CCH+Partner+Update+July+12-_-EM-NP-_-graphic-Download+Free+SaaS+Developers+Kit+CFA-_-CCH+Partner+Update%26cm_lm=jessica.balfour@wolterskluwer.com 


2: 
The app has been tested on few Android devices, IE 10.0  and few versions of Firefox and Chrome. 
For direct web access, you will need to  use a browser which supports CORS ( IE 8,9 are too limited and do not work)

Please send me an email at gurleen.randhawa@gmail.com if you have any questions
