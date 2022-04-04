# Coast Line Tracking

>Ce service WPS est réalisé dans le cadre d'un projet de mise en pratique avancée à l'Université de Bretagne Occidentale au profil de l'Institut Universitaire Europèen de la Mer. 

Il consiste au dévéloppement d'un webservice pour le suivi de traits de côtes. Il est accessible via le service WPS de [GeoServer](https://geoserver.org/)

## Pré requis

>Geoserver 2.19.2 fonctionnant avec java 11 et l'[extension WPS](https://docs.geoserver.org/latest/en/user/services/wps/install.html)

Les drois d'accès au service WPS et spécifiquement à ce service doivent être configuré dans le GeoServer. [Documentation de configuration](https://docs.geoserver.org/stable/en/user/services/wps/security.html)

## Documentation

> Trois process sont disponibles : 
> - Draw radial
> - Calculate distances between coastlines
> - distancesToCSV
> - coastLinesTracking