# Projet Ydays : Infra OpenSource
 L'objectif de ce projet est de monter une infrastructure complète OpenSource fonctionnnel et stable. Une fois déployé, l'architecture restera en constante évolution, l'objectif est l'agrandir au fur et à mesure.

# Jour 1
## Mise au Point
Le projet a été défini, il faut maintenant définir les limites à X temps du projet ainsi que les solutions utilisés.

Deadline : Février

Contenu de l'infra en février :
- Annuaire (LDAP)
- Serveur DHCP
- Serveur DNS
- Poste test
- Firewall (Pfsense)
- Serveur Web (apache2)
- Reverse Proxy (HAProxy)

Solution souhaités :
- OpenLDAP
- HAProxy
- SPIFFE
- Open Policy Agent
- apache2
- (Kubernetes ?)
- Postes (Déployés en docker ou kub ?)


## Déploiement

- Déploiement du serveur LDAP
- Déploiement du serveur DNS
- Déploiement du serveur DHCP
- Déploiement du serveur web
- Déploiement du proxy

# Jour 2

## Suite du déploiement de l'infra avec quelques changements

- Changement de PfSense pour OPNSense (PfSense n'est pas opensource)
- Déploiement du pare-feu et configuration du routage
- Développement de l'annuaire LDAP
