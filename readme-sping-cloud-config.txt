Development > Software Development
Spring Cloud Config

Section
    Lecture

S01 | Introduccion
    Entendamos el contexto
    Soluciones previas al Spring Cloud Config
    Conceptos de Spring Cloud Config
S02 | Configuración básica
    Git local, bootstrap
    Ambientes y ramas
S03 | Orden de Prioridad
    Orden de prioridad de variables en Java
    Orden de prioridad de variables en Spring
    Orden de prioridad de variables en Spring Boot
S04 | Refresco de propiedades
    Refresh (Config Server y de la aplicacion cliente)
    Inyectar variables diversas formas
S05 | Propiedades encriptadas
    Secretos en los valores
    Desencriptado en server
    Desencriptado en client
    Errores y solución de problemas
S06 | Backend File server
    File server (Windows, Linux)
S07 | Backend Github
    Github publico
    Github con password
    Github con SSH
S08 | Backend Bitbucket
    Bitbucket publico
    Bitbucket con password
    Bitbucket con SSH
S09 | Backend Azure
    Azure Repos
    Azure Keyvault
    Azure Table Storage
S10 | Backend AWS
    AWS S3 Backend
    AWS Parameter Store
    AWS Secrets Manager
S11 | Backend Database
    JDBC Backend
        SQL server, encrypted
        MySQL
    Redis Backend
S12 | Backend Hashicorp Vault    
S13 | Configuraciones avanzadas
    SSL Verification
    Estoy detrás de un Forward Proxy
    Leer de múltiples repositorios
S14 | Alternativas
    K8S y ConfigMap/Secrets

SIMILARES
https://www.udemy.com/course/distributed-configuration-with-spring-cloud-config/

S1
http://localhost:8888/my-client/dev/
http://localhost:8888/my-client/dev/develop
http://localhost:8888/my-client/dev/master
curl -v http://localhost:8888/encrypt -d "Hola que tal"
curl -v http://localhost:8888/decrypt -d 50c81f86b0c52f5530d78a336ec3cb442a36acdbbdc3737a04ff9321cb88634f

http://cdn.foofun.cn/spring-cloud/spring-cloud/Dalston.SR4/source/single/spring-cloud.html#_features

Prioridad
https://docs.spring.io/spring-boot/docs/current/reference/html/features.html#features.external-config
https://betterprogramming.pub/5-observations-on-spring-boots-loading-precedence-for-properties-files-with-spring-cloud-config-331d1af9052e

en los yaml con ''
en los properties sin ''
https://piotrminkowski.com/2017/07/17/microservices-configuration-with-spring-cloud-config/
https://piotrminkowski.com/2019/12/03/secure-spring-cloud-config/
https://tanzu.vmware.com/developer/guides/spring/spring-cloud-config-security/
https://asbnotebook.com/spring-cloud-config-encrypt-decrypt-configuration-properties/
https://asbnotebook.com/spring-cloud-config-server-with-file-system/

https://spicethemes.com/theme/

https://medium.com/javarevisited/spring-cloud-config-server-4175fd819e7e


 

S2
https://soshace.com/centralize-the-configuration-of-services-with-spring-cloud-config/
https://soshace.com/spring-cloud-config-refresh-strategies/
https://www.baeldung.com/spring-reloading-properties
https://picodotdev.github.io/blog-bitix/2018/09/recargar-sin-reiniciar-la-configuracion-de-una-aplicacion-spring-boot-con-spring-cloud-config/

Refresh
https://gist.github.com/dsyer/a43fe5f74427b371519af68c5c4904c7

S05
https://stackoverflow.com/questions/35165862/is-there-a-way-a-spring-cloud-config-client-can-decrypt-cipher-text-fetched-from

S6
https://www.baeldung.com/spring-cloud-config-without-git

S07
https://fullstackdeveloper.guru/2021/11/08/how-to-load-aws-secrets-automatically-on-application-startup-in-spring-boot/

S9
https://refactorizando.com/spring-cloud-config-server-vault-git/

S14
https://joshgunh.medium.com/spring-cloud-config-vs-kubernetes-configmap-detailed-comparison-bce64b594af8

POWERPOINT
Background
56,100,179  0,0,0
Candara

Font para cajas
Aptos
Daytona
Ebrima
Miriam
Nirmala UI
Source Sans Pro <---

