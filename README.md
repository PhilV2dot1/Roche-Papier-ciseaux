# Roche-Papier-ciseaux

* Contrat Celo : 0xDeDb830D70cE3f687cad36847Ef5b9b96823A9b0
* Contrat Base : 0xE7e255228EBA6ad9422E7F8E76aB31ffeb8E8b1B

Comment jouer :
1. Créer votre profil :
soliditycreerProfil("VotreNom")
2. Jouer une partie :
solidityjouer(0)  // 0 = Pierre
jouer(1)  // 1 = Papier
jouer(2)  // 2 = Ciseaux
Le contrat génère automatiquement le choix de l'ordinateur et annonce le résultat !
Fonctionnalités :
Statistiques personnelles :

obtenirStats() - Vos victoires, défaites, égalités, taux de victoire, séries
obtenirHistorique(10) - Les 10 dernières parties jouées
obtenirStatsChoix() - Analyse de vos choix préférés et leur efficacité
obtenirRang() - Votre position dans le classement

Système de séries :

Série actuelle : Nombre de victoires consécutives
Meilleure série : Record personnel de victoires d'affilée
Événement spécial quand vous battez votre record !

Classement global :

obtenirClassement() - Top 10 des meilleurs joueurs
Classement basé sur le nombre total de victoires
Affiche aussi les meilleures séries de chacun

Gestion du profil :

reinitialiserStats() - Recommencer à zéro tout en gardant votre nom
obtenirStatsJoueur(adresse) - Voir les stats d'un autre joueur

Événements émis :

PartieJouee - Détails de chaque partie (votre choix, ordinateur, résultat)
SerieBattue - Quand vous établissez un nouveau record de série
VictoireParfaite - Milestone tous les 10 victoires

Exemple de partie :
jouer(0) → "Vous: Pierre | Ordinateur: Ciseaux | VICTOIRE !"
jouer(1) → "Vous: Papier | Ordinateur: Papier | Egalite"
jouer(2) → "Vous: Ciseaux | Ordinateur: Pierre | Defaite"
Statistiques avancées :
Le contrat calcule automatiquement :

Taux de victoire en pourcentage (×100 pour précision)
Choix favoris et leur taux de réussite
Historique complet de toutes vos parties
Comparaison avec les autres joueurs

C'est parfait pour s'amuser, battre des records, et grimper dans le classement sans utiliser de fonds ! 🎮RetryClaude does not have the ability to run the code it generates yet.Claude can make mistakes. Please double-check responses. Sonnet 4.5
