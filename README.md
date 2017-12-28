Oracle PaaS Service Manager

This document is based on [https://docs.oracle.com/en/cloud/paas/java-cloud/pscli/](https://docs.oracle.com/en/cloud/paas/java-cloud/pscli/)
---


# Installation

## Windows

- chocolatey
- open cmd or powershell as Administrator
- choco install curl
- choco install python3


## Download PSM

REST API Server name
- psm.us.oraclecloud.com
- psm.europe.oraclecloud.com

https://<rest-server>/paas/core/api/v11/cli/<identitydomain>/client

ex, https://psm.us.oraclecloud.com/paas/core/api/v11/cli/aceboss2018/client

curl -X GET -u cloud.admin:CaudAl@8NoiSE -H X-ID-TENANT-NAME:gse00013250 https://psm.us.oraclecloud.com/paas/core/api/v1.1/cli/gse00013250/client -o psmcli.zip