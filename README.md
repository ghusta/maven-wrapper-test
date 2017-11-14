# Test : maven-wrapper

## Installation de maven-wrapper

> mvn -N io.takari:maven:wrapper

## Avantage 

- Plus besoin d'installer une version Maven en local. 

## Utilisation

Au lieu de la commande `mvn ...` on utilisera `./mvnw ...` (unix) ou `./mvnw.cmd ...` (windows).

Si la version de Maven requise n'est pas présente, elle sera téléchargée sur https://repo1.maven.org/.

## Doc de référence

- https://github.com/takari/maven-wrapper