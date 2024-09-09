# Instructions : Utiliser Git pour cloner, modifier, commit, et push

## 1. Cloner le dépôt

La première étape est de cloner ce dépôt Git sur votre machine locale.

Ouvrez un terminal et exécutez la commande suivante :

```bash
git clone https://github.com/votre-utilisateur/votre-depot.git
```

Cela va télécharger tous les fichiers du dépôt sur votre ordinateur.

Ensuite, accédez au dossier cloné :

```bash
cd nom_du_dépôt
```

---

## 2. Créé le fichier `syracuse.c`

Ouvrez un nouveau fichier `syracuse.c` dans un éditeur de texte comme Visual Studio Code, Notepad++, ou autre.

Ajoutez votre nom dans un commentaire en haut du fichier

Sauvegardez vos modifications après les avoir faites.

---

## 3. Ajouter les modifications à Git (staging)

Vous devez indiquer à Git que vous avez crée ce fichier. Vous ferez pareil pour toute modification de fichier ultérieure. Utilisez la commande suivante pour ajouter ces modifications à l'index de Git :

```bash
git add syracuse.c
```

Cette commande indique à Git de préparer le fichier (nouveau ou modifié) pour un commit.

---

## 4. Effectuer un commit

Une fois les modifications ajoutées à l'index, vous pouvez faire un commit pour enregistrer ces modifications dans l'historique Git. Tapez la commande suivante avec un message descriptif de vos changements :

```bash
git commit -m "Ajout de mon nom dans le fichier syracuse.c"
```

Le commit crée un instantané de vos modifications, avec un message expliquant ce que vous avez fait.

---

## 5. Pousser les modifications vers GitHub

Maintenant que vous avez commité vos changements, il est temps de les envoyer (ou "pousser") vers le dépôt distant sur GitHub. Utilisez la commande suivante :

```bash
git push origin main
```

Cela envoie vos modifications sur la branche `main` du dépôt distant (`origin` fait référence au dépôt GitHub d'où vous avez cloné).

---

## 6. Vérifier sur GitHub

Une fois la commande `git push` exécutée, allez sur la page du dépôt GitHub et actualisez la page pour vérifier que vos modifications ont bien été envoyées. Vous devriez voir vos nouveaux commits et les modifications du fichier `README.md`.

---

### Explication des commandes dans le guide :
1. **`git clone`** : Clone le dépôt depuis GitHub vers votre machine.
2. **`git add`** : Prépare (ou "stage") les fichiers modifiés pour être committés.
3. **`git commit -m`** : Enregistre les changements avec un message descriptif.
4. **`git push origin main`** : Envoie les changements vers le dépôt distant GitHub.
