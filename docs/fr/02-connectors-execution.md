# 2. Connecteurs et exécution

Un connecteur encapsule une action externe : swap, dépôt, retrait ou autre interaction DeFi. Le compte transmet les données au connecteur autorisé, qui construit l’appel vers le protocole cible. Cette couche rend la composition plus lisible et limite les chemins d’exécution à des modules connus.

La sécurité dépend toutefois des validations de paramètres, des adresses autorisées et du traitement des retours. Un nouveau connecteur élargit la surface d’attaque et doit être lu avec son interface, ses tests et la gouvernance du système.

L’architecture vise une expérience de compte unique, capable d’enchaîner des opérations diverses dans une transaction.

[Chapitre suivant : permissions et contrôles](03-permissions-controls.md)
