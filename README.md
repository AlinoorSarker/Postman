Postman

Introduction | What is POSTMAN

What is Postman?
Postman is a Google Chrome app for interacting with HTTP APIs. It presents you with a friendly GUI for constructing requests and reading responses. The people behind Postman also offer an add-on package called Jetpacks, which includes some automation tools and, most crucially, a Javascript testing library.

API Client<br/>
A client library, sometimes called a helper library, is a set of code that application developers can add to their development projects. It provides chunks of code that do the basic things an application needs to do in order to interact with the API.
develop, test, share, document APIs

Step 1: Open Postman webpage - https://www.getpostman.com/<br/>
Step 2: Create a free account<br/>
Step 3: Activate the account<br/>
Step 4: Download and install postman app<br/>

Professional API Testing using POSTMAN - Tips & Tricks<br/>
01. Import Requests<br/>
always try to import request from the browser rather creating
Use the Import button-> Paste Raw Text (Paste your CURL copied from chrome)
02. Use Create Collections<br/>
Create Collection for the 
03. Write Test Cases<br/>
04. Use folder Structure for the Different req.<br/>
05. JSON Schema validation<br/>
06. Leverage Postman BDD<br/>
07. Control test workflows<br/>
08. Use Environment & Dynamic Variables<br/>

<b>API calls Collection include mainly three things:</b><br/>

HTTP headers<br/>
HTTP Request  (POST,GET,PUT,DELETE )<br/>
Status Code/ Response Code<br/>

Status Code/Response Code - There are many status/response code, from them we can verify the response.<br/>

200 - OK, The request was successful.<br/>
201 - Created, The request was successful and data was created.<br/>
204 - No Content, The response is empty.<br/>
400 - Bad Request, The request could not be understood or was missing required parameters.<br/>
401 – Unauthorized, Authentication failed or user does not have permissions for the requested operation.<br/>
403 - Forbidden, Access denied.<br/>
404 - Not Found, Data was not found.<br/>
405 - Method Not Allowed, Requested method is not supported for the specified resource.<br/>
500 - Internal Server Error.<br/>
503 - Service Unavailable, The service is temporary unavailable.<br/>



<b>How to set and get VARIABLES through SCRIPTING</b><br/>

1. How to get variables through scripts<br/>
2. How to set variables through scripts<br/>
//pm.variables.get();<br/>
//pm.variables.set();<br/>
//pm.globals.get();<br/>
//pm.globals.set();<br/>
//pm.environment.get();<br/>
//pm.environment.set();<br/>


<b>How to DEBUG</b><br/>
1. How to debug with Postman Console<br/>
2. How to open Postman Console window<br/>
3. Information shown on Postman Console window<br/>
4. Clear logs<br/>
5. console.log()<br/>
    console.info()<br/>
    console.warn()<br/>
    console.error()<br/>
6. App Debug Logs : Developer - DevTools<br/>

