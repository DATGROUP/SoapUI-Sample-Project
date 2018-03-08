# SoapUI-Sample-Projects

We test with Soap UI the API of our application.
If you have trouble with request and response of the API, you should use this projects.

SoapUI application Tests
- SD3 Pro
- valuateExpert
- valuateFinance


Steps to use the Soap UI -Projects:
1. Click on the project -> Custom Properties

2. Set your username, signatures etc.
You can change the protocol and hostname for your project.

variables in project: protocol://host/ 

values of variables:  https://www.dat.de/

3. Double-click on Project and then click on the green arrow to run all TestSteps.

If all TestSteps are green then you API works.
If not, then you must look if you have written the wrong logindata
or the faultCode and faultString gives you the right advice what is wrong in your request.

For more information about the API look at the Kompendium on www.dat.de.
