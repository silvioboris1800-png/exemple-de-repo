# ⚽ MON TABLEAU DE BORD FOOTBALL

## 📅 Historique des séances

```dataview
TABLE date, duree, intensite, statut, endurance, vitesse
FROM "Séances"
WHERE type = "seance"
SORT date DESC
```
```dataview
TABLE WITHOUT ID length(rows) AS "Nombre total de séances"
FROM "Séances"
WHERE type = "seance"
```
