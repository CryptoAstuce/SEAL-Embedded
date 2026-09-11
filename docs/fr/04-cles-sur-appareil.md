# Cles sur appareil

Le mode symetrique stocke la cle secrete sur le dispositif et augmente fortement le risque physique.
Une extraction compromet les donnees passees chiffrees avec cette cle ou sa cle publique associee.
La documentation recommande le mode asymetrique sauf revue par des experts en securite et cryptographie.
La rotation des cles doit inclure versionnement des parametres et rejet des artefacts obsoletes.
Les fichiers de pre-calcul sont sensibles a la substitution meme lorsqu ils ne contiennent pas le secret.
Les canaux entre appareil, adapter, serveur et decrypteur doivent avoir une authentification independante.
Le chiffrement homomorphe protege le contenu, pas automatiquement l origine ni l integrite du transport.

Suite : [05 — Limites et verification](05-limites-et-verification.md).
