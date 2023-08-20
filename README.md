# PostgreSQL Tips & Tricks

Quelques trucs et astuces sur PostgreSQL ...

[![forthebadge](https://forthebadge.com/images/badges/you-didnt-ask-for-this.svg)](http://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/contains-technical-debt.svg)](http://forthebadge.com)  [![forthebadge](https://forthebadge.com/images/badges/check-it-out.svg)](http://forthebadge.com)  [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

![PostgreSQL](./images/postgresql-logo-256.png)

### Scripts utiles

#### Audit

* [Obtient les statistiques de contenu d'une table](./scripts/audit/table-statistics.sql)
* [Vérifier le fillfactor pour chaque tables et index de la base de données](./scripts/audit/fill-factor-value.sql)
* [Trouver les index en doublon](./scripts/audit/duplicate-indexes.sql)
* [Trouver les index inutiles](./scripts/audit/useless-indexes.sql)
* [Obtenir la structure de la table](./scripts/audit/table-structure.sql)
* [Obtenir les statistiques d'utilisation](./scripts/audit/index-usage-statistics.sql)
* [Les tables sur lesquelles il manque un index](./scripts/audit/tables-need-indexing.sql)
* [Retourner les tables sur lesquelles il manque une clé primaire ou une clé unique](./scripts/audit/tables-without-pk-ui.sql)
* [Retourner les tables sur lesquelles il manque une clé primaire](./scripts/audit/tables-without-pk.sql)
* [Retourner les tables avec des champs de type Geometry non indexés](./scripts/audit/tables-without-indexes-on-geometry.sql)
* [Trouver les tables avec le plus de fragmentation](./scripts/audit/find_bloated_tables.sql)
* [Trouver les index manquants](./scripts/audit/missing-indexes.sql)
* [Rechercher une valeur dans les colonnes d'une table](./scripts/audit/search-in-every-field-in-a-table.sql)

#### Taille

* [Vérifier la taille de la base de données](./scripts/size-related-issues/db-size.sql)
* [Obtenir le nombre de bits gaspillés](./scripts/size-related-issues/wasted-bytes.sql)
* [Quelle table a le plus de dead tuples](./scripts/size-related-issues/dead-tuples.sql)
* [Quelle table ou index consomme le plus d'espace](./scripts/size-related-issues/most-space.sql)

#### Performance

* [Top 10 des requêtes les plus longues](./scripts/performance-related-issues/top-10-longest-queries.sql)
* [Obtenir les requêtes en cours d'exécution et les statuts de verrouillage](./scripts/performance-related-issues/running-queries.sql)
* [Tuer une requête](./scripts/performance-related-issues/kill.sql)

#### Securité

* [Retourne les autorisations par utilisateur](./scripts/security/user-grants.sql)

### Liens utiles

* [PostgreSQL SQL Tricks](https://postgres.cz/wiki/PostgreSQL_SQL_Tricks) - Tips & Tricks
* [PostgreSQL Index Maintenance](https://wiki.postgresql.org/wiki/Index_Maintenance) - Maintenance des index
* [Postgres Cheat Sheet](https://postgrescheatsheet.com/#/tables) - PGSQL cheat sheet
* [PGSQL commands & queries](https://dzone.com/articles/useful-postgresql-commandsqueries-part-1) - Commandes et requêtes utiles

## Réalisé avec

* [Git](https://git-scm.com)

## Contributions

Si vous souhaitez contribuer, lisez le fichier CONTRIBUTING.md pour savoir comment procéder.
