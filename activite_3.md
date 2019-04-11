Git & GitHub - Partie 3 Activité
=================================

##Enoncé : Je vais vous demander d'expliquer, avec vos propres mots, les points suivants : 

Qu'est-ce qu'un commit;
À quoi sert la commande git log;
Qu'est-ce qu'une branche.

Imaginez que vous parlez à un ami qui connaît le développement web, mais n'a jamais utilisé Git. Comment lui présenteriez-vous le principe de ces concepts importants de Git ?

Plus votre explication est simple, juste et claire, mieux c'est ! Cela va de soi, mais vous ne pouvez pas reprendre mes explications du cours. Il faut reformuler avec vos propres mots/schémas/etc. Vous avez le choix du format :
-------------------------------------------------------------------------------------------------
## Qu'est-ce qu'un commit; 



Le  Commit est une commande de git qui te permet  de versionner ton fichier dès que tu avances sur ton projet et qu'il a atteint un état et que tu souhaites l'enregistrer, alors on appelle la commande  "$ git commit " . Très important !  Ajoute toujours un commentaire qui permettra de tracer toutes tes modifications.   exemple:  $ Git commit -am "ici commentaire descriptif de la modif"   Cette action est indispensable, car le texte  s'affichera quand on appellera une autre commande git " Git log ". 
voici un exemple de 3 commits:

smgue@LAPTOP-MC81QAEV MINGW64 ~/activite_3 (master)
$ git log
commit db976288f7d123908009d73d0593fbb475861519 (HEAD -> master, version_1)
Author: Barkhoum <smguesmia@gmail.com>
Date:   Thu Apr 11 18:50:46 2019 +0200

     ajout de la troisieme partie du site

commit b89a8c3c5cb2114e3d0d2709e6edbe1a391b72dc
Author: Barkhoum <smguesmia@gmail.com>
Date:   Thu Apr 11 17:56:30 2019 +0200

     ajout de texte sur la partie qu'est ce qu'un commit

commit 3a58329c7f8c3321c49690bb383d9404baa367f8
Author: Barkhoum <smguesmia@gmail.com>
Date:   Thu Apr 11 15:23:37 2019 +0200

    ajout de texte qu'est ce qu'une branche

------------------------------------------------------------------------------------------------- 

## À quoi sert la commande git log;


Justement je t’en parlais plus haut ! c’est la continuité de la commande git commit . Elle te permettra d'avoir un aperçu de l'historique de tous les  traitements qui ont été apportés aux fichiers avec des informations importantes qui te permettront de t'y retrouver  facilement et rapidement.
Voici ce que l'on a quand on appelle cette commande :
Un SHA( numéro d'identifiant unique ) avec le mot "commit" suivi d'un numéro unique.  Une ligne réservée aux informations concernant l'auteur: prénom et adresse mail.  La date de mise à jour du fichier.



commit b89a8c3c5cb2114e3d0d2709e6edbe1a391b72dc
Author: Barkhoum <smguesmia@gmail.com>
Date:   Thu Apr 11 17:56:30 2019 +0200 

Ces informations-là, ont étaient renseignées lors de l'installation du logiciel sur le pc. Si un jour tu es  amené à travailler sur un projet  et que tu as des questions concernant celui-ci, tu pourras grâce à ces informations contacter la personne qui a travaillé sur le projet. Pour terminer, comme il se doit avec la principale fonction d'un historique, la date et l'heure du ou des commits.
-------------------------------------------------------------------------------------------------

## Qu'est ce qu'une branche 

Une branche consiste à faire divergence de ton code source. Celle-ci qui te permettra de travailler en parallèle seul ou en collaboration avec d'autres personnes sur le même repository et d'avoir des versions différentes. Grace à cette fonctionnalité, tu auras un point de vue pratique sur toutes les modifications. Tu pourras ajouter du code et aussi revenir sur tes versions précédentes si tu le souhaite. 
Comme un arbre, tu pourras en créer plusieurs branches afin que d'autres  développeurs puissent travailler en parallèle sur l'une d'entre elles pour ne pas impacter  ton projet.  Aussi avec certaines commandes de Git, tu pourras les associer à ton repository et avoir un historique détaillé et d'accéder  à savoir  "qui a fait quoi" !
Comme sur la photo à droite :
1)	La commande Git branch te permet de savoir  combien de branches tu as, et sur quelle branche tu es positionné avec comme indication l’étoile. Ici en nous sommes sur la branche master.
2)	La commande Git checkout te permet de basculer d’une branche à l’autre. Ici j’ai demandé de basculer sur la branche  version_1.
3)	La commande Git status te permet de vérifier le statut de la branche et te dit qu’il n’a pas de commit , mais que tout va bien !
4)	J’ai appelé la commande git branch pour vérifier que je suis bien sur la branche version_1.
5)	J’ai finalement  basculé sur la branche master avec la commande checkout.
6)	Pour finir j’ai vérifié que je suis bien sur la branche master grâce à l’étoile. 
 
smgue@LAPTOP-MC81QAEV MINGW64 ~/activite_3 (master)
$ git branch
* master
  version_1

smgue@LAPTOP-MC81QAEV MINGW64 ~/activite_3 (master)
$ git checkout version_1
Switched to branch 'version_1'

smgue@LAPTOP-MC81QAEV MINGW64 ~/activite_3 (version_1)
$ git status
On branch version_1
nothing to commit, working tree clean

smgue@LAPTOP-MC81QAEV MINGW64 ~/activite_3 (version_1)
$ git branch
  master
* version_1

smgue@LAPTOP-MC81QAEV MINGW64 ~/activite_3 (version_1)
$ git checkout master
Switched to branch 'master'

smgue@LAPTOP-MC81QAEV MINGW64 ~/activite_3 (master)
$ git branch
* master
  version_1



Comme un arbre, tu pourras en créer plusieurs branches afin que d'autre développeurs puissent travailler en parallele sur l'une d'entre elle pour ne pas impacter sur ton projet.

Aussi avec certaines commandes de Git, tu pourras les associer à ton repository et avoir un historique détaillé et d'accéder  à savoir  "qui a fait quoi" !  

###Alors convaincu ? Moi je m’en lasse plus ! Git & GitHub je l'ai adopté, c'est génial pour la gestion de tes projets. Alors lance-toi !


Auteur:Barkhoum  merci d'avoir pris le temps de lire. 
------------------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------------------
###Voir le fichier en format pdf [Barkhoum](http://barkhoum.com/TpGit/Git%20et%20github%20activite3.pdf) 








