# NOTE DE CADRAGE

1.1 Objectif du test

Ce test technique évalue votre capacité à :

    Analyser un besoin complexe et identifier les enjeux critiques
    Formuler les questions déterminantes avant le démarrage du projet
    Prioriser les développements selon la valeur business
    Identifier et anticiper les risques majeurs du projet
    Communiquer efficacement vos recommandations à l'écrit

## 1. Executive summary

   ### a- Vision produit comprise en 3-4 lignes
    Plateforme de gaming de l'administration francaise (badging et collaboratif), qui permet aux citoyens de faire leur démarches de manière ludique, simple et efficace. Cette plateforme sera compatbile avec l'environnement existant des services publiques tout en respectant les obligations légales.
   
   ### b- 3 objectifs business principaux identifiés
    Résultat concret dans les 12 mois :
    * avoir déployé une plateforme évolutive pour plusieurs administrations
    * avoir testé et enrichi la gamification de la plateforme
    * avoir implanté la fonctionnalité communautaire de la plateforme
> *justement il manque des objectifs quantifiable business (nombre d'utilisateurs, objectif d'allègment des services, etc. ...).*

   ### c- Proposition de valeur reformulée
>   - Problème : Les démarches administratives sont souvent ressenties comme longues, complexes et energivores.
>   - Public cible : Les utilisateurs qui doivent réaliser des démarches administratives.
>   - Solution : Une plateforme qui intègre des mécanismes de gamification. 
>   - Bénéfice : Rendre les démarches plus motivantes, accessibles et collaboratives. 
>   - Différenciation : Transformer une expérience administrative contraignante en parcours ludique.

## 2. Top 10 questions critiques (1 page)

### a- Les 10 questions les plus importantes à clarifier
> 1. objectifs business quantifiables : quel est le nombre attentdu d'utilisateurs à la création et sur plusieurs périodes, et quels autres indicateurs seront utilisés ?  
> 2. objectifs business quantifiables : combien de fonctionnalités sont attendues dans les 24 mois ?
> 3. fonctionnalités : quelles démarches doivent être déployées en priorité (avec quelle administration) ?
> 4. fonctionnalités : comment doit se présenter la partie "communautaire"?
> 5. technique : les administrations disposent-elles toutes d'API et  de pour communiquer avec leur système ?
> 6. technique : comment seront déterminés les étapes des démarches administratives et sur quelle base de données celles-ci seront synchronisées ?
> 7. modération : quelles sont les limites des aidants utilisateurs ? 
> 8. modération : Comment seront contrôlées les fausses informations et seront modérés les échanges ?
> 9. sécurité : quelles données personnelles sont necessaires à son fonctionnement ? 
> 10. assistant : aura-t-il une source API fiable pour s'appuyer lors de ses conseils ? 

### b - Classement par impact : bloquant / important / nice-to-have
| Bloquant   |  Important |  nice-to-have |
| -----------| -----------| -----------   |
| 3.         | 7.         | 1.            |
| 4.         | 8.         | 2.            |
| 5.         | 10.        |               |
| 6.         |            |               |
| 9.         |            |               |
|            |            |               |



### c - Format tableau : question, impact, justification
| Question   |  Impact      | Justification |
| -----------| -----------  | -----------   |
| 1.         | nice-to-have | pas bloquant pour le développement ni déployement  |
| 2.         | nice-to-have | pas bloquant pour le développement ni déployement  |
| 3.         | bloquant   | obligatoire pour commencer la phase de conception product design |
| 4.         | bloquant   | obligatoire pour commencer la phase de conception product design |
| 5.         | bloquant   | obligatoire pour la phase test en mvp |
| 6.         | bloquant   | obligatoire pour la phase de développement |
| 7.         | Important  | obligatoire pour la phase test en mvp |
| 8.         | Important  | obligatoire pour la phase test en mvp |
| 9.         | bloquant   | obligatoire pour la phase de développement |
| 10.        | Important  | obligatoire pour la phase de développement |
|            |            |               |


## 3. Analyse MVP (1,5 page)

### a. 5 fonctionnalités core pour un MVP
>  1. catalogue de démarches
>  2. parcours guidé par étapes
>  3. suivi de la progression de la démarche
>  4. système de points ou badges
>  5. authentification sécurisée

### b. Matrice effort/valeur simple
| Fonctionnalité Core | Valeur | Effort | Priorité |
| ----------- | ----------- | ----------- | ----------- |
| Catalogue des démarches | 5/5| 2/5 | P1 |
| Parcours guidé par étapes | 5/5 | 3/5 | P1 |
| Suivi de progression | 5/5 | 2/5 | P1 |
| Système de points et badges | 4/5 | 2/5 | P1 |
| Authentification sécurisée | 5/5 | 4/5 | P2 |

