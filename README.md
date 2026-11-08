# Gestion d'une agence immobilière

## Présentation

Projet universitaire réalisé en binôme visant à concevoir une base de données relationnelle pour la gestion d'une agence immobilière avec LibreOffice Base.

Il permet de structurer et de manipuler les informations relatives aux biens immobiliers, aux propriétaires, aux locataires, aux agences, aux contrats de bail et aux opérations d'entretien.

## Fonctionnalités réalisées

Gestion des agences immobilières et de leurs employés.
Gestion des biens immobiliers et de leurs caractéristiques.
Gestion des propriétaires et des locataires.
Gestion des mandats de location et des contrats de bail.
Enregistrement des interventions et des factures d'entretien.
Création de requêtes SQL pour répondre à différentes demandes de recherche et de gestion.
Création de formulaires de saisie et de consultation.

## Modèle de données

La base repose sur 10 tables :

- AGENCE_IMMO
- EMPLOYE
- BIENS
- PROPRIETAIRE
- LOCATAIRE
- MANDAT
- CONTRAT_BAIL
- AGENCE_ENTRETIEN
- INTERVENTION
- FACTURE

Les relations entre les tables ont été définies à l'aide de clés primaires et étrangères. 
Les contraintes d'intégrité on été ajouté pour contrôler la cohérence des données saisies. Par exemple le fait que la date de naissance d'un employé(année) ne peut être supérieur à la date du jour.



## Requêtes SQL

Le projet comprend 10 requêtes correspondant aux questions du cahier des charges, notamment :

Recherche de biens selon plusieurs critères.
Identification de l'agence ayant loué un bien.
Recherche des biens loués à une date donnée.
Identification des biens en mandat de gestion.
Recherche de locataires selon un propriétaire.
Consultation des factures d'entretien.
Calcul de sommes et de montants.
Identification des propriétaires possédant le plus de biens.
Recherche des entreprises intervenues dans certaines villes.

## Technologies et compétences

SGBD :HSQLDB embarqué dans LibreOffice Base.
Langage :SQL.
Outil :LibreOffice Base.

Compétences mobilisées :
Modélisation relationnelle.
Conception de bases de données.
Gestion des clés primaires et étrangères.
Contraintes d'intégrité.
Requêtes SQL, jointures et agrégations.
Création de formulaires.

## Installation et utilisation

Installer LibreOffice.
Télécharger le fichier `Agence_Immobiliere.odb`.
Ouvrir le fichier avec LibreOffice Base.
Consulter les tables, requêtes et formulaires disponibles.

## Limites du projet

Il s'agit d'une réalisation universitaire. Le modèle actuel ne comporte notamment pas de table dédiée à l'historique individuel des paiements de loyers.

Certaines fonctionnalités du cahier des charges restent donc à approfondir.

