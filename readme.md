# Introduction
Dans ce laboratoire, nous avons mis en pratique nos connaissances sur la création de tables et les divers paramètres que nous pouvons configurer. L'objectif principal de ce lab est de structurer les étapes suivantes de manière méthodique et efficace :

**Création des tables de staging** : Nous avons initié le processus en créant des tables de staging basées sur les tables sources préalablement établies lors du laboratoire précédent. Ce premier pas est crucial pour assurer que les données sources sont correctement représentées et prêtes pour les étapes suivantes de transformation et d'analyse.

**Préparation des données** : Dans les tables staging établies, nous nous sommes concentrés sur la préparation des données. Cela inclut le formatage des données pour assurer leur cohérence et leur compatibilité avec les normes internes et externes. Le nettoyage des données était également une priorité afin de supprimer les incohérences et les valeurs erronées qui pourraient compromettre les analyses futures.

**Optimisation des tables de staging** : Pour garantir des performances optimales et une gestion efficace des données, nous avons appliqué plusieurs stratégies d'optimisation. Cela comprend la définition du clustering et du partitioning, techniques essentielles pour améliorer l'efficacité des requêtes et réduire les coûts de traitement. De plus, nous avons utilisé des tags et des labels pour organiser et catégoriser les tables, facilitant ainsi leur gestion et leur suivi tout au long du cycle de vie du projet.

### Création des tables de staging
Pour chaque table source créée lors du lab précédent, créer une table de staging. Par exemple, pour products, créer `stg_products`.
### Préparation des données
1. **Formatage des types de colonnes**: Dans le lab précédent, toutes les colonnes étaient de type *STRING*. Il est donc nécessaire de les reformater pour attribuer les bons types.
2. **Renommage des colonnes**: Renommer certaines colonnes, par exemple, au lieu de `updated_at` ou `created_at`, il est préférable de mettre `update_date` ou `creation_date`.
3. **Nettoyage des données**: Les données reçues contiennent parfois des valeurs absurdes ou incorrectes (par exemple des valeurs nulles). Éliminer ces valeurs.
### Optimisation des tables de staging
1. **Partitioning et clustering**: Afin de réduire les coûts de stockage et de requêtage, partitionner et clusteriser les tables de staging créées.
2. **Tags et labels** : Pour faciliter l'identification et la manipulation, définir des tags et labels. Par exemple, utiliser le tag `staging`.
