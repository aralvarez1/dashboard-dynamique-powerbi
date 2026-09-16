# Tableau de bord dynamique — Power BI

Tableau de bord interactif Power BI pour le suivi d'avancement de projets.

---

## Contexte / besoin métier

Besoin d'un outil de pilotage visuel permettant aux décideurs de suivre les
indicateurs clés en temps réel, avec des filtres dynamiques par période, zone
géographique, phases et types.

## Données

- **Source** : données d'activité fournies par Sanitoral
- **Qualité** : nettoyage et modélisation préalables (relations, types, doublons)
- **Limites** : pas de connexion directe à une source live (fichier statique)

## Démarche

1. **Modélisation** : création du modèle de données, définition des relations
2. **Mesures DAX** : KPIs calculés (%age face au prévisionnel, qualification des projets en retard)
3. **Visualisations** : graphiques, cartes, tables, segments interactifs
4. **Interactivité** : Q&A, navigation entre pages

## Résultats

- Dashboard interactif avec navigation multi-pages
- Filtres dynamiques (zone, phase, type) pour une analyse exploratoire
- Indicateurs de performance lisibles et actionnables

## Limites & pistes

- Données statiques, pas d'actualisation automatique
- **Pistes** : connecter une source live (SQL Server, API), ajouter des vraies alertes (mail, notifications, ...)
