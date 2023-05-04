# JBoss EAP 7.4 + PostgreSQL

This Helm chart packages an application with [JBoss EAP 7.4](https://www.redhat.com/en/technologies/jboss-middleware/application-platform) and PostgreSQL to be deployed on OpenShift.

It deploys a persistent PostgreSQL database as well as a Jakarta EE application running in JBoss EAP 7.4 that connects to the database.

The source code of the Helm chart and the Jakarta EE application is at https://github.com/jboss-eap-up-and-running/eap7-with-postgres