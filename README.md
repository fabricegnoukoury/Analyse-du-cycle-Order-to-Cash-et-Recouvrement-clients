## Analyse du cycle Order-to-Cash (O2C) – Recouvrement clients B2B

## Situation

- L’entreprise étudiée est un acteur de la distribution B2B à fort volume, reposant sur un modèle d’achat en gros et de revente.
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

- Structuration des flux (facturation vs paiement)
- Réconciliation des données financières
- Reconstruction du lien factures ↔ paiements
- Création d’une temporalité analytique
- Définition d'indicateurs de recouvrement (DSO, taux de recouvrement, encours)
- Analyse des indicateurs et priorisation des actions (relances, mise en demeure, suivi des litiges)

## Résultats clés

- Taux de recouvrement : 99.9%
- DSO moyen (calcul sur CA glissant 30 jours) : ~18 jours
- Encours clients : 153K€
- Cycle de paiement rapide et stable
- Conversion du chiffre d’affaires en cash élevée

## Stack technique

- Power Query – collecte et fiabilisation des données
- Modélisation analytique – structuration des flux financiers (facturation ↔ paiement)
- DAX – conception des indicateurs de suivi (DSO, encours, taux de recouvrement)
- Power BI – dashboard et visualisation

## Contenu

- Données brutes → factures et paiements issus de systèmes ERP
- Modèle_O2C.pbix → dashboard de pilotage du recouvrement
