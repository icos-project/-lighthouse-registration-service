# Controller-Lighthouse registration service
This service runs as a sidecar to the shell backend and periodically refreshes the controller's address entry. It needs to be supplied with a set of environment variables to run:

```
CLIENTID=<id of the client configured in keycloak>
SECRET=<secret for client id>
REALM=<realm configured in keycloak>
PASSWORD=<password for the keycloak user>
USER=<keycloak user>
KEYCLOAK=https://<keycloak address.tld>
LIGHTHOUSE=http://<lighthouse address>/api/v3
ADV_ADDRESS=<controller address to advertise, including port>
ADV_NAME=<controller name to advertise>
```


# Legal
The lighthouse registration service is released under the Apache license 2.0.
Copyright © 2022-2024 Marc Michalke, Technische Universität Braunschweig. All rights reserved.

🇪🇺 This work has received funding from the European Union's HORIZON research and innovation programme under grant agreement No. 101070177.
