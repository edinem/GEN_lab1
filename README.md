# Génie Logiciel - GEN

## Laboratoire 1 - Introduction à Git

### Authors : Daniel Oliveira Paiva et Edin Mujkanovic

### Date : 22 février 2019

### Lien du repo : 

#### Listes des commandes ainsi que leur description : 

`git clone git@github.com:edinem/GEN_lab1.git` : Clonage du repo en local en utilisant SSH
`cd GEN_lab1` : On rentre dans le dossier "GEN_lab1" qui contient le repo en local.
`touch master1_file` : Création du fichier master1_file.
`git add master1_file` : On ajoute le fichier master1_file.
`git commit -m "commit master 1"` : On commit le fichier ajouté.
`git push` : On push les modifications sur le repo remote.
`git checkout -b "essai"` : On crée une nouvelle branche "essai"

**changement dans la branch essai**

`touch essai1_file` : On crée un nouveau fichier "essai1_file".
`git add essai1_file` : On ajoute le fichier nouvellement créé.
`git commit -m "commit essai 1"` : On commit le nouveau fichier.
`touch essai2_file` : On créer le fichier "essai2_file".
`git add essai2_file` : On ajoute le fichier nouvellement créé.
`git commit -m "commit essai 2"` : On commit le nouveau fichier.
`touch essai3_file` : On crée le fichier "essai3_file".
`git add essai3_file : On ajoute le fichier nouvellement créé.
`git commit -m "commit essai 3"` : On commit le nouveau fichier.
`git checkout master` : On passe dans la branche master.

**changement dans la branche master**

`touch master2_file : On crée le fichier "master2_file".
`git add master2_file : On ajoute le fichier nouvellement créé.
`git commit -m "commit master 2" `: On commit le nouveau fichier.
`git push` : On push les modifications sur le remote.
`git checkout essai` : On passe dans la branche essai.

**changement dans la branch essai**

`git log` : On regarde les logs de la branche actuelle afin de récuperer l'id du commit.
`git checkout master` : On passe dans la branche master.

**changement dans la branche master**

`git merge 87ad01737d6e49435d38b090d9dae66f6f1628e1` : On merge le commit défini par l'id avec la branche master.
`git push `: On pousse les modifications sur le remote.
`git checkout -b "essai2"` : On crée la nouvelle branche "essai2".

**changement dans la branche essai2**

`git checkout essai` : On retourne dans la branche essai.

**changement dans la branche essai**

`touch essai4_file` : On crée le fichier "essai4_file".
`git add essai4_file` : On ajoute le fichier nouvellement créé.
`git commit -m "commit essai 4"` : On commit le nouveau fichier.
`git checkout essai2` : On passe à la branche essai2.

**changement dans la branche essai2**

`touch esssai2_1_file` : Crée le fichier essai2_1_file
`git add esssai2_1_file` : Ajoute le fichier nouvellement créée
`git commit -m "commit essai2 1"` : Commit les modifs 
`git checkout master` : Switch sur la branche master

**changement dans la branche master**

`git merge essai` : Merge la branche essai avec la branche master
`git push` : Push les modifs sur le serveur
`git checkout essai `: Switch sur la branche essai

**changement dans la branche essai**

`git branch dev 87ad01737d6e49435d38b090d9dae66f6f1628e1` : Crée une branche "dev" sur le commit id mentionné 
`git checkout dev` : Switch sur la branche dev

**changement dans la branche dev**

`touch dev1_file` : Crée un fichier dev1_file
`git add dev1_file` : AJoute le fichier nouvellement créée
`git commit -m "commit dev 1"` : Commit les modifs
`git checkout -b "essai3"` : Crée une branche essai3 et switch dessus

**changement dans la branche essai3**

`touch essai3_1_file` : Crée le fichier essai3_1_file
`git add essai3_1_file` : Ajoute le fichier essai3_1_file dans le versionning
`git commit -m "commit essai3 1"` : Commit les modifs
`git checkout master`: Switch sur la branche master

**changement dans la branche master**

`git merge essai2` : Merge la branche essai2 avec la branche master
`git push` : Push les modifs sur la branche master
`git checkout dev` : Switch sur la branche  dev

**changement dans la branche dev**

`git push -u origin dev` : Push les modifs de la branche dev sur l'upstream origin
`git checkout essai3` : Switch sur la branche essai3

**changement dans la branche essai3**

`git push -u origin essai3` : Push les modifs de la branche essai3 sur l'upstream origin
`git checkout essai` : Switch sur la branche essai

**changement dans la branche essai**

`git push -u origin essai` : Push sur les modifs de la branch essai sur l'upstream origin
`git checkout essai2` : Switch sur la branche essai2

**changement dans la branche essai2**

`git push -u origin essai2` : Push les modifs de la branche essai2 sur l'upstream origin
`git checkout master` : switch sur la branche master

**changement dans la branche master**

`git branch --merged` : Affiche les branches mergées avec master 
`git branch -d essai2` : Supprime la branche essai2 localement  
`git push origin --delete essai2` : Supprime la branche essai2 sur le remote pour éviter de clone dessus
