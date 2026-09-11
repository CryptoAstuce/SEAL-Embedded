# Role du capteur chiffre

SEAL-Embedded permet a un appareil contraint de produire des donnees compatibles avec Microsoft SEAL.
La bibliotheque device chiffre mais ne genere pas les cles, ne calcule pas et ne dechiffre pas.
L adapter genere les artefacts puis convertit les ciphertexts vers le format SEAL complet.
Un serveur non fiable peut ensuite effectuer le calcul homomorphe sans voir le message.
Le resultat chiffre revient vers un environnement sur qui conserve la cle secrete.
Cette separation reduit la charge embarquee mais cree plusieurs frontieres de transfert.
Chaque frontiere doit authentifier version, parametres, cle publique et provenance des artefacts.

Suite : [02 — Chiffrement asymetrique](02-chiffrement-asymetrique.md).
