# Memoire et arithmetique

Le code embarque evite les allocations et adapte ses buffers aux limites de la cible.
La transformee NTT accelere les multiplications polynomiales requises par le chiffrement RLWE.
Les representations RNS decoupent les coefficients selon plusieurs moduli machine.
Les tables pre-calculees echangent de la memoire contre du temps de calcul sur le capteur.
Les tailles compilees doivent rester coherentes avec les fichiers produits par l adapter.
Un depassement de buffer ou une configuration tronquee peut invalider securite et interoperabilite.
Les assertions de developpement ne remplacent pas les controles requis en version finale.

Suite : [04 — Cles sur appareil](04-cles-sur-appareil.md).
