#Cesar et Vigenère

1. Objectif 
Cet atelier a pour but de faire comprendre deux méthodes classiques de chiffrement, afin de découvrir une première approche de la cryptographie et développer une curiosité vers les méthodes modernes. Il permet de découvrir les notions de message clair, chiffré, clef de chiffrement. Ces notions sont essentielles aujourd'hui dans l'échange de messages via Internet. Les méthodes de chiffrements sont beaucoup plus complexes maintenant, mais s'appuient toujours sur le partage d'information secrètes via un canal public.

2. Matériel 
Double disques à imprimer et fixer avec une attache parisienne. Table de Vigenère à imprimer.

3. Principe 
Un message secret doit être envoyé, mais on ne fait pas confiance à la personne qui le transporte. On veut alors le chiffrer, pour qu'il ne soit lisible que par le destinataire. Quand une donnée transite sur Internet, on ne maîtrise pas le chemin qu'elle empreinte, on veut donc que toute personne non destinataire ne puisse voler cette donnée.

Méthode de César :
On choisi un chiffre, et on décale chaque lettre du message par ce chiffre. Par exemple, A devient D si on décale de 3. Le double disque permet de chiffrer et déchiffrer avec ce code, en faisant tourner l'un des disques d'autant de lettre que le nombre choisit, et en faisant la correspondance entre lettre en clair (disque 1) et lettre chiffrée (disque 2).
Pour déchiffrer, il faut connaître le nombre de décalage effectué et faire l'opération inverse pour tout le message. 
Cette méthode tient son nom de Jules César qui avait utilisé un décalage de 3 pour chiffrer des messages militaires.

Aujourd'hui, cette méthode n'est plus utilisée car très rapide à déchiffrer pour un attaquant : il suffit de tester tous les décalages possibles (25 en tout, car 26 = pas de décalage, et 27 équivaut a un décalage de 1 par modulo 26). Cela peut être compliqué pour un message long de craquer le code à la main, mais très simple pour une machine de nos jours.

Méthode de Vigenère :
Cette méthode repose sur le chiffrement de César, mais en utilisant un décalage différent pour chaque lettre. Pour cela on utilise une clef : un mot ou texte dont chaque lettre représente le chiffre de décalage par sa position dans l'alphabet. Si la clef est plus courte que le message clair, on la répète. Exemple : la clef BAC produit un décalage de 1 - 0 - 2.

On peut utiliser le double disque, en le faisant tourner à chaque lettre de la clef, ou alors avoir autant de double disque que de lettre dans la clef. (un pour décalage de 1, puis de 0, puis de 2...). On peuut également utiliser alors la table de Vigenère pour faire la correspondance entre lettre claire et chiffrée. Exemple d'utilisation de la table :

IMAGE ICI

Ce chiffrement est resté incassable pendant 3 siècles, jusqu'en 1863. La méthode pour craquer ce code consiste à déterminer la longueur de la clef, et mener une analyse statistique sur la fréquence des lettres. Une solution fut pendant longtemps de choisir une clef plus grande que le clair, ce qui évite toute répétition de la clef (par exemple avec un livre). Mais cela requière donc que les deux interlocuteurs aientt pu échanger de manière sûre la clef utilisée avant de s'envoyer des messages.

De manière générale, la cryptographie est essentielle pour échanger des messages de manière sécurisée, notamment sur internet. Par exemple le protocole https, que l'on peut voir sur certains sites, indique que les données envoyées à ce site sont chiffrées et donc qu'aucun intermédiaire ne peut les voler. Cela garantie une sécurité sur le transport des données, et non la fiabilité du site en lui-même. mOn veut chiffrer toutes les données importantes pour qu'aucun utilisateur malveillant ne puisse y accèder. Ces méthodes constituent une base des premiers codes utilisés dans l'histoire. 

4. Déroulement 

-Imprimmer et préparer les doubles disques et les tableaux. 
-Proposer des messages chiffrés aux enfants, qu'ils doivent déchiffrer, afin de comprendre les différentes méthodes. Deux groupes doivent communiquer en chiffrant et déchiffrant plusieurs messages. 
