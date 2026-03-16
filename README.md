# Canaries
Se denominan *Canaries* a los servicios internos que nos permiten comprobar la interacción con recursos internos mediante SSRF al ejecutar una segunda acción que interactúa con un servicio externo.  

**Petición => Servicio => Recurso Interno => Recurso externo**

Existe una variedad de servicios conocidos que podemos tratar de acceder. A continuación serán enumerados algunos junto a su puerto por defecto.

| Ports | Services                                                                                                                                                             |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1090  | JavaRMI                                                                                                                                                              |
| 1098  | JavaRMI                                                                                                                                                              |
| 1099  | JavaRMI                                                                                                                                                              |
| 1199  | JavaRMI                                                                                                                                                              |
| 2375  | Docker                                                                                                                                                               |
| 2376  | Docker                                                                                                                                                               |
| 4242  | OpenTSDB                                                                                                                                                             |
| 443   | WebLogic,Shellshock,PeopleSoft,ApacheStruts,JBoss,Confluence,Jira,Bamboo,Bitbucket,Crowd,Crucible,Fisheye,Jenkins,HystrixDashboard,W3TotalCache,ApacheTomcat,FastCGI |
| 4443  | JavaRMI                                                                                                                                                              |
| 4444  | JavaRMI                                                                                                                                                              |
| 4445  | JavaRMI                                                                                                                                                              |
| 4446  | JavaRMI                                                                                                                                                              |
| 6379  | Redis                                                                                                                                                                |
| 80    | Confluence,Jira,Bamboo,Bitbucket,Crowd,Crucible,Fisheye,Jenkins,HystrixDashboard,W3TotalCache,ApacheTomcat,FastCGI                                                   |
| 8080  | Confluence,Jira,Bamboo,Bitbucket,Crowd,Crucible,Fisheye,Jenkins,HystrixDashboard,ApacheTomcat                                                                        |
| 8082  | ApacheDruid                                                                                                                                                          |
| 8443  | Confluence,Jira,Bamboo,Bitbucket,Crowd,Crucible,Fisheye,ApacheTomcat                                                                                                 |
| 8500  | HashicorpConsul                                                                                                                                                      |
| 8501  | HashicorpConsul                                                                                                                                                      |
| 8888  | ApacheDruid,Jenkins,Weblogic                                                                                                                                         |
| 8983  | ApacheSolr                                                                                                                                                           |
| 8999  | JavaRMI                                                                                                                                                              |
| 9010  | JavaRMI                                                                                                                                                              |
| 9121  | GitlabPrometheusRedisExporter                                                                                                                                        |
| 9200  | Elasticsearch                                                                                                                                                        |
| 9999  | JavaRMI                                                                                                                                                              |
## Referencias
https://github.com/assetnote/blind-ssrf-chains
