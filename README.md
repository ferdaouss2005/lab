# lab
Dans ce TP, nous allons travailler sur la création d’une classe Voiture et l’utilisation des constructeurs en Java.
J’ai créé la classe Voiture dans le package lab.
J’ai déclaré les quatre attributs privés : marque, modele, vitesse et annee.
si on ne declare pas private l’attribut devient accessible aux classes du même package. Le programme peut donc se compiler si les autres conditions sont respectées, pour voir cela j ai fait un test 
sur la premiere image l attribut n eatit pas private donc il est compile 
<img width="887" height="178" alt="lab1" src="https://github.com/user-attachments/assets/178813b0-f3f0-4b66-b04f-80fa1d41290d" />
par contre quand il est private non
<img width="870" height="326" alt="labb" src="https://github.com/user-attachments/assets/96755bb7-8c98-4436-8775-b7dde86526ec" />

en etape 3 , J’ai ajouté un constructeur sans paramètres pour initialiser les attributs avec des valeurs par défaut, alors l’initialisation permet de donner des valeurs initiales à l’objet dès sa création.

et en etape 4 : J’ai ajouté un constructeur paramétré pour créer des objets avec des valeurs spécifiques
et pour etape 5: La copie superficielle copie les références, tandis que la copie profonde copie aussi les objets eux-mêmes.
et pour etape 6 : On ne peut pas rendre les attributs public, car cela permettrait de les modifier directement sans contrôle. Les getters et setters permettent de protéger les attributs et de contrôler leur accès et leur modification.
etape 7 : On ne peut pas accéder directement à voiture.marque car l’attribut est preivate
apres on veut changer les parametres de setters 
voila les setters de debut
<img width="332" height="214" alt="image" src="https://github.com/user-attachments/assets/34e13927-121e-4a98-94cf-1e62ca16de2f" />



pour la deerniere etape j’ai testé les cas valides et invalides pour vérifier les validations et garantir que l’objet conserve des données correctes.
<img width="524" height="277" alt="image" src="https://github.com/user-attachments/assets/3e0f1aab-05ab-4b82-bcee-fb1cee1984ca" />
et voila l execution finale
