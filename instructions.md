Get started with CAP
-----------------------------------

Welcome to Node JS Web Starter application that uses the IBM DataCache REST interface!

This sample application demonstrates how to write a Node JS application using IBM DataCache REST interface and deploy it on BlueMix.

1. [Install the cf command-line tool](https://www.ng.bluemix.net/docs/redirect.jsp?name=cf-instructions).
2. [Download the starter application package](https://ace.ng.bluemix.net:443/rest/../rest/apps/7b425fca-6f3b-476e-95fd-b51184554cd4/starter-download)
3. Extract the package and cd to it.
4. Connect to BlueMix:

		cf api https://api.ng.bluemix.net

5. Log into BlueMix:

		cf login -u carlos.arranz@indraempresarial.com
		cf target -o carlos.arranz@indraempresarial.com -s dev
		
6. Deploy your app:

		cf push CAP

7. Access your app: [http://cap.ng.bluemix.net](http://cap.ng.bluemix.net)
