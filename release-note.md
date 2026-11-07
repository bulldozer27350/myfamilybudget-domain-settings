# Release Notes — Silo Paramètres (domain-settings)

Toutes les versions publiées de ce dépôt respectent la spécification [SemVer 2.0.0](https://semver.org/lang/fr/).

---

## [0.0.1] - 2026-11-07

### Type de release
**Version initiale** (mise en place et validation de la structure autonome multi-dépôts)

### Résumé
Première version stable du silo Paramètres (`domain-settings`), regroupant `settings-api` et `settings-core` avec import du BOM centralisé, cycle de build autonome et configuration de déploiement GitHub Packages.

### Changements par composant
- **`settings-api`** : simulation, hypothèses économiques (aucun changement métier).
- **`settings-core`** : persistance JPA de la table app_settings.

### Rétro-compatibilité & Compatibilité binaire
Non applicable : version initiale, aucune version antérieure publiée.
