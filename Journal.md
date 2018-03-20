
20/02/18 : La maladie étudiée reste à determiner d'ici la semaine prochaine. Par ailleurs nous avons eu un premier contact avec le principe de classe de python bien pratique pour la modélisation. Pour la semaine prochaine , on aimerait se rensigner davantage sur les données disponibles concernant certaines maladies notamment la tuberculose. Enfin se renseigner sur certaines lois de probabilités en rapport avec ce que l'on veut faire.

27/02/18 : Choix de la grippe (pandemique et/ou saisonnières) documentation sur basemap et pandas pour la cartographie. On a trouvé énormement de documentation sur la grippe (via le site de l'oms cf biblio). Utilisation de bernouilli pour le modele d'infection 

06/03/18: - Visualisation des données: On a décidé la bibliothèque plotly pour la visualisation des données. le premier problème recontré était de pouvoir paramètrer le proxy; ce qui a été résolu sauf qu'on a aussi vu que l'utilisation de la bibliothèque plotly est conditionné par la création d'un compte qui se trouve être payant.
         - on a trouvé qu'il y a la bibliothèque folium qui permet aussi de faire la visualisation.


13/03/18 : améloration et mise en relation du code et de la carte. reproduction d'un model réaliste de contamination et de guérison de la grippe. 

21/03/18 : Au niveau du modele :
Tentatives de rapprochement entre le modele et la réalité (graphique disponible ici https://www.bag.admin.ch/bag/fr/home/themen/mensch-gesundheit/uebertragbare-krankheiten/ausbrueche-epidemien-pandemien/aktuelle-ausbrueche-epidemien/saisonale-grippe---lagebericht-schweiz.html). Cependant une loi binomiale ne semble pas adaptée à une guérison donc je vais chercher une alternative pour la semaine prochaine.

Au niveau de la visualisation :

Amelioration de la carte, désormais lorsque l'on clique sur un pays un popup apparait dans lequel nous allons ajouter un graph circulaire présentant les différentes données du pays.
