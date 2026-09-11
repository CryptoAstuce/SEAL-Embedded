# Limites et verification

SEAL-Embedded est presente comme code de recherche non destine a la production.
Il ne realise sur le capteur ni generation de cles, ni evaluation homomorphe, ni dechiffrement.
La compatibilite depend d artefacts adapter correspondant exactement a la configuration device.
Les modes debug peuvent conserver des capacites et assertions qui changent le profil final.
Ce parcours repose sur device/lib, adapter, user_defines et la politique SECURITY du depot.
Aucune installation, compilation, execution sur cible ou mesure nouvelle n a ete effectuee.
Aucune garantie materielle ou de resistance aux canaux auxiliaires n est revendiquee.
Pour verifier, consulter les tests locaux et sur cible dans un environnement isole approprie.
