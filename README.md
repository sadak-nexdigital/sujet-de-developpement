# sujet-de-developpement

API SYSTEM sys-ontime-flightstats-api:

The API system interacts directly with data ressources to retrieve flights data and render it to the prc-api-ontime.

GET/FLIGHTS:

This endpoint will trigger flow getFlights which obtains a customer list of flights based on flightstats-api.

GET/{flightID}:

This endpoint will trigger flow getFlights which obtains a customer a flight specification using flight id based on flightstats-api.

APIs security considerations:

This Process API is meant to be deployed to CloudHub and managed using the API Platform Manager.

Running on premise:

In this section we detail the way you should run your Anypoint project on your computer.

Where to Download Anypoint Studio and Mule ESB:

First thing is where to get the tools.

You can download Anypoint Studio from this https://www.mulesoft.com/lp/dl/studio

You can download Mule ESB from this https://anypoint.mulesoft.com/login/signup?apintent=generic

Importing an Anypoint project into Studio:
Anypoint Studio offers several ways to import a project into the workspace, for instance:

Anypoint Studio generated Deployable Archive (.zip)
Anypoint Studio Project from External Location
Maven-based Mule Project from pom.xml
Mule ESB Configuration XML from External Location


Running on Studio:
Once you have imported you Anypoint project into Anypoint Studio you need to follow these steps to run it:

Locate the package explorer, in src/main/mule, right click on Anypoint project (sys-ontime-flightstats-api) folder
Hover you mouse over "Run as"
Click on "Mule Application"
