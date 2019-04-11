<h1>Git & GitHub - Partie 3 Activité</h1>

<h2>Enoncé : Je vais vous demander d'expliquer, avec vos propres mots, les points suivants : </h2>

<p>Qu'est-ce qu'un commit;
À quoi sert la commande git log;
Qu'est-ce qu'une branche.</p>

<p>Imaginez que vous parlez à un ami qui connaît le développement web, mais n'a jamais utilisé Git. Comment lui présenteriez-vous le principe de ces concepts importants de Git ?</p>

<p>Plus votre explication est simple, juste et claire, mieux c'est ! Cela va de soi, mais vous ne pouvez pas reprendre mes explications du cours. Il faut reformuler avec vos propres mots/schémas/etc. Vous avez le choix du format :</p>

///////////////////////////////////////////////////
/////										 //////
///// <h3> Qu'est-ce qu'un commit; </h3>     //////
/////                                        //////
///////////////////////////////////////////////////

  le Commit veut dire : que dés que tu avances sur ton projet et qu'il a atteind un etat et que tu souhaite l'enregister, tu dois commité avec la commande "$ git commit "  Tres important ! Ajoute toujours un commentaire qui permettra de tracer toutes tes modifications.<br>
  exemple:  $ Git commit -m "ici commentaire descriptif de la modif"<br> 
  Cette action sera utile, car le resultat du commit s'affichera quand on appelera un autre commande git " Git log ".

 

///////////////////////////////////////////////////
/////										 //////
/////<h2> À quoi sert la commande git log;</h2>////
/////                                        //////
///////////////////////////////////////////////////

<p>la commande git log et trés utile ,car elle te permettra d'avoir un aperçu de l'historique des tous traitements qui ont été apportés aux fichiers. avec des informations importants qui te permettront de t'y retrouverer facilement et rapidement.<br>
voici ce que l'ont a quand on appelle cette commande :<br>

- Un SHA( numero d'identifiant unique ) avec le mot "commit" suivi d'un numero unique <br>
- D'un ligne reservé aux informations concernant l'auteur: prenom et adresse mail:<br>
- La date de mise à jour du fichier.

commit b89a8c3c5cb2114e3d0d2709e6edbe1a391b72dc<br>
Author: Barkhoum <smguesmia@gmail.com><br>
Date:   Thu Apr 11 17:56:30 2019 +0200 <br>

Ces informations là, ont etaient renseignées l'ors de l'instalation du logiciel sur le pc. Si un jour tu es ammené à travailler sur un projet  et que tu as des questions concernant ce projet, tu pourras grace à ces infos contacter la personne qui a travailler sur le projet.
Pour terminer, comme il se doit avec la principale fonction d'un historique, la date et l'heure du ou des commits.

///////////////////////////////////////////////////
/////										 //////
/////  <h2> Qu'est ce qu'une branche </h2>   //////
/////                                        //////
///////////////////////////////////////////////////

<p>Une branche consiste à faire divergence de ton code source. Celle-ci qui te permettra de travailler en parallèle seul ou en collaboration avec d'autre personnes sur le même repository et d'avoir des versions différentes. <br>

Grace à cette fonctionnalité, tu auras un point de vu pratique sur toutes les modifications. Tu pourras ajouter du code et aussi revenir sur tes versions précédentes si tu le souhaite.<br>

Comme un arbre, tu pourras en créer plusieurs branche, afin que d'autre développeurs puissent travailler sur l'une de ses branches et pour ne pas impacter sur ton projet.<br>
voici un exemple :

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



Aussi avec certaines commandes de Git, tu pourras les associer à ton repository et avoir un historique détaillé et d'accéder  à savoir  "qui a fait quoi" !  </p>
<h4>Alors convaincu ? moi je me lasse plus ! Git & GitHub je l'ai adopté, c'est génial pour la gestion de tes projets. Alors lance-toi !</h4>


<h5>Auteur:Barkhoum </h5>








