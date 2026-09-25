# Mémoire et arithmétique

Le code embarqué évite les allocations et adapte ses buffers aux limites de la cible.
La transformée NTT accélère les multiplications polynomiales requises par le chiffrement RLWE.
Les représentations RNS découpent les coefficients selon plusieurs moduli machine.
Les tables pré-calculées échangent de la mémoire contre du temps de calcul sur le capteur.
Les tailles compilées doivent rester cohérentes avec les fichiers produits par l’adapter.
Un dépassement de buffer ou une configuration tronquée peut invalider sécurité et interopérabilité.
Les assertions de développement ne remplacent pas les contrôles requis en version finale.

Suite : [04 — Clés sur appareil](04-cles-sur-appareil.md).
