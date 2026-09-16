# 3. Permissions et composition

La composition de plusieurs actions dans une transaction augmente la puissance du compte, mais aussi la surface de risque. Les contrôleurs doivent vérifier l’appelant, le compte, le connecteur et les données avant d’autoriser l’exécution.

Les permissions ERC20 persistantes, la réentrance et les tokens non standards sont des points de revue importants. Les adresses déployées par réseau, présentées dans docs/addresses.json, doivent être reliées à la version réellement utilisée.

La gouvernance et les clés administratives restent des hypothèses de confiance à expliciter.

[Chapitre suivant : limites](04-limits.md)
