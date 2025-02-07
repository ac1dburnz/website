# godaddy-ddns

![Version: 2.0.11](https://img.shields.io/badge/Version-2.0.11-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: latest](https://img.shields.io/badge/AppVersion-latest-informational?style=flat-square)

Chart to provide a DDNS service for godaddy domains. Uses the GoDaddy REST API to update the given domain's DNS IP address to the public IP address of the host it is executing on. Performs a check every 10 minutes, but you can alter this if you like by modifying /etc/cron.d/godaddy-ddns inside the Chart.

## Chart Sources

- https://github.com/truecharts/charts/tree/master/charts/incubator/godaddy-ddns
- https://github.com/truecharts/containers/tree/master/mirrorgodaddy-ddns

## Available Documentation

- [**Changelog**](CHANGELOG)

- [**Helm Security**](container-security)

- [**Helm Security**](helm-security)

