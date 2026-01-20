Respect du RGPD et l'origine de nos Base de Données

RGPD – Protection des données et conformité réglementaire

Origine des données

Les données utilisées dans ce projet proviennent de datasets publics mis à disposition à des fins de recherche et d’apprentissage, notamment le dataset Student Insomnia and Educational Outcomes.
Ces jeux de données ne contiennent aucun identifiant direct (nom, prénom, email, numéro étudiant) permettant d’identifier une personne réelle.
Les fichiers .csv correspondent à des versions transformées et nettoyées du dataset initial, utilisées exclusivement dans le cadre de ce projet académique.

Nature des données traitées

Les données traitées sont des données personnelles au sens du RGPD.
Certaines variables, comme celles liées au sommeil, au stress ou au bien-être, peuvent être assimilées à des données sensibles ou semi-sensibles, car elles sont indirectement liées à l’état de santé ou au bien-être psychologique des individus.
Cependnt, aucune donnée médicale officielle ni donnée permettant une identification directe n’est utilisée.
Anonymisation et minimisation des données

Les données utilisées dans le projet sont anonymisées :
absence de toute information nominative,
aucune donnée permettant une ré-identification directe ou indirecte,
analyses réalisées principalement à un niveau agrégé.
Le principe de minimisation des données est respecté : seules les variables strictement nécessaires à l’objectif du projet sont utilisées.
Finalité du traitement des données
Les données sont utilisées exclusivement à des fins de prévention et de recherche académique.

L’objectif du projet est :
d’identifier des signaux de risque,
de mieux comprendre les facteurs influençant la réussite académique,
de proposer un outil d’aide à la décision.
Les données ne sont en aucun cas utilisées à des fins de sanction, de notation automatique ou de prise de décision punitive à l’encontre des étudiants.
Absence de stigmatisation et contrôle humain
La solution proposée ne vise pas à étiqueter ou stigmatiser les étudiants.
Le modèle fournit uniquement :
une probabilité de risque,
ou une catégorisation indicative.
Toute décision finale relève d’un contrôle humain, ce qui garantit que le modèle reste un outil d’aide et non un système de décision automatisée.

Transparence et consentement

Dans un contexte de déploiement réel, les principes de transparence imposeraient :
une information claire des étudiants sur l’utilisation de leurs données,
la communication des objectifs du traitement,
la possibilité pour les personnes concernées d’exercer leurs droits (information, opposition, suppression).
Dans le cadre de ce projet académique, les données étant publiques et anonymisées, aucun consentement individuel n’est requis.
Explicabilité du modèle (RGPD et IA Act)
Afin de respecter les exigences de transparence du RGPD et les principes de l’IA Act, une attention particulière est portée à l’explicabilité du modèle.

L’analyse de la feature importance permet :
une explication globale : identification des variables ayant le plus d’impact sur l’entraînement du modèle,
une explication locale : compréhension des facteurs influençant une prédiction individuelle.
Cette démarche limite l’effet “boîte noire” et renforce la confiance dans les résultats produits par le modèle.
Durée de conservation des données

Conformément au principe de limitation de la conservation :
les données sont conservées uniquement pour la durée du projet académique,
dans un contexte réel, une durée de conservation limitée (par exemple 12 à 24 mois) serait recommandée,
au-delà de cette période, les données devraient être supprimées ou définitivement anonymisées.

Conclusion RGPD

Le projet respecte les principes fondamentaux du RGPD en garantissant :
l’anonymisation des données,
une finalité claire et légitime de prévention,
l’absence de sanction et de stigmatisation,
la transparence et l’explicabilité du modèle,
une durée de conservation limitée des données.


Sources des bases de données


Dataset principal utilisé
Nom du dataset :
Student Insomnia and Educational Outcomes Dataset
Description :
Ce dataset contient des informations anonymisées sur des étudiants, notamment liées au sommeil, au stress, au bien-être, à l’activité physique et à la performance académique.
Il est utilisé à des fins de recherche et d’analyse afin d’étudier les liens entre habitudes de vie et réussite scolaire.
Lien vers la base de données :
https://www.kaggle.com/datasets/akshaydattatraykhare/student-insomnia-and-educational-outcomes
Fichiers dérivés utilisés dans le projet
À partir du dataset initial, plusieurs fichiers ont été créés dans le cadre du projet :
df_tableau.csv
Fichier intermédiaire issu de la transformation et de la structuration des données initiales.
final.csv
Fichier nettoyé et standardisé servant de base de référence pour l’analyse exploratoire, la modélisation et le dashboard.
Ces fichiers ne contiennent aucune donnée personnelle identifiable et sont utilisés exclusivement dans le cadre du projet académique.
Cadre d’utilisation des données

Les données :
sont publiquement accessibles,
sont utilisées à des fins pédagogiques et de preuve de concept,
ne permettent pas l’identification directe ou indirecte d’étudiants réels,
respectent les principes de protection des données (RGPD).
