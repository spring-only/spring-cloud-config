# Sesion 01 - bicicleta-server

## crear repo en github
bicicleta-server

## constantes
set BASE=C:\home\udemy
cd /d %BASE%\spring-cloud-config\s01-intro

## clonando uno nuevo
git clone https://github.com/spring-only/bicicleta-server.git
git add .
git commit -m "Commit inicial"
git push


# Sesion 01 - bicicleta-config-repo

## crear repo en github
bicicleta-config-repo

## constantes
set BASE=C:\home\udemy
cd /d %BASE%\spring-cloud-config\s01-intro

## clonar repo en github
git clone https://github.com/spring-only/bicicleta-config-repo.git

cd .\bicicleta-config-repo

echo # bicicleta-config-repo >> README.md
git add .
git commit -m "Commit inicial"
git branch -M main
git push -u origin main

## crear archivo properties
bicicleta-server.properties

## agregar archivo
git add .
git commit -m "Nuevo archivo"
git push -u origin main


# Sesion 01 - bicicleta-config-server

## crear repo en github
bicicleta-config-server

## constantes
set BASE=C:\home\udemy
cd /d %BASE%\spring-cloud-config\s01-intro

## clonar repo en github
git clone https://github.com/spring-only/bicicleta-config-server.git

cd .\bicicleta-config-server

echo # bicicleta-config-server >> README.md
git add .
git commit -m "Commit inicial"
git branch -M main
git push -u origin main

## usar spring-initializer
https://start.spring.io/
Config Server