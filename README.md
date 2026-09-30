# Shopify MCP : assistants IA et API Admin GraphQL

Présentation des interventions Allaux autour de Shopify MCP : outils pour le marchand, données accessibles aux agents et développement d’un serveur privé adapté au besoin.

Développement et intégration par **[Emre Ucak — Allaux](https://allaux.fr/a-propos)**.

## Intégration pour le marchand

Les outils publics destinés aux agents d’achat et ceux destinés au développement répondent à des usages différents de l’exploitation d’une boutique. Pour consulter des ventes ou traiter des fiches produit depuis un assistant, Allaux présente une application personnalisée et des outils MCP au-dessus de l’API Admin GraphQL.

- Autorisations d’application limitées au besoin.
- Outils de lecture du catalogue, des stocks et des commandes.
- Écritures encadrées lorsque le projet les demande.
- Pagination, coût des requêtes et journalisation des appels.

Le périmètre se décide selon les API disponibles et les autorisations de la boutique. Le guide Allaux distingue les interfaces Shopify et leurs usages ; ce dépôt ne distribue pas un serveur officiel Shopify.

## Ressources

- [Shopify MCP : possibilités et serveur sur mesure](https://allaux.fr/shopify/mcp)
- [Application Shopify sur mesure](https://allaux.fr/expertises/application-shopify-sur-mesure)
- [Application Shopify livrée](https://allaux.fr/realisations/application-shopify-complete)
- [Serveur MCP pour boutique](https://allaux.fr/expertises/serveur-mcp-boutique-pilotable)

## Choix de l’interface

| Usage | Périmètre à étudier |
|---|---|
| Développement | Documentation et validation des requêtes |
| Agent d’achat | Catalogue et parcours accessibles à l’acheteur |
| Compte client | Données autorisées du client authentifié |
| Exploitation marchand | Outils privés sur l’API Admin |

Le projet commence par cette distinction. Un outil de consultation marchand doit demander uniquement les champs utiles et paginer ses réponses. Un outil d’écriture demande des permissions et contrôles supplémentaires ; le jeton d’application reste côté serveur.

## Présentation publique

Ce dépôt contient une présentation technique. Les sources, les accès et les données clients restent privés. Pour étudier une adaptation à votre contexte, indiquez vos outils existants, les échanges de données attendus et les contraintes d’exploitation.

## Contact

**Emre Ucak — Allaux**, développeur indépendant depuis 2019.

- [contact@allaux.fr](mailto:contact@allaux.fr)
- [WhatsApp : +33 6 21 86 33 28](https://wa.me/33621863328)
- [Décrire votre projet](https://allaux.fr/contact)
- [allaux.fr](https://allaux.fr/)
