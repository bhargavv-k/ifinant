## Next CIDR Block
Every time we create new environment the CIDR block below needs to be updated. This would primarily be job of Duplo team.
```
10.244.0.0/16
```

## Global Protect & Perimeter81 IP Addresses

### Global Protect

| Region             | IP Address      |
|--------------------|-----------------|
| US South East - 01 | 134.238.204.233 |
| US South East - 02 | 134.238.204.199 |
| India South - 01   | 130.41.59.201   |
| India South - 02   | 130.41.59.200   |
| India West - 01    | 134.238.16.225  |
| India West - 02    | 134.238.16.25   |
| Peru - 01          | 130.41.99.30    |
| Peru - 02          | 130.41.99.155   |

### Perimeter81

| Region             | IP Address      |
|--------------------|-----------------|
| USA                | 173.255.242.190 |
| India              | 68.183.81.250   |
| Latin America      | 64.176.7.8      |

## Non-Prod Environments

| Environment       | AWS Account Name | AWS Account Number | Duplo Infra    | Region        | VPC CIDR          | NAT Gateway IP     | Duplo Console URL                                       | OpenVPN IP          |
|-------------------|------------------|--------------------|----------------|---------------|-------------------|--------------------|---------------------------------------------------------|---------------------|
| dev01             | inf-dev-001      | 524172451985       | nonprod01      | us-east-2     | 10.221.0.0/16     | 18.216.104.39      | [duplo-nonprod](https://duplo.nonprod.infinant.com/)    | https://13.58.7.130 | 
| qa02              | inf-dev-001      | 524172451985       | qa             | us-east-2     | 10.222.0.0/16     | 13.58.58.239       | [duplo-nonprod](https://duplo.nonprod.infinant.com/)    | https://13.58.7.130 |
| sutton-uat        | inf-dev-001      | 524172451985       | uat            | us-east-2     | 10.224.0.0/16     | 18.189.5.80        | [duplo-nonprod](https://duplo.nonprod.infinant.com/)    | https://13.58.7.130 |
| thread-uat        | inf-dev-001      | 524172451985       | thread-uat     | us-east-2     | 10.227.0.0/16     | 3.130.52.44        | [duplo-nonprod](https://duplo.nonprod.infinant.com/)    | https://13.58.7.130 |
| dev02             | inf-dev-001      | 524172451985       | dev02          | us-east-2     | 10.237.0.0/16     | 18.117.201.169     | [duplo-nonprod](https://duplo.nonprod.infinant.com/)    | https://13.58.7.130 |
| qa1               | inf-dev-001      | 524172451985       | qa1            | us-east-2     | 10.241.0.0/16     | 3.136.123.174      | [duplo-nonprod](https://duplo.nonprod.infinant.com/)    | https://13.58.7.130 |


## Sandbox Environment

| Environment       | AWS Account Name | AWS Account Number | Duplo Infra    | Region        | VPC CIDR          | NAT Gateway IP     | Duplo Console URL                                       | OpenVPN IP          |
|-------------------|------------------|--------------------|----------------|---------------|-------------------|--------------------|---------------------------------------------------------|---------------------|
| sandbox           | inf-sbx-001      | 471074506674       | sandbox001     | us-east-2     | 10.222.0.0/16     | 3.135.41.235       | [duplo-sandbox](https://duplo.sandbox.infinant.com/)    | https://3.15.96.137 |


## Performance Environment

| Environment       | AWS Account Name | AWS Account Number | Duplo Infra    | Region        | VPC CIDR          | NAT Gateway IP     | Duplo Console URL                                       | OpenVPN IP            |
|-------------------|------------------|--------------------|----------------|---------------|-------------------|--------------------|---------------------------------------------------------|-----------------------|
| performance       | inf-perf-001     | 940482439549       | perf           | us-east-2     | 10.239.0.0/16     | 3.12.157.233       | [duplo-performance](https://duplo.perf.infinant.com/)   | https://18.216.110.67 |


## Hotfix Environment

| Environment       | AWS Account Name | AWS Account Number | Duplo Infra    | Region        | VPC CIDR          | NAT Gateway IP     | Duplo Console URL                                       | OpenVPN IP          |
|-------------------|------------------|--------------------|----------------|---------------|-------------------|--------------------|---------------------------------------------------------|---------------------|
| hotfix            | inf-hotfix-001   | 970547335041       | hotfix         | us-east-2     | 10.237.0.0/16     | 18.223.9.104       | [duplo-hotfix](https://duplo.hotfix.infinant.com/)      | https://3.147.99.86 |


## Production Environments

| Environment         | AWS Account Name   | AWS Account Number | Bank Name                | Duplo Infra    | Region        | VPC CIDR          | NAT Gateway IP     | Duplo Console URL                                             | OpenVPN IP            |
|---------------------|--------------------|--------------------|--------------------------|----------------|---------------|-------------------|--------------------|---------------------------------------------------------------|-----------------------|
| thread-prod         | thread-prd-001     | 381492051689       | Thread Bank              | prod01         | us-east-2     | 10.229.0.0/16     | 3.132.4.90         | [duplo-thread-prod](https://duplo.thread.infinant.com/)       | https://3.141.223.144 |
| cbt-prod            | cbt-prd-001        | 730335537968       | Community Bank & Trust   | cbtprod1       | us-east-2     | 10.236.0.0/16     | 13.58.130.15       | [duplo-cbt-prod](https://duplo.cbt.infinant.com/)             | https://3.142.176.137 |
| sutton-prod         | sutton-prd-001     | 471112641449       | Sutton Bank              | prod01         | us-east-2     | 10.228.0.0/16     | 3.18.30.195        | [duplo-sutton-prod](https://duplo.sutton.infinant.com/)       | https://3.132.40.178  |
| legend-prod         | legend-prd-001     | 975050278593       | Legend Bank              | legendprd1     | us-east-2     | 10.233.0.0/16     | 52.14.134.223      | [duplo-legend-prod](https://duplo.legend.infinant.com/)       | https://3.13.66.107   |
| cubi-prod           | cubi-prd-001       | 650251714626       | Customers Bank           | cubiprod       | us-east-2     | 10.238.0.0/16     | 18.217.23.15       | [duplo-cubi-prod](https://duplo.cubi.infinant.com/)           | https://3.16.116.108  |
| fbol-prod           | fbol-prd-001       | 794038242169       | FBOL Bank                | fbolprod       | us-east-2     | 10.240.0.0/16     | 3.134.251.27       | [duplo-fbol-prod](https://duplo.fbol.infinant.com/)           | https://3.22.84.176   |
| emprise-prod        | emprise-prd-001    | 017868794534       | Emprise Bank             | empriseprod    | us-east-2     | 10.242.0.0/16     | TODO               | [duplo-emprise-prod](https://duplo.emprise.infinant.com/)     | https://3.141.92.6    |
| rockpoint-prod      | rockpoint-prd-001  | 655497436170       | Rockpoint Bank           | rockpointprod  | us-east-2     | 10.243.0.0/16     | TODO               | [duplo-rockpoint-prod](https://duplo.rockpoint.infinant.com/) | https://18.189.210.10 |



# Single Pane View

## Interlace Services

| Name                           | DB Required? | Ingress Required? | Frontend Service? | Dev01 | Dev02 | QA1   | QA02  | Thread-UAT | Sutton-UAT | Sandbox | Hotfix | Perf | Sutton-Prod | Thread-Prod | Legend-Prod | CBT-Prod | CUBI-Prod | FBOL-Prod | Emprise-Prod | Rockpoint-Prod |
|--------------------------------|--------------|-------------------|-------------------|-------|-------|-------|-------|------------|------------|---------|--------|------|-------------|-------------|-------------|----------|-----------|-----------|--------------|----------------|
| **account-opening**            | Yes          |                   |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **accounts**                   |              | Yes               | Yes               | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **accounts-cubix**             |              |                   |                   | Yes   | Yes   | Yes   | Yes   |            |            | Yes     |        |      |             |             |             |          | Yes       |           |              |                |
| **accounts-fiserv**            |              |                   |                   | Yes   | Yes   | Yes   | Yes   |            | Yes        | Yes     | Yes    |      | Yes         |             |             |          |           |           |              |                |
| **accounts-statements**        |              |                   |                   | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         |          |           | Yes       |              | Yes            |
| **accounts-statements-hc3**    |              |                   |                   | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         |          |           | Yes       |              | Yes            |
| **ach-preprocessor**           |              | Yes               |                   | Yes   | Yes   | Yes   | Yes   |            |            | Yes     | Yes    | Yes  |             |             | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **ach-sutton**                 | Yes          | Yes               | Yes               | Yes   | Yes   | Yes   | Yes   |            | Yes        | Yes     | Yes    |      | Yes         |             |             |          |           |           |              |                |
| **audit**                      |              |                   |                   |       | Yes   | Yes   | Yes   |            |            | Yes     | Yes    |      |             |             | Yes         | Yes      |           |           |              |                |
| **cards**                      |              | Yes               | Yes               | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         |             |          |           | Yes       | Yes          | Yes            |
| **coarse-api**                 |              | Yes               |                   | Yes   | Yes   | Yes   | Yes   |            |            | Yes     | Yes    | Yes  |             |             |             | Yes      |           |           |              |                |
| **comply-advantage**           |              |                   |                   |       | Yes   | Yes   | Yes   |            |            | Yes     |        |      |             |             |             |          |           |           | Yes          |                |
| **customer-kyc-sardine**       |              | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         |          |           | Yes       |              | Yes            |
| **customers**                  |              | Yes               | Yes               | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **documents**                  | Yes          | Yes               | Yes               | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      |           | Yes       |              | Yes            |
| **fedlink**                    | Yes          |                   |                   | Yes   | Yes   |       |       |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **fees**                       | Yes          | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **fraud-monitoring-sardine**   |              |                   |                   | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      |           | Yes       |              | Yes            |
| **iav-validifi**               |              |                   |                   | Yes   | Yes   | Yes   | Yes   |            |            | Yes     | Yes    | Yes  |             |             |             | Yes      |           |           |              |                |
| **iav-yodlee**                 |              |                   |                   | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         |          |           | Yes       |              | Yes            |
| **intuit**                     |              |                   |                   | Yes   | Yes   | Yes   | Yes   | Yes        |            |         |        |      |             | Yes         |             |          |           |           |              |                |
| **manager-cards**              | Yes          |                   |                   | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         |             |          |           | Yes       |              | Yes            |
| **manager-casemgmt**           | Yes          | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **manager-monitoring**         | Yes          |                   |                   | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **manager-notifications**      | Yes          | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **manager-scheduling**         | Yes          | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **manager-tenant-users**       | Yes          | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **manager-transaction-events** | Yes          | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **manager-translations**       | Yes          | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **moneymovement**              | Yes          | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **payments**                   |              | Yes               | Yes               | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **platform**                   |              | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **rdc**                        |              | Yes               | Yes               | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     |        |      |             |             |             |          |           |           |              |                |
| **rdc-ensenta**                |              | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     |        |      |             |             |             |          |           |           |              |                |
| **reports**                    | Yes          | Yes  	 	        |    	 	        | Yes   | Yes   | Yes   | Yes   |            |            | Yes     |        | Yes  |             |             |             |          |           | Yes       | Yes          | Yes            |
| **transfers**                  |              | Yes               | Yes               | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **universal-payments**         |              | Yes               | Yes               | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **virtual-accounts**           | Yes          | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **virtual-customers**          | Yes          | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **virtual-ledger**             | Yes          | Yes               |                   | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      |           | Yes       | Yes          | Yes            |


## Interlace Cards

| Name                             | DB Required?    | Ingress Required? | OP Required? | Dev01 | Dev02 | QA1   | QA02  | Thread-UAT | Sutton-UAT | Sandbox | Hotfix | Perf | Sutton-Prod | Thread-Prod | Legend-Prod | CBT-Prod | CUBI-Prod | FBOL-Prod | Emprise-Prod | Rockpoint-Prod |
|----------------------------------|-----------------|-------------------|--------------|-------|-------|-------|-------|------------|------------|---------|--------|------|-------------|-------------|-------------|----------|-----------|-----------|--------------|----------------|
| **service-core-bank**            | cardservicesdb  | Yes               | Yes          | Yes   | Yes   |       | Yes   | Yes        |            |         | Yes    |      |             |             |             |          |           |           |              |                |
| **service-core-bank-gateway**    | cardservicesdb  | Yes               | Yes          | Yes   | Yes   |       | Yes   | Yes        |            |         | Yes    |      |             |             |             |          |           |           |              |                |
| **service-core-bank-scheduled**  | cardservicesdb  |                   | Yes          | Yes   | Yes   |       | Yes   | Yes        |            |         | Yes    |      |             |             |             |          |           |           |              |                |
| **service-core-bank-async**      | cardservicesdb  |                   | Yes          | Yes   | Yes   |       | Yes   | Yes        |            |         | Yes    |      |             |             |             |          |           |           |              |                |


## Interlace Console

| Name                        | Dev01 | Dev02 | QA1   | QA02  | Thread-UAT | Sutton-UAT | Sandbox | Hotfix | Perf | Sutton-Prod | Thread-Prod | Legend-Prod | CBT-Prod | CUBI-Prod | FBOL-Prod | Emprise-Prod | Rockpoint-Prod |
|-----------------------------|-------|-------|-------|-------|------------|------------|---------|--------|------|-------------|-------------|-------------|----------|-----------|-----------|--------------|----------------|
| **console-admin**           | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-api-keys**        | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-app-management**  | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-backoffice**      | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-dashboard**       | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-insights**        | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-login-provider**  | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-onboarding**      | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    |      | Yes         | Yes         | Yes         | Yes      |           |           |              |                |
| **console-root-config**     | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-shared**          | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-sidebar**         | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-topbar**          | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-virtual-banking** | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **console-webhooks**        | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |


## Interlace Studio

| Name                 | DB Required    | Ingress Required | OP Required? | Dev01 | Dev02 | QA1   | QA02  | Thread-UAT | Sutton-UAT | Sandbox | Hotfix | Perf | Sutton-Prod | Thread-Prod | Legend-Prod | CBT-Prod | CUBI-Prod | FBOL-Prod | Emprise-Prod | Rockpoint-Prod |
|----------------------|----------------|------------------|--------------|-------|-------|-------|-------|------------|------------|---------|--------|------|-------------|-------------|-------------|----------|-----------|-----------|--------------|----------------|
| **data-dictionary**  |                |                  |              | Yes   |       |       |       |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **descriptor**       |                | Yes              |              | Yes   |       |       |       |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **flow**             |                | Yes              |              | Yes   |       |       |       |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **project**          |                | Yes              |              | Yes   |       |       |       |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **view**             |                | Yes              |              | Yes   |       |       |       |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **widget**           |                | Yes              |              | Yes   |       |       |       |            |            |         |        |      |             |             |             |          |           |           |              |                |


## Mobile Web

| Name                 | DB Required?    | Ingress Required? | OP Required? | Dev01 | Dev02 | QA1   | QA02  | Thread-UAT | Sutton-UAT | Sandbox | Hotfix | Perf | Sutton-Prod | Thread-Prod | Legend-Prod | CBT-Prod | CUBI-Prod | FBOL-Prod | Emprise-Prod | Rockpoint-Prod |
|----------------------|-----------------|-------------------|--------------|-------|-------|-------|-------|------------|------------|---------|--------|------|-------------|-------------|-------------|----------|-----------|-----------|--------------|----------------|
| **mobile-web**       |                 | Yes               | Yes          |       | Yes   |       | Yes   |            |            | Yes     |        |      |             |             |             |          |           |           |              |                |
| **mobile-web-app**   |                 | Yes               |              |       | Yes   |       | Yes   |            |            | Yes     |        |      |             |             |             |          |           |           |              |                |


## Interlace Serverless Lambdas

| Name                                       | Dev01 | Dev02 | QA1   | QA02  | Thread-UAT | Sutton-UAT | Sandbox | Hotfix | Perf | Sutton-Prod | Thread-Prod | Legend-Prod | CBT-Prod | CUBI-Prod | FBOL-Prod | Emprise-Prod | Rockpoint-Prod |
|--------------------------------------------|-------|-------|-------|-------|------------|------------|---------|--------|------|-------------|-------------|-------------|----------|-----------|-----------|--------------|----------------|
| **cloudwatch-notification**                | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **interlace-console-send-email**           | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **interlace-search-tenant**                | Yes   | Yes   |       |       |            |            | Yes     | Yes    |      |             |             |             |          |           |           |              |                |
| **openapi-automation**                     | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **stream-qldb-events**                     | Yes   |       | Yes   | Yes   | Yes        | Yes        | Yes     |        |      |             | Yes         | Yes         | Yes      |           |           |              |                |
| **sutton-sftp-download**                   | Yes   |       |       |       |            | Yes        |         |        |      | Yes         |             |             |          |           |           |              |                |
| **sutton-sftp-upload**                     | Yes   |       |       |       |            | Yes        |         |        |      | Yes         |             |             |          |           |           |              |                |
| **interlace-sftp-fedfile-download-lambda** | Yes   | Yes   |       |       | Yes        | Yes        | Yes     | Yes    |      |             |             | Yes         | Yes      |           |           |              |                |
| **interlace-sftp-fedfile-upload-lambda**   | Yes   | Yes   |       |       | Yes        | Yes        | Yes     | Yes    |      |             |             | Yes         | Yes      |           |           |              |                |


## S3 Buckets

| Name                             | Dev01 | Dev02 | QA1   | QA02  | Thread-UAT | Sutton-UAT | Sandbox | Hotfix | Perf | Sutton-Prod | Thread-Prod | Legend-Prod | CBT-Prod | CUBI-Prod | FBOL-Prod | Emprise-Prod | Rockpoint-Prod |
|----------------------------------|-------|-------|-------|-------|------------|------------|---------|--------|------|-------------|-------------|-------------|----------|-----------|-----------|--------------|----------------|
| **file-transfer**                | Yes   | Yes   | Yes   | Yes   |            | Yes        | Yes     | Yes    | Yes  | Yes         |             |             | Yes      | Yes       |           |              |                |
| **openapi-automation**           | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      | Yes       | Yes       | Yes          | Yes            |
| **user-documents**               | Yes   | Yes   | Yes   | Yes   | Yes        | Yes        | Yes     | Yes    | Yes  | Yes         | Yes         | Yes         | Yes      |           | Yes       |              | Yes            |
| **wire-incoming**                | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      |           | Yes       |              | Yes            |
| **wire-outgoing**                | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      |           | Yes       |              | Yes            |
| **wire-staging**                 | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      |           | Yes       |              | Yes            |
| **wire-processed**               |       |       |       |       |            |            | Yes     | Yes    | Yes  |             |             |             | Yes      |           | Yes       |              | Yes            |
| **ach-incoming**                 | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **ach-outgoing**                 | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **ach-processed**                | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **data-extracts**                | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         | Yes         |          |           | Yes       | Yes          | Yes            |
| **intrafi-incoming**             | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     |        | Yes  |             | Yes         |             |          |           |           |              |                |
| **intrafi-outgoing**             | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     |        | Yes  |             | Yes         |             |          |           |           |              |                |
| **intrafi-processed**            | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     |        | Yes  |             | Yes         |             |          |           |           |              |                |
| **irs-outgoing**                 | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         |             |          |           |           |              |                |
| **irs-processed**                | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         |             |          |           |           |              |                |
| **revenue-outgoing**             | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         |             |          |           |           |              |                |
| **revenue-processed**            | Yes   | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             | Yes         |             |          |           |           |              |                |
| **settlement-outgoing**          | Yes   | Yes   | Yes   | Yes   |            |            | Yes     | Yes    | Yes  |             |             | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **settlement-processed**         | Yes   | Yes   | Yes   | Yes   |            |            | Yes     | Yes    | Yes  |             |             | Yes         | Yes      |           | Yes       | Yes          | Yes            |
| **lockbox-outgoing**             | Yes   | Yes   | Yes   | Yes   |            |            | Yes     | Yes    | Yes  |             |             |             | Yes      |           |           |              |                |
| **lockbox-incoming**             | Yes   | Yes   | Yes   | Yes   |            |            | Yes     | Yes    | Yes  |             |             |             | Yes      |           |           |              |                |
| **lockbox-processed**            | Yes   | Yes   | Yes   | Yes   |            |            | Yes     | Yes    | Yes  |             |             |             | Yes      |           |           |              |                |
| **loan-pool-documents-outgoing** |       | Yes   | Yes   | Yes   |            |            | Yes     | Yes    | Yes  |             |             |             | Yes      |           |           |              |                |
| **card-settlement-incoming**     |       | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             |             |             |          |           |           |              |                |
| **card-settlement-staging**      |       | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             |             |             |          |           |           |              |                |
| **card-settlement-processed**    |       | Yes   | Yes   | Yes   | Yes        |            | Yes     | Yes    | Yes  |             |             |             |          |           |           |              |                |
| **data-ingestion**               |       | Yes   | Yes   | Yes   |            |            | Yes     | Yes    | Yes  |             |             |             |          | Yes       |           |              |                |


## Cron Jobs
Note: this is not complete, still being updated

| Name                                | Dev01  | Dev02  | QA1   | QA02 | Thread-UAT | Sutton-UAT | Sandbox | Hotfix | Perf | Sutton-Prod | Thread-Prod | Legend-Prod | CBT-Prod  | CUBI-Prod | FBOL-Prod    | Emprise-Prod | Rockpoint-Prod |
|-------------------------------------|--------|--------|-------|------|------------|------------|---------|--------|------|-------------|-------------|-------------|-----------|-----------|--------------|--------------|----------------|
| **baseload-update-cron**            | Yes    | Yes    | Yes   | Yes  | Yes        | Yes        | Yes     | Yes    |      |             |             |             |           |           |              |              |                |
| **sftp-download-cron-&lt;bank&gt;** | Yes    | Yes    | Yes   | Yes  | Yes        | Yes        | Yes     | Yes    |      |             |             | Yes         | Yes       | Yes       | Yes          | Yes          |                |
| **sftp-upload-cron-&lt;bank&gt;**   | Yes    | Yes    | Yes   | Yes  | Yes        | Yes        | Yes     | Yes    |      |             |             | Yes         |           | Yes       | Yes          | Yes          |                |


## Glue Jobs

| Name                                               | Dev01 | Dev02 | QA1  | QA02 | Thread-UAT | Sutton-UAT | Sandbox | Hotfix | Perf | Sutton-Prod | Thread-Prod | Legend-Prod | CBT-Prod | CUBI-Prod | FBOL-Prod | Emprise-Prod | Rockpoint-Prod |
|----------------------------------------------------|-------|-------|------|------|------------|------------|---------|--------|------|-------------|-------------|-------------|----------|-----------|-----------|--------------|----------------|
| **&lt;env&gt;-&lt;bank&gt;-etl-accounts**          | Yes   | Yes   |      |      |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **&lt;env&gt;-&lt;bank&gt;-etl-customers**         | Yes   | Yes   |      |      |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **&lt;env&gt;-&lt;bank&gt;-etl-transactions**      | Yes   | Yes   |      |      |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **&lt;env&gt;-&lt;bank&gt;-etl-loans**             | Yes   | Yes   |      |      |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **&lt;env&gt;-&lt;bank&gt;-etl-settlement**        | Yes   | Yes   |      |      |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **&lt;env&gt;-&lt;bank&gt;-etl-checkalt-fifo**     | Yes   | Yes   |      |      |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **&lt;env&gt;-&lt;bank&gt;-etl-checkalt-lendesca** | Yes   | Yes   |      |      |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **&lt;env&gt;-&lt;bank&gt;-etl-checkalt-setcpros** | Yes   | Yes   |      |      |            |            |         |        |      |             |             |             |          |           |           |              |                |
| **&lt;env&gt;-&lt;bank&gt;-etl-checkalt-ubs**      | Yes   | Yes   |      |      |            |            |         |        |      |             |             |             |          |           |           |              |                |


## API Gateway IDs

| Name                                           | Dev01 | Dev02 | QA1  | QA02 | Thread-UAT | Sutton-UAT | Sandbox    | Hotfix     | Perf       | Sutton-Prod | Thread-Prod | Legend-Prod | CBT-Prod    | CUBI-Prod  | FBOL-Prod  | Emprise-Prod | Rockpoint-Prod |
|------------------------------------------------|-------|-------|------|------|------------|------------|------------|------------|------------|-------------|-------------|-------------|-------------|------------|------------|--------------|----------------|
| **&lt;env&gt;-account-verification-api**       |       |       |      |      |            |            | sdov6wotw5 | fc9fm7kkd8 | 0i0607sjoc | zzep9f77i1  |             | dj3707izt4  | 26eka68d47  | cmzyqrslz6 | 2b4m8pa2w5 | 2g57dqbn11   | 03sfh91w8e     |
| **&lt;env&gt;-accounts-api**                   |       |       |      |      |            |            | 12enbi3qrl | f7ea65usy5 | rwmgde3atl | 723hprcspf  |             | 1jxfeb1sn0  | 9qj8upkqq2  | qucld2crwb | rrqang9yse | 5mkdzx8lp1   | 64fxxff2mh     |
| **&lt;env&gt;-ach-payments-api**               |       |       |      |      |            |            | 3h075ubt70 | cno2pqad9l | v9ytnf8x6b | 2kticbsn3h  |             | ax8riv106m  | 5otfz2xbl1  | ajq17rk8m8 | 8ulhtjo8mc | pu1ofvp3oh   | 0k70nfbz5i     |
| **&lt;env&gt;-ach-preprocessor-api**           |       |       |      |      |            |            | 7i31tnbz7l | tchyim3ze5 | bv1wrf0ck3 | i5q3x8y367  |             | m57d0y2b99  | j3ori31726  | n1v8sg1gfg | fidh0dc2ca | s1y8nw35a7   | e21xeevi8f     |
| **&lt;env&gt;-analytics-api**                  |       |       |      |      |            |            | gbk0qluv3f | dqjzwietlf | ctad8kymej | 3zm0dthzib  |             | ou7m9vw85i  | 7zj60ht0ui  | 7h5il8aqqi | e6nm4tkqmb | 6jqaeb9xrb   | 744xssrpm9     |
| **&lt;env&gt;-billpay-api**                    |       |       |      |      |            |            | nbt52894bh | ybbopelgyc | rjq93qg9c3 | 5d27rrebxl  |             | jfc2li0v29  | rla1oz1951  | 5qjuiqwgs2 | hey1ygs725 | clo68b0al0   | nfbnk13ebd     |
| **&lt;env&gt;-business-api**                   |       |       |      |      |            |            | mwful0mxlf | 5s5p34q4pa | g1t1uz073g | 1uh01yc0k6  |             | 32xmqxw10e  | 6zdicg8g8k  | zo3j1hbd98 | fgvht2jj9b | vx63s58ut6   | 7na1gmcth9     |
| **&lt;env&gt;-cards-api**                      |       |       |      |      |            |            | peeslpegld | g3ugv7q49f | jqmn1rkf73 | 714nae2eyc  |             | 58t7concii  | bs2479xaoi  | f1pv1e1mi9 | o630gpb12m | c7u44klwz1   | bugxxgrdxe     |
| **&lt;env&gt;-casemgmt-api**                   |       |       |      |      |            |            | o25r0e140i | xca8s6eupl | o3fvo06u2h | w6s39z97r9  |             | 35fmoyvjog  | tboevb658l  | u4gyc11ui7 | w82hky5747 | ucgxbnnhx9   | 673eu1slm1     |
| **&lt;env&gt;-coarse-api**                     |       |       |      |      |            |            | 7g436clpoj | yzoamm00bk | y1xi2bu21k | l16vrl6yq5  |             | u9pgklq3vb  | lx62ymf808  | bhfz4rma07 | dr27j26xoh | d7klvqwqo8   | jlhczja9f3     |
| **&lt;env&gt;-cubix-account-api**              |       |       |      |      |            |            | xfdz5qw5g3 | ipx2jmsjo7 | xtyrjjxx09 | rwghd25lm6  |             | 7jd43z0hxj  | khj0k11paj  | z27gniea48 | f299aibj6j | w3f7vb9ke7   | uel5uvvvj5     |
| **&lt;env&gt;-customer-api**                   |       |       |      |      |            |            | lskf92fdg3 | ui5bbxey0m | biu4ayeu41 | r6qat2o735  |             | 0zbl8de5w2  | foioif1xb1  | 0cbq68g6n5 | dihd8hnsq4 | kq7psfp554   | r22bdkj8j4     |
| **&lt;env&gt;-customer-offers-api**            |       |       |      |      |            |            | 7p5b35hvua | hqinrt9309 | 4s9fzutgfi | 0srtu2495e  |             | yd3zp2xs3i  | 5wgmi6fij0  | 4jhi15b4l1 | y7wsbkytxb | 48ez388m1i   | 2djmspqy58     |
| **&lt;env&gt;-debit-card-payment-api**         |       |       |      |      |            |            | 0xvwj3egrj | q152tq3s3m | 88wvotftxf | gsyvo1r3qh  |             | hyzg6gbggi  | w388icw9gl  | c6iaj5hqok | a4q5ocate2 | wvqzi7oizg   | pqunm4jebc     |
| **&lt;env&gt;-documents-api**                  |       |       |      |      |            |            | dpo28odnm7 | 1s2jjsuq6e | rooh930wj6 | 63q3x6e409  |             | 22yxswpey0  | 42epvp0915  | 9jhd5ju0el | gudng2gw0j | 7n1h5ol934   | nsafnu78x0     |
| **&lt;env&gt;-fees-api**                       |       |       |      |      |            |            | vpbiw4tnvj | 5z1uyxko55 | x93c0sc0v3 | 7dnu18cvu5  |             | xh1xvia8n3  | nejhzn4j54  | qiww9wi8qc | r0fcqk7xk3 | e399mvydsk   | 2agrf9jgke     |
| **&lt;env&gt;-financial-institution-api**      |       |       |      |      |            |            | 2idccsqiai | wwz30js3ee | xczkeyv29j | ofdk5nz6ul  |             | pfvnji9puc  | r3s3uxziq9  | yzw1wns9xi | 2k4he1o1z3 | l137lg6f3a   | l68k5oo8y2     |
| **&lt;env&gt;-fraud-api**                      |       |       |      |      |            |            | qomdirq5zh | go541l2cv3 | 25izlhm84i | ihvn9jd27g  |             | ixxweozjs0  | gexqknoow4  | voivyt0ihc | hfe06lhkx3 | k2wl9i1ee9   | 6kj4z3zzva     |
| **&lt;env&gt;-interlace-search-tenant**        |       |       |      |      |            |            |            |            |            | n9h9wfgqak  |             | hgjf0o9k2k  | s5l83dzn2m  | nasm50bmm2 | zagbpgl5vl | dmf608rlod   | gvxjgbxrmd     |
| **&lt;env&gt;-mnymover-api**                   |       |       |      |      |            |            | os4z76jtpb | x4l8g6chlb | h7fykeinjc | pebycyhk0l  |             | 7bqhudf6gb  | zmnd64kf5b  | c607fpnqa3 | 3kgezrjbrl | jdwsv4gsfi   | lgd8q40tah     |
| **&lt;env&gt;-mobile-web**                     |       |       |      |      |            |            | ip5rg7ong1 |            |            |             |             |             |             |            |            |              |                | 
| **&lt;env&gt;-monitoring-api**                 |       |       |      |      |            |            | kns9sidpsi | sskpdq2pie | 7ylgngflq5 | gdrukyxiw8  |             | wc32i8lrpk  | esge14b6j9  | z4p1ywzjei | sjmfna8kqa | 6h2hegwn95   | lyed7ymaa2     |
| **&lt;env&gt;-notifications-api**              |       |       |      |      |            |            | 7e1lo70h55 | 6ytox7nvoi | hpf94cgri7 | 6ong7upypd  |             | 1dcmtrdyni  | 2pz9x5giji  | bnm5v5qwba | j9qolml583 | jv8bf1z3c1   | snf7gfcm7l     |
| **&lt;env&gt;-platform-api**                   |       |       |      |      |            |            | o05p3x43qj | 5s3sv9kfm0 | d2kqu89m0m | m41h309exk  |             | tb2b8y3chi  | 81j13gp9xl  | mofe42vwn9 | 7odo92r380 | prk9fakfyd   | 0l6t8oerej     |
| **&lt;env&gt;-rdc-api**                        |       |       |      |      |            |            | btzlyyiheb | 1bvlciww2g | 75eu13p24d | ajjhuaxxzi  |             | 9r8i725br5  | p5tbkaq5wd  | p7llf37s9a | 7oikm4mnac | mj713heord   | qvtieraqn3     |
| **&lt;env&gt;-reports-api**                    |       |       |      |      |            |            | 1czamyecm8 | k2i23uk4gb | ep6xnxgkl9 | uzcj5z82j5  |             | 0l7gu6r2eh  | c6p2mmnwjg  | h7wbkkxcc2 | ffjikbmzb4 | xnturckvi7   | 064zfnjvqe     |
| **&lt;env&gt;-scheduling-api**                 |       |       |      |      |            |            | m2u5u3catb | xukksdg4dj | 38b8lu2i26 | loidsspohk  |             | arp5lae122  | gnb1z6qb21  | j9zusj2v32 | 1b1xcv6yr0 | fa0y363dee   | rzh0q8b2j1     |
| **&lt;env&gt;-send-otp**                       |       |       |      |      |            |            |            | hwqsf3uhsk |            |             |             |             |             |            |            |              |                |
| **&lt;env&gt;-service-core-gateway**           |       |       |      |      |            |            |            | ryzdj4e2y9 |            |             |             |             |             |            |            |              |                |
| **&lt;env&gt;-service-core-bank**              |       |       |      |      |            |            |            |            |            | 5t7o7v0ivd  |             | 6jvtmf5bkg  |             |            |            |              |                |
| **&lt;env&gt;-sutton-api**                     |       |       |      |      |            |            | a7w44orit0 | 69uei3w9zi | qb83qjokli | h6jne69erl  |             | mpm1nayvpc  | hgzby8fi84  | ozpagt2m41 | bgbmwydj73 | zkc5tloir7   | khhrezl1c2     |
| **&lt;env&gt;-tenant-customer-api**            |       |       |      |      |            |            | 4oyx7zwzm9 | ny5pmdn0cd | 9h0ufbkz2a | aqe7vr6fzi  |             | htjms7ao63  | 3rk3y4t4rk  | 8cnqv8gm8l | 8by4bq8656 | a75dsryhzl   | fwf1x1owe3     |
| **&lt;env&gt;-tenant-users**                   |       |       |      |      |            |            | 5p49lh1nd7 | 41bhriuqq0 | 095rpesxzb | mhx42v10rg  |             | z50ylhrkt8  | 2wwwz5r2gf  | ym1ou68oo3 | cdj6iilxtf | h0dif8f2k5   | iaj3h9y7z5     |
| **&lt;env&gt;-token-notification**             |       |       |      |      |            |            |            | 80mqk4j7v9 |            |             |             |             |             |            |            |              |                |
| **&lt;env&gt;-transaction-events**             |       |       |      |      |            |            | no0prd12yg | s3qs02fd9a | w9scw2os3l | nvyvhxteq8  |             | 5lumdm544i  | 2y6p9d9rfd  | 4gnkl6p9uf | 7mf8wwu2oa | q0kfu0f3yl   | q37emjq9k8     |
| **&lt;env&gt;-transfers-api**                  |       |       |      |      |            |            | xoxk5v18s5 | rq6vjj4dff | f22em8e0td | zl0bp5cw28  |             | pzo4n3dzuh  | 5js34bagqg  | 0ccxn7srql | ttspk3rwmg | 3snitebq5b   | 4xfe7kiena     |
| **&lt;env&gt;-translations**                   |       |       |      |      |            |            | jh8tirk5v6 | ds4l3sck43 | wzcqzd4u59 | nje87xmjq3  |             | ymqq9vvtd4  | bj1akyzwie  | p3f07k5t72 | 7zsb17crvj | k61rab9s40   | 5we0doj40b     |
| **&lt;env&gt;-umx-api**                        |       |       |      |      |            |            | vp65qn6th5 | nthmycf3ec | 1z1pdp0cp2 | faytkuu810  |             | bcz47pqy37  | oig3q9ka97  | u7gssq4o59 | kk35gx135i | bknhxh9tgd   | 2abxeccc9g     |
| **&lt;env&gt;-universal-payments-api**         |       |       |      |      |            |            | uc64t3uqm1 | slk7qlth5d | z0mywipm5f | t2ovm1459e  |             | io5d6n0jq7  | iq29d3w7ol  | jr8qfheqfj | un5qppk9r2 | 04acoginol   | 59wlisdm2l     |
| **&lt;env&gt;-virtual-accounts-api**           |       |       |      |      |            |            | 81q42loo33 | p6w0k2uxe4 | dq2a9wzga6 | ml3pwee1l3  |             | eru963thx3  | 3bqd2nyqph  | ph0yk0atyg | mopessxjr1 | 0j4hk985u5   | nidmu3g0p1     |
| **&lt;env&gt;-virtual-customers-api**          |       |       |      |      |            |            | w3hzyiq5t2 | ua9ugp0ch7 | p4m697zq4i | 9fqny64i2b  |             | uol8uyyr49  | 6y7v4qqjj8  | lvqikq6ck3 | inw3pf1wv0 | rqy8gnff02   | 4bpei6pk4m     |
| **&lt;env&gt;-virtual-ledger-api**             |       |       |      |      |            |            | lfgsc7rle8 | t9t69husw6 | 5l6gpnjxee | sjmyu5iwdf  |             | ui58pz35sl  | sqeuuzttgg  | ea56niliah | 6ekrpa6vla | 25ir633f0i   | f1nf8456ok     |
| **&lt;env&gt;-wire-payments-api**              |       |       |      |      |            |            | db0zvym3lb | jjacyujg4d | ssj8kpufz9 | dp0omxr9r5  |             | lh0nhmpu0l  | bjvaqn1hw8  | egutajv1r0 | 2t4prupwb4 | p7f6h5jza9   | 24u8olx8e2     |