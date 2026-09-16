# 2. Connecteurs

Les connecteurs encapsulent les appels vers les protocoles externes. Ils exposent des fonctions adaptées au compte, puis construisent les paramètres nécessaires au swap, au dépôt, au retrait ou à une autre action.

Cette abstraction permet de composer des stratégies sans dupliquer la logique de compte. Elle impose en contrepartie de vérifier chaque connecteur, ses adresses, ses approvals et la gestion des retours du protocole tiers.

Le dépôt de contrats montre cette frontière entre l’intention de l’utilisateur et l’appel externe.

[Chapitre suivant : permissions](03-permissions.md)
