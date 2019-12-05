# Les techniques de SSO
## Les composants
Dans un système d´authentification unique, on trouve en général les éléments suivants : 
- Le client qui est un navigateur web. Il demande l´accès à l´application. 
- Le serveur d´authentification qui est l´élément central du système de SSO. Il assure l´authentification de l´utilisateur, la persistance de sa connexion et la propagation de l´identité de l´utilisateur auprès des applications. 
- Le serveur d´application qui ne délivre les ressources qu´après s´être assuré que le navigateur qui l´accède se soit authentifié auprès du serveur d´authentification. 
- L´agent qui vérifie que l´utilisateur est authentifié. 
Eventuellement le portail web qui centralise l´accès aux applications autorisées (service d´authentification) et donne une vision globale à l´utilisateur de l´ensemble des applications auxquelles il a droit. 

## Fonctionnement d´un SSO
