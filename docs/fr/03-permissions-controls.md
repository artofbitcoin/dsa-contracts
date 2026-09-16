# 3. Permissions et contrôles

Les contrats de compte doivent empêcher un appelant non autorisé de détourner les actifs. Les contrôleurs et modules vérifient le compte exécutant, le connecteur demandé et les données transmises. La configuration des adresses déployées complète ces contrôles avec un registre par réseau.

Les opérations composées peuvent accroître le risque de réentrance, de mauvaise approbation ERC20 ou de retour inattendu d’un protocole tiers. Les wrappers doivent donc conserver une frontière explicite entre intention utilisateur et appel externe.

La gouvernance du système et les clés administratives restent des éléments de confiance à documenter séparément.

[Chapitre suivant : limites et vérification](04-limits-verification.md)
