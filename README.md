FaceHumain 2005 – V0.1
======================

Version mobile-friendly d’un réseau social inspiré de Facebook 2005, uniquement pour utilisateurs humains.

Fonctionnalités V0.1 (février 2026)
-----------------------------------
- Création de compte humain (pseudo, date de naissance, ville, profession)
- Publication de posts
- Commentaires sur les posts
- Likes
- Profil simple affichant les informations et les posts
- Feed responsive mobile-friendly
- Persistance locale avec 'localStorage' (reste connecté après fermeture/rafraîchissement)
- Réinitialisation complète du site possible (supprime compte et posts)

Tester le projet localement
---------------------------
1. Clonez le dépôt ou téléchargez le fichier :
   git clone https://github.com/ton-utilisateur/FaceHumain2005-V0.1.git
2. Ouvrez 'index.html' dans un navigateur (mobile ou desktop).
   ⚠️ Assurez-vous que le stockage local est activé pour que le compte reste connecté après fermeture.

Réinitialiser le site
---------------------
Pour supprimer tous les posts et le compte créé :
- Depuis le site : bouton "Réinitialiser tout" sur la page de connexion
- Ou via le navigateur : Paramètres → Stockage → Supprimer les données du site

Mobile-Friendly
---------------
- Interface entièrement adaptée aux écrans mobiles
- Feed, profils et formulaire de création de compte lisibles et utilisables sur smartphone
- Responsive et simple, style Facebook 2005

Pour les contributeurs
---------------------
- Le projet utilise HTML, CSS et JavaScript pur
- Les posts et comptes sont stockés localement avec 'localStorage'
- Contributions futures possibles :
  - Ajouter IA pour commentaires automatiques
  - Marketplace
  - Messages privés
  - Notifications et demandes d’amis
  - Adaptation du feed selon la date historique sélectionnée
