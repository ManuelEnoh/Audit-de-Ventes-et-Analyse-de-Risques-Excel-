# Audit-de-Ventes-et-Analyse-de-Risques-Excel-
Analyse des ventes d'une entreprise fictive
Description
Ce projet est une simulation d'audit financier sur un fichier de ventes. J'ai analysé 5 000 transactions (pour un chiffre d'affaires total de 2,73 M€) afin d'identifier des erreurs de données et des risques financiers.

Objectif
L'objectif était de vérifier la fiabilité des données d'une entreprise fictive, de contrôler le respect des règles comptables (comme la séparation des exercices) et d'analyser la dépendance vis-à-vis des gros clients.

Résultats de l'Audit
Détection automatique d'erreurs : Grâce aux fonctions FILTER et COUNTIF, j'ai créé un système qui isole automatiquement 72 factures en double et 20 transactions avec un montant nul.

Test de "Cut-off" (Période) : J'ai identifié 15 ventes enregistrées en 2024 mais qui dataient de 2023. Ce test permet de s'assurer que les revenus sont comptabilisés dans la bonne année.

Analyse de concentration client : À l'aide de Tableaux Croisés Dynamiques, j'ai mis en évidence qu'un seul client représente 13 % du chiffre d'affaires total (356 k€), ce qui représente un risque de dépendance économique.

Outils utilisés
Fonctions Excel : FILTER, UNIQUE, COUNTIF, SUMIFS.

Analyse de données : Tableaux Croisés Dynamiques (TCD) pour analyser les ventes par mois et par canal.

Concepts d'Audit : Intégrité des données, Test de coupure (Cut-off) et Exactitude.
