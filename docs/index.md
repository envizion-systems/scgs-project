# SCGS Scope document for required REST endpoint facilities

## Internal Infrastructure
The internal SCGS network numbered 10.0.0.n  
The iis server is sitting at http port 80  
To which we've installed the Powerforce REST services

### Invocation of Services

-	Here is the SCGS internal url to the API : http://localhost/cgi-bin/oecgi4.exe/. In this documentation will refer to this as "{BASE_URL}"  

- the ```<shiftid>``` is the internal DB identifier for each shift. This value will be passed to the consumer and must be used in the call back to manipulate the rosters. The shiftid is the required parameter on all ```PUT``` requests into the API.

-	When starting to utilised the Powerforce REST API and test internal connectivity, that all necessary services are started up, run the following URL into a browser :{BASE_URL}/sysusers.  

    - This command requires no authentication, and reaches into the REST interface to confirm end-to-end connectivity.

## Service Authentication

The Powerforce REST API sits behind generic user authentication managed by the client themselves.  

Prior to access being granted to any resource, the end-user must be authorised to the application. This is managed internally to SCGS, by adding a web based user login for the individual user.  

Through this mechanism, all REST requests are able to be audited, authorised and actioned according to the user's level of access.

### TODO
- Ideally the /cgi-bin/oecgi4.exe wants to be hidden as /api/, however the version of the IIS dashbord did not support the creation of 're-mapping'.  
- SCGS IT can internally address this at at later stage.