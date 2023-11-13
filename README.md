# auto-vote-bot
Vote pour Marie à un concours sur le site marieclaire : _EDIT Novembre 2023 - Page fermée_
https://groupemarieclaire.qualifioapp.com/20/E614CF04-A50C-4CD5-AE3C-C4C2F07D21CD/s200/v1.cfm?id=E614CF04-A50C-4CD5-AE3C-C4C2F07D21CD&pdomain=https://www.marieclaire.fr

# Fonctionnement
Le programme génère des fausses coordonnées grâce au module Faker :
  - Nom, Prénom
  - Adresse, CP, Ville
  - Email
  - Numéro de téléphone

Le module Selenium sert à automatiser les clics et remplissages utilisateur, et ChromeDriverManager à interagir avec le navigateur Google Chrome via Selenium.

# A noter

_qty_votes_ détermine le nombre de votes à effectuer (défaut = 10).

Le programme fonctionnement parfaitement avec les notebooks jupyter de la distribution Anaconda : https://www.anaconda.com/download





