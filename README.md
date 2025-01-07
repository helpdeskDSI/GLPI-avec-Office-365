# GLPI-avec-Office-365
Problème de configuration de la messagerie dans GLPI avec Office 365

Bonjour à tous,

Je travaille actuellement avec GLPI 10.0.17 installé sur Wampserver64 3.3.7, et j'essaie de configurer le service de messagerie (notifications) et le collecteur de courriels. 
Mon objectif est de permettre aux utilisateurs d'envoyer des e-mails via GLPI et de collecter automatiquement les réponses pour créer des tickets dans l'interface.

Ce qui fonctionne :
La messagerie fonctionne avec Gmail.
J'ai également réussi à configurer un serveur de messagerie local avec hMailServer.
Problème rencontré :
Lorsque j'essaie de configurer la messagerie avec Outlook/Office 365, je rencontre des erreurs. Voici les paramètres que j'utilise :

Mode d'envoi des courriels : SMTP+TLS
Hôte SMTP : smtp.office365.com
Port : 587
Identifiant SMTP : Adresse e-mail Office 365 (exemple : helpdeskdsi@outlook.fr)
Mot de passe SMTP : Mot de passe de l'adresse e-mail
Malgré ces paramètres, j'obtiens une erreur disant que l'envoi d'e-mails a échoué.

Tests effectués :
La connectivité vers smtp.office365.com sur le port 587 a été testée avec PowerShell (Test-NetConnection), et tout semble fonctionner correctement.
J'ai aussi vérifié les identifiants de connexion et les droits du compte.
Ce que je recherche :
Je cherche des conseils ou un exemple de configuration correcte (ou même un code ou un script prêt à l'emploi) pour résoudre ce problème. Si quelqu'un a rencontré et résolu un problème similaire, je serais très reconnaissant pour votre aide.

Merci d'avance pour votre support ! 🙏
