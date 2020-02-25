#Puzzle de Merkle

1. Objectif
Cet atelier a pour but d'aborder les notions de secret partagé par un canal public, et de complexité pour un attaquant de trouver le secret.

2. Matériel
Puzzles à imprimer, et ciseaux pour les découper. Eventuellement une boîte par puzzle, ou les arranger par tas.

3. Principe
Pour partager une clef secrète, Bob envoit à Alice un grand nombre de puzzles (et les garde en mémoire également). Chaque puzzle contient une clef, et un identifiant et suffisamment facile à résoudre. Alice choisit un puzzle, le résout, et renvoit à Bob l'identifiant du puzzle choisi. Ils savent ainsi tous les deux quel puzzle a été choisi, et peuvent utiliser la clef qu'il contenait pour communiquer.
Si Eve a pu voir tous les puzzles envoyés, ainsi que l'identifiant retourné par Alice, il lui faut résoudre beaucoup de puzzles afin de trouver lequel contenait cet idenfiant et voler la clef secrète. Plus il y a de puzzles, plus ce sera long pour Eve. 
Cette méthode permet d'obtenir une clef secrète partagée entre Alice et Bob, sans que personne d'autre ne puisse l'obtenir rapidement. Il suffit de recommencer l'opération si une clef a été compromise par exemple.

4. Déroulement
-
- Imprimmer et découper les puzzles.
- Deux élèves jouent le rôle d'Alice et Bob. Un espace (une table par exemple) représente le médium de communication que tout le monde peut voir. Le reste de la classe joue le role d'Eve (par petit groupe, individuellement, au choix). 
- Bob pose prend tous les puzzles et les pose sur la table (pour simuler l'étape de création). Toute la classe peut les voir. Alice les prend, et chaque Eve en a un exemplaire (copie de ce qui est vu sur le médium).
- Alice choisi un puzzle et le résoud, sans que personne ne le voie. Elle écrit ensuite l'identifiant du puzzle sur un papier et le pose sur la table. A cette étape, s'assurer que les enfants comprenne que Alice et Bob savent tous les deux la clef à utiliser. 
- Chaque Eve essaye de retrouver la clef en résolvant les puzzle. Par exemple chronométrer les groupes pour déterminer les plus rapides. 
- Montrer que il faut en moyenne plusieurs essais pour trouver la clef. Plus il y aura de puzzle, plus ce sera long, et que Alice et Bob ont sûrement eu le temps de changer de clefs entre temps.

- Variante : par petit groupe les élèves doivet trouver comment utiliser les puzzle, et l'enseignant joue le rôle d'Eve pour vérifier s'ils ont la bonne méthode.
