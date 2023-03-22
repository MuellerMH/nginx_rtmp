
# Nginx with RTMP Dockerfile

This Dockerfile installs and configures Nginx with RTMP module on Ubuntu 14.04.2.

## Installation

- Clone this repository
- Build the docker image with docker build -t nginx-rtmp .
- Run the docker container with docker run -d -p 80:80 -p 443:443 -p 1935:1935 nginx-rtmp

## Configuration

The Nginx configuration file nginx.conf is included in the Dockerfile and can be modified to suit your needs.

## Exposed Ports

This image exposes ports 80, 443 and 1935 for HTTP, HTTPS and RTMP protocols.

## Working Directory
The working directory for this image is set to /usr/local/nginx.

## Default Command
The default command for this image is /usr/local/nginx/sbin/nginx -c /usr/local/nginx/conf/nginx.conf.

## Autor

Dieses Programm wurde von [Manuel Engelhardt](https://about.me/manuelmueller) entwickelt, einem erfahrenen Softwareentwickler und Gründer der Firma ITDevOps.de.

[ITDevOps.de](https://ITDevOps.de) ist ein Unternehmen, das sich auf die Entwicklung von Softwarelösungen und die Bereitstellung von IT-Beratungsdiensten spezialisiert hat. Mit einem Team von erfahrenen Entwicklern und Beratern bietet [ITDevOps.de](https://ITDevOps.de) seinen Kunden eine breite Palette von Dienstleistungen an, darunter Softwareentwicklung, Systemadministration, DevOps-Implementierung, Cloud-Beratung und mehr.

[Manuel Engelhardt](https://about.me/manuelmueller) ist ein erfahrener Entwickler, der über umfangreiche Kenntnisse in den Bereichen Softwareentwicklung, Systemadministration, Cloud-Computing und DevOps verfügt. In seiner Freizeit trägt Manuel Engelhardt zur Open-Source-Community bei und teilt sein Wissen durch Konferenzvorträge und Schulungen.

## License
This Dockerfile and associated scripts are licensed under the MIT License.
