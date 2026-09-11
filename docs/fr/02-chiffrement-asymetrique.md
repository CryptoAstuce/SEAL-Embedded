# Chiffrement asymetrique

Le mode asymetrique embarque une cle publique sur l appareil et garde la cle secrete ailleurs.
Il limite les consequences d une lecture de la memoire du capteur par rapport au mode symetrique.
Le contexte de chiffrement doit correspondre exactement aux parametres prepares par l adapter.
Le degre polynomial et les moduli conditionnent securite, taille memoire et profondeur de calcul.
Les valeurs encodees doivent rester dans le domaine attendu par le schema BFV compatible.
Une cle publique remplacee par un attaquant detourne les donnees sans necessairement casser le chiffrement.
Son authenticite doit donc etre protegee lors du provisionnement et des mises a jour.

Suite : [03 — Memoire et arithmetique](03-memoire-et-arithmetique.md).
