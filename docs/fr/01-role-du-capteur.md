# Rôle du capteur chiffré

SEAL-Embedded permet à un appareil contraint de produire des données compatibles avec Microsoft SEAL.
La bibliothèque device chiffre mais ne génère pas les clés, ne calcule pas et ne déchiffre pas.
L’adapter génère les artefacts puis convertit les ciphertexts vers le format SEAL complet.
Un serveur non fiable peut ensuite effectuer le calcul homomorphe sans voir le message.
Le résultat chiffré revient vers un environnement sûr qui conserve la clé secrète.
Cette séparation réduit la charge embarquée mais crée plusieurs frontières de transfert.
Chaque frontière doit authentifier version, paramètres, clé publique et provenance des artefacts.

Suite : [02 — Chiffrement asymétrique](02-chiffrement-asymetrique.md).
