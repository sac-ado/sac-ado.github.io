#Puzzle de Merkle

1. Objectif
Cet atelier a pour but d'aborder les notions de secret partagé par un canal public, et de complexité pour un attaquant de trouver le secret. Cela est très utilisé aujourd'hui pour partager des informations via Internet de manière sécurisée. Les méthodes de chiffrement abordées dans l'atelier C1 repose sur l'échange aupréalable d'une clef. Cet atelier ainsi que l'atelier C3 proposent d'aborder des méthodes d'échanges sans ce prérequis, ce qui est le cas sur Internet, où l'on n'a pas accès à un canal sécurisé pour partager une clef. Les méthodes proposées ici permettent par exemple d'utiliser un canal public pour échanger une clef de chiffrement.

2. Matériel
Puzzles à imprimer, et ciseaux pour les découper. Eventuellement une boîte par puzzle, ou les arranger par tas.

3. Principe
Pour partager une clef secrète, Bob envoit à Alice un grand nombre de puzzles (et les garde en mémoire également). Chaque puzzle contient une clef, et un identifiant et suffisamment facile à résoudre. Alice choisit un puzzle, le résout, et renvoit à Bob l'identifiant du puzzle choisi. Ils savent ainsi tous les deux quel puzzle a été choisi, et peuvent utiliser la clef qu'il contenait pour communiquer.
Si Eve a pu voir tous les puzzles envoyés, ainsi que l'identifiant retourné par Alice, il lui faut résoudre beaucoup de puzzles afin de trouver lequel contenait cet idenfiant et voler la clef secrète. Plus il y a de puzzles, plus ce sera long pour Eve. 
Cette méthode permet d'obtenir une clef secrète partagée entre Alice et Bob, sans que personne d'autre ne puisse l'obtenir rapidement. Il suffit de recommencer l'opération si une clef a été compromise par exemple.

4. Déroulement
- Imprimmer et découper les puzzles. Expliquer ce que contiennent les puzzles : une clé et un identifiant.
- Deux élèves/intervenants jouent le rôle d'Alice et Bob. Bob envoit les puzzles, et garde un exemplaire des puzzles pas découpés. Alice les récpère, choisi un puzzle, le résoud, et envoi l'identifiant. Les envois se font sur une table ou par un facteur, les enfants doivent comprendre que tout le monde peut voir les messages qui y passent. A ce moment, s'assurer que les enfants comprennent que Alice et Bob peuuvent utiliser la même clé (par exemple pour un code Vigenère).
- Maintenant, les élèves par petit groupe jouent le rôle d'Eve. Avec un exemplaire des puzzles pour chaque groupe, ils doivent retrouver la clé utilisée en résolvant les puzzles.
- Certains groupes y arriveront du premier coup, d'autre devront résoudre tous les puzzles. En moyenne, il faut plusieurs essais pour y arriver, et chaque essai est d'autant plus long que les puzzles seront compliqués et nombreux. 
- Conclure sur la notion de complexité, cette méthode s'appuie sur le temps nécessaire à l'attaquant pour voler la clé afin de partager une information secrète entre plusieurs personnes. Bob peut envoyer de nouveaux puzzles pour changer de clé si un attaquant trouve la clé. Aujourd'hui, un ordinateur peut générer beaucoup de puzzles très rapidement, mais les programmes utilisés pour les découper rendent les programmes très difficiles à résoudre en grande quantité. 
