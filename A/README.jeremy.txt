EXPLICATIONS :

Apr�s maintes tentatives pour r�aliser la partie A, nous nous sommes retrouv�s avec cette erreur (cf. screesnshot "Aerror")..
Le chemin donn� pour l'instruction WORKDIR n'est pas le bon. 

Nous sommes donc all� voir dans le chemin en question quel �tait le bon nom de dossier (cf. screenshot "Apath").
Il s'av�re que le chemin attribu� dans le Dockerfile au WORKDIR semble g�n�r� "al�atoirement" puisqu'� chaque �x�cution de la commande
"docker-compose up -d" pour tester si nous avions r�ussi � corriger ce probl�me, le chemin apparaissant dans l'erreur n'est jamais le m�me.

Malgr� nos efforts, nous ne sommes pas parvenu � comprendre d'o� provenait ce probl�me par nous-m�me, nous nous en excusons par avance.