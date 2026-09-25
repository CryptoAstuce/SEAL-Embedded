# Chiffrement asymétrique

Le mode asymétrique embarque une clé publique sur l’appareil et garde la clé secrète ailleurs.
Il limite les conséquences d’une lecture de la mémoire du capteur par rapport au mode symétrique.
Le contexte de chiffrement doit correspondre exactement aux paramètres préparés par l’adapter.
Le degré polynomial et les moduli conditionnent sécurité, taille mémoire et profondeur de calcul.
Les valeurs encodées doivent rester dans le domaine attendu par le schéma BFV compatible.
Une clé publique remplacée par un attaquant détourne les données sans nécessairement casser le chiffrement.
Son authenticité doit donc être protégée lors du provisionnement et des mises à jour.

Suite : [03 — Mémoire et arithmétique](03-memoire-et-arithmetique.md).
