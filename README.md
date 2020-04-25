# Welcome to Pom parent `java-parent` :wave:

> NOTE : Le format est basé sur [Make a README].

[![HitCount](http://hits.dwyl.com/bdelion/java-parent.svg)](http://hits.dwyl.com/bdelion/java-parent) [![Version](https://img.shields.io/badge/version-0.0.1-blue.svg?cacheSeconds=2592000)](https://img.shields.io/badge/version-0.0.1-SNAPSHOT-blue.svg?cacheSeconds=2592000) [![Documentation](https://img.shields.io/badge/documentation-yes-brightgreen.svg)](https://github.com/bdelion/java-parent/wiki)

![Maven CI for Java](https://github.com/bdelion/java-parent/workflows/Maven%20CI%20for%20Java/badge.svg?branch=develop) [![Travis CI Build Status](https://travis-ci.com/bdelion/java-parent.svg?branch=develop)](https://travis-ci.com/bdelion/java-parent)

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?branch=develop&project=fr.fifiz.socle.java%3Ajava-parent&metric=alert_status)](https://sonarcloud.io/dashboard?id=fr.fifiz.socle.java%3Ajava-parent&branch=develop) [![Known Vulnerabilities](https://snyk.io/test/github/bdelion/java-parent/badge.svg?targetFile=pom.xml)](https://snyk.io/test/github/bdelion/java-parent?targetFile=pom.xml)

<p>
<a href="https://sourcerer.io/bdelion"><img src="https://sourcerer.io/icons/logo-sharing.svg" height="24px" alt="Sourcerer"></a> <a href="https://www.gitmemory.com/bdelion"><img src="https://www.gitmemory.com/images/logo.png" height="24px" alt="gitMemory"></a>
</p>

> `java-parent` est un pom qui permet de gérer pour mes dév Java Training :
>
> -   les versions des dépendances obligatoires.
> -   les phases de builds communes.

## :house: [Homepage]

## Usage

Ajouter au `pom.xml` de votre composant :

```xml
<parent>
    <groupId>fr.fifiz.socle.java</groupId>
    <artifactId>java-parent</artifactId>
    <version>8.0.0-SNAPSHOT</version>
</parent>
```

## :construction_worker: Fabriqué avec

-   [Visual Studio Code] - Editeur de code source.

## :busts_in_silhouette: Authors

:bust_in_silhouette: **Bertrand DELION**

-   Github: [@bdelion]

Voir aussi la liste des [contributeurs] ayant participés à ce projet.

## :books: Journal des modifications

Pour connaître les dernières évolutions et leurs impacts, consuler la page [CHANGELOG].

## :handshake: Contributions

Les contributions, problèmes et demandes de fonctionnalités sont les bienvenus !
N'hésitez pas à consulter la page des [issues], et à ouvrir une `issue` afin de discuter de ce que vous souhaitez modifier.

## :bookmark: Versioning

Nous utilisons [SemVer] pour le versioning.

Pour les versions disponibles, voir [les tags de ce projet].

## :link: Liens utiles

-   :pencil: Documentation : [Wiki]
-   :building_construction: Build :
    -   [Job Travis CI]
    -   [Github Actions]
-   Repository : [GitHub Package Registry]

## :spider_web: Dependency

-   [Dependencies] - Dépendances de ce projet
-   [Dependents] - Projets dépendants de celui-ci

[make a readme]: https://www.makeareadme.com/#template-1
[homepage]: https://github.com/bdelion/java-parent/tree/master
[visual studio code]: https://code.visualstudio.com/
[@bdelion]: https://github.com/bdelion
[contributeurs]: https://github.com/bdelion/java-parent/graphs/contributors
[changelog]: CHANGELOG.md
[issues]: https://github.com/bdelion/java-parent/issues
[semver]: http://semver.org/
[les tags de ce projet]: https://github.com/bdelion/java-parent/tags
[wiki]: https://github.com/bdelion/java-parent/wiki
[job travis ci]: https://travis-ci.com/bdelion/java-parent
[github actions]: https://github.com/bdelion/java-parent/actions
[github package registry]: https://github.com/bdelion/java-parent/packages
[dependencies]: https://github.com/bdelion/java-parent/network/dependencies
[dependents]: https://github.com/bdelion/java-parent/network/dependents
