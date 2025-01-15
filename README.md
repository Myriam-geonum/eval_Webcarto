# eval_Webcarto
Compte-rendu du projet : 
méthodes, démarches et recherches
travail réalisé par Lily Gentaz & Myriam Moustaid
Introduction
	Pour le projet géonumérique nous travaillons toutes les deux sur la définition d’un outil d’aide à la décision sur les espaces à désimperméabiliser pour plusieurs commanditaires dont la métropole du Grand Lyon. La désimperméabilisation des sols en ville est importante car elle permet de réduire les risques d'inondations en favorisant l'infiltration de l'eau de pluie. Elle contribue également à la recharge des nappes phréatiques et améliore la biodiversité urbaine en créant des habitats pour la faune et la flore.

Les acteurs du territoire ont besoin d’intégrer de plus en plus d’actions en faveur de la désimperméabilisation des espaces urbains. L’identification de zones prioritaires est essentielle pour mieux aborder de nouveaux projets, prioriser des actions et sensibiliser le grand public. 

Dans le cadre de notre projet on s’intéresse donc aux différents types de revêtements du sol et l’on a trouvé cela intéressant d’en faire notre entrée pour ce projet de Web cartographie. 

L’utilisation des 3 types de données est donc tout à fait cohérent : 
Les sites de pluviométrie permettent de récupérer de la donnée à une échelle très local
Les pistes cyclables malgré un revêtement imperméable correspond à une politique de mobilité douce 
L’occupation du sol qui est un élément majeur dans l’étude de perméabilité mais également dans l’identification de zones prioritaires

Structure de l’environnement de travail
Le projet est organisé selon l’architecture vue en cours. Le dossier WebCarto_eval contient 4 dossiers, un Readme qui correspond à ce compte-rendu et le HTML qui ouvre la page web créée et contient la structure de la page web : les blocs, titres, images, etc.  
Figure 1 : Structure de l’environnement de travail 


Au sein du css on retrouve un script WebCarto.css avec les différents styles personnalisés que l’on  va retrouver dans notre application.  Au sein du dossier data on retrouve les données au format .js que l’on a récupéré par un autre moyen que fetch().  Au sein de img il n’y a rien finalement car la seule image a été récupéré en copiant l’adresse, il s’agit du logo du master. Au sein du dossier js on retrouve le script Webcarto.js avec les éléments dynamiques de la page web et toute l’interactivité.  
