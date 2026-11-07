# Credit-Decision-Support-System

## Présentation du projet

Le **Credit Decision Support System** est une application analytique conçue pour accompagner l’évaluation des demandes de crédit grâce à un modèle de scoring et à un tableau de bord de suivi.

L’outil permet de saisir les informations principales d’un client, d’estimer sa probabilité de défaut et de produire une décision de crédit selon les règles définies dans le système.

## Fonctionnalités principales

### 1. Saisie des demandes de crédit

- Formulaire interactif permettant de renseigner les caractéristiques du client.
- Centralisation des informations nécessaires à l’évaluation de chaque demande.

### 2. Scoring et aide à la décision

- Estimation de la probabilité de défaut à partir des variables renseignées.
- Génération d’une décision de crédit : acceptation ou refus.
- Affichage immédiat du résultat et de la probabilité estimée.
- Présentation visuelle facilitant l’interprétation des résultats.

### 3. Historique et suivi des demandes

- Enregistrement et centralisation des demandes traitées.
- Consultation de l’historique des clients et de leurs caractéristiques.
- Suivi des décisions associées à chaque demande.

### 4. Tableau de bord analytique

Le tableau de bord permet de suivre plusieurs indicateurs clés :

- Nombre total de demandes de crédit.
- Nombre de demandes acceptées et refusées.
- Répartition des décisions de crédit.
- Historique des demandes et des résultats du scoring.

## Objectifs du projet

- Illustrer l’intégration d’un modèle de scoring dans une application de décision.
- Structurer le traitement et le suivi des demandes de crédit.
- Faciliter la consultation des résultats et des indicateurs de performance.
- Renforcer la traçabilité des décisions.
- Démontrer le potentiel de l’analytique pour soutenir les processus de gestion du risque de crédit.

## Cas d’usage

Ce prototype illustre un processus simplifié d’évaluation du risque de crédit, depuis la saisie des informations du client jusqu’à la production d’un score, d’une décision et de son enregistrement dans un tableau de bord.

Il constitue une base pour explorer des fonctionnalités plus avancées, telles que la comparaison de modèles, le suivi de la performance prédictive et l’analyse des facteurs associés au risque de défaut.

## Technologies utilisées

- **Python** — développement de la logique applicative et du traitement des données.
- **Dash** — création de l’interface interactive et des formulaires de saisie.
- **Plotly** — visualisation des résultats du scoring et des indicateurs du tableau de bord.
- **scikit-learn** — développement et utilisation du modèle de scoring pour estimer le risque de défaut.


## Limites et précautions

La qualité des estimations dépend des données, du modèle utilisé et des règles de décision définies dans l’application. Une utilisation en contexte bancaire réel nécessiterait notamment une validation du modèle, une évaluation de ses performances, des contrôles de qualité des données et une analyse des risques de biais.

Cette application est un prototype d’aide à la décision et ne doit pas être considérée, à elle seule, comme un système de décision de crédit validé pour un usage opérationnel.

