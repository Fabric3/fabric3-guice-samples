Web App Sample
=====================

Demonstrates using Fabric3 with Guice in a web application.

After building, the WAR can be deployed to any compliant Servlet container:

mvn clean install

The Jetty Maven plugin is supported for testing. However, it must be invoked using the jetty:run-exploded goal:

mvn clean jetty:run-exploded


