# CSRF (Cross-Site Request Forgery)
CSRF : attaque qui force un utilisateur à exécuter des actions indésirables sur une application Web dans laquelle il est actuellement authentifié
Spring Security protège par défaut contre les failles CSRF.
# XSS (Cross Site Scripting)
XSS : injection de code dans une page
Un attaquant envoie un script malveillant à un utilisateur sans méfiance. Le navigateur de l'utilisateur final n'a aucun moyen de savoir que le script ne doit pas être approuvé et exécutera le script.
Spring Security protège par défaut contre les failles XSS.
# CORS (Cross-Origin Resource Sharing)
CORS : mécanisme basé sur un en-tête HTTP qui permet à un serveur d'indiquer toute autre origine (domaine ou port) que la sienne à partir de laquelle un navigateur doit autoriser le chargement de ressources
CORS s'appuie également sur un mécanisme par lequel les navigateurs adressent une requête de « contrôle en amont » au serveur hébergeant la ressource cross-origin pour vérifier que le serveur autorisera la requête réelle. Dans ce contrôle en amont, le navigateur envoie des en-têtes qui indiquent la méthode HTTP et les en-têtes qui seront utilisés dans la demande réelle.
