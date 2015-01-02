# magnolia-docker
A repository containing docker images for [Magnolia CMS](http://magnolia-cms.com/).

## The base image
A base image is available as a starting point for any container running Magnolia CMS.

This image is based on Ubuntu 14.10, JDK 7 and Tomcat 8 and includes JDBC drivers for MySQL and PostgreSQL.

It starts automatically an empty Tomcat server and exposes the port 8080.

## Additional images
Additional Dockerfiles are also provided in order to illustrate some common deployment patterns.

### one-author-derby
A straightforward Dockerfile used to illustrate basic usage of the base image.

## Important notes
This images are still in early phase of development and not suited to be used in production. For instance, default Tomcat and JVM settings are still used.