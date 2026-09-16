# 1. Modèle des Smart Accounts

Un DeFi Smart Account est un compte programmable qui détient des actifs et délègue des actions à des connecteurs. L’utilisateur peut ainsi composer plusieurs opérations DeFi depuis une même adresse logique.

Le dépôt sépare les contrats de compte, les contrôleurs et les bibliothèques d’exécution. Cette structure rend les responsabilités lisibles : le compte conserve l’état, le contrôleur orchestre et le connecteur traduit l’intention vers le protocole cible.

[Chapitre suivant : connecteurs](02-connectors.md)