### c. Timeline proposée (3 sprints)
#### * sprint 1 - phase de conception
> - User Stories.
> - Parcours utilisateurs.
> - Wireframes et maquettes.
> - Définition des règles métier.
> - Validation des choix techniques.

#### * sprint 2 - phase de développement
> - Catalogue des démarches.
> - Parcours guidé.
> - Suivi de progression.
> - Système de points et badges.
> - Intégration FranceConnect et sécuritaire incluant module paiement.
> - Cablage APIs.

#### * sprint 3 - phase de test
> - Tests fonctionnels.
> - Tests de sécurité.
> - Tests d'accessibilité.
> - Tests utilisateurs.
> - Corrections et validation du MVP.

### d. 3 fonctionnalités à reporter en V2
#### accès par role
##### l'assistant intelligent.
##### la partie collaborative : communauté, entre-aide, classement des utilisateurs.
##### les quêtes cachées et secondaires.

## 4. Risques majeurs et mitigation (0,5 page)

### a. 3 risques principaux identifiés et Actions de mitigation proposées
> 1. Risque technique : difficulté d'intégration avec les systèmes informatiques existants (FranceConnect et APIs). -> audit des systèmes informatiques avec une administration pilote partenaire
> 2. Risques sécuritaire : données extrêmement sensibles et pouvant faire l'objet d'attaque. -> audit de sécurité et administration pilote, partenaire pour contrôle d'application du RGPD et de la législation encour. 
> 3. Risque utilisateur : difficulté à rendre l'application adaptée à tout profil. -> prendre un temps supplémentaire à la phase de conception (respect d'une appli simple intuitive, d'une personnalisation de parcours en fonction du profil, respect RGAA, panel testeur diversifié)

## 5. Approche recommandée (0,5 page)

#### Méthodologie suggérée (Agile/Lean)
    Le projet combinera trois méthodes complémentaires :
* Agile – qui permet de développer progressivement
    - Phases concernées : planification, conception, développement, tests et ajustements.
    - Principe : avancer par cycles courts et adapter la plateforme après chaque retour testeurs.
    - Objectif : faire évoluer la plateforme pour répondre au cahier des charges.

* Lean – qui permet d’optimiser les ressources
    - Phases concernées : conception, développement, mesure des résultats et évolution des fonctionnalités.
    - Principe : éliminer les fonctionnalités et dépenses inutiles (identification des besoins, priorisation, développement, mesurage, amélioration).
    - Objectif : concentrer le budget sur les fonctionnalités essentielles du MVP.

* Scrum – Organiser le travail (ajout)
    - Phases : planification, développement, revue des résultats et rétrospective.
    - Organisation : cycles de deux semaines administré par le Product Owner : choix des fonctionnalités prioritaires selon vote, création et réalisation des tickets décidés, avec suivi par le scrum master. Se termine par revue du sprint et rétrospective avec bilan et amélioration à apporter .
    - Objectif : répartir le travail, suivre l'avancement et améliorer le fonctionnement de l'équipe.


#### Équipe minimale requise
| Rôle | Responsabilité |
| ----------- | ----------- |
| Product Owner | Gestion de projet |
| Scrum Master | Méthode Scrum. |
| Développeur Front-end | Interface utilisateur. |
| Développeur Back-end | Fonctionnalités et API. |
| UX/UI Designer | Ergonomie et accessibilité. |
| Expert sécurité / RGPD | Sécurité et conformité. |
| Testeurs | Vérification du produit. |

#### 3 quick wins identifiés
1. Préparer la phase de conception : définir les étapes, intervenants et responsabilités, et le livrable.
2. Formaliser des parcours utilisateurs à partir des "personas" déjà existantes.
3. Prépaser un premier jet d'une liste de User stories qui répondes aux besoins définis.

#### Prochaines étapes concrètes
1. Retour des réponses aux 10 questions.
1. Valider les fonctionnalités du MVP.
2. Identifier une administration partenaire.
3. Choisir une première démarche administrative.
4. Vérifier la faisabilité des connexions aux API.
5. Concevoir les maquettes.
6. Développer et tester le MVP.

## 6. Bonus (optionnel, 0,5 page max)

    Croquis ou schéma de l'architecture high-level (diagramme)
    Ou parcours utilisateur simplifié du parcours principal
