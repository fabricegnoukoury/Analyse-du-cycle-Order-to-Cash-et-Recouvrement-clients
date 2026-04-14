## Analyse du cycle Order-to-Cash (O2C) – Recouvrement clients B2B

## Situation

- L’entreprise étudiée est un acteur de la distribution B2B à fort volume, reposant sur un modèle d’achat en gros et de revente à faible marge avec une rotation rapide des stocks.
- Le segment B2B constitue un levier clé de chiffre d’affaires, avec une forte dépendance à la logistique et à la gestion des encours clients.
- Dans ce contexte, la conversion du chiffre d’affaires en cash est critique pour maintenir la performance financière.

## Complication

Malgré une activité commerciale soutenue, la visibilité sur le recouvrement clients est limitée.

- Les données opérationnelles proviennent de systèmes ERP distincts
- Il n’existe pas de lien direct entre les factures et les paiements
- Une réconciliation des flux est nécessaire
- Le suivi des encours clients et du recouvrement est partiel

## Problématique

- Quelle est la performance réelle du recouvrement clients ?
- Le chiffre d’affaires est-il efficacement converti en cash ?
- Quels leviers permettent d’améliorer le suivi et le pilotage du cycle Order-to-Cash ?

## Approche


- Structuration des flux (facturation vs encaissement)
- Réconciliation des données financières
- Reconstruction du lien factures ↔ paiements
- Création d’une temporalité analytique
- Définition de KPI de recouvrement (DSO, taux de recouvrement, encours)
- Construction de dashboards de pilotage et priorisation des relances

## Stack technique

- Power Query – collecte et fiabilisation des données
- Modélisation analytique – structuration des flux financiers (facturation <-> paiement)
- DAX – conception des indicateurs de suivi (DSO, encours, taux de recouvrement)
- Power BI – dashboard et visualisation

## Contenu

- Données brutes → factures et paiements issus de systèmes ERP
- Modèle_O2C.pbix → dashboard de pilotage du recouvrement
- Documentation_KPI.xlsx → définition des indicateurs (DSO, taux de recouvrement, encours)
