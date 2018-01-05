EXPLICATIONS :

Après maintes tentatives pour réaliser la partie A, nous nous sommes retrouvés avec cette erreur (cf. screesnshot "Aerror")..
Le chemin donné pour l'instruction WORKDIR n'est pas le bon. 

Nous sommes donc allé voir dans le chemin en question quel était le bon nom de dossier (cf. screenshot "Apath").
Il s'avère que le chemin attribué dans le Dockerfile au WORKDIR semble généré "aléatoirement" puisqu'à chaque éxécution de la commande
"docker-compose up -d" pour tester si nous avions réussi à corriger ce problème, le chemin apparaissant dans l'erreur n'est jamais le même.

Malgré nos efforts, nous ne sommes pas parvenu à comprendre d'où provenait ce problème par nous-même, nous nous en excusons par avance.