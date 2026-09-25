# Clés sur appareil

Le mode symétrique stocke la clé secrète sur le dispositif et augmente fortement le risque physique.
Une extraction compromet les données passées chiffrées avec cette clé ou sa clé publique associée.
La documentation recommande le mode asymétrique sauf revue par des experts en sécurité et cryptographie.
La rotation des clés doit inclure versionnement des paramètres et rejet des artefacts obsolètes.
Les fichiers de pré-calcul sont sensibles à la substitution même lorsqu’ils ne contiennent pas le secret.
Les canaux entre appareil, adapter, serveur et décrypteur doivent avoir une authentification indépendante.
Le chiffrement homomorphe protège le contenu, pas automatiquement l’origine ni l’intégrité du transport.

Suite : [05 — Limites et vérification](05-limites-et-verification.md).
