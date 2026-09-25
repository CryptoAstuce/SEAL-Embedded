# Limites et vérification

SEAL-Embedded est présenté comme code de recherche non destiné à la production.
Il ne réalise sur le capteur ni génération de clés, ni évaluation homomorphe, ni déchiffrement.
La compatibilité dépend d’artefacts adapter correspondant exactement à la configuration device.
Les modes debug peuvent conserver des capacités et assertions qui changent le profil final.
Ce parcours repose sur device/lib, adapter, user_defines et la politique SECURITY du dépôt.
Aucune installation, compilation, exécution sur cible ou mesure nouvelle n’a été effectuée.
Aucune garantie matérielle ou de résistance aux canaux auxiliaires n’est revendiquée.
Pour vérifier, consulter les tests locaux et sur cible dans un environnement isolé approprié.
