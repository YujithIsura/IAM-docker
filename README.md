# IAM-docker


### This repository contains following Docker resources:
- WSO2 Identity Server Dockerfile witch has been linkd with separate openLDAP
- openLDAP Dockerfile
- Docker Compose files to manage those dockerfiles.

       The identity server dockerfile build genaric docker images for deploing identity server in containerized envirenments it includes the ubuntu 16.04, JDK, collection of utility libraries and more importantly some configurations to link new openLDAP to WSO2 identity server. The openLDAP dockerfile includes osixia/openldap 1.2.2
       Docker compose file has been created for managing Dockerfiles, passing envirenment variables, etc. This includes phpldapadmin image as well.. for managing new openLDAP.
       
       
Installation

1. Clone this Repository




