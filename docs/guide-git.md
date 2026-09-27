# Guide Pratique : Commandes Terminal et Git

Ce guide récapitule les commandes essentielles utilisées pour la gestion de ce projet, tant au niveau du système (Terminal) qu'au niveau du versioning (Git).

---

## 💻 1. Commandes du Terminal (CLI)

1. **`mkdir`** (Make Directory)
   * **Description :** Permet de créer un ou plusieurs nouveaux dossiers.
   * **Option principale :** `-p` (crée les dossiers parents si nécessaire, utile pour imbriquer des répertoires).
   * **Exemple :** `mkdir -p docs src/css`

2. **`touch`**
   * **Description :** Crée un fichier vide ou met à jour la date de modification d'un fichier existant.
   * **Exemple :** `touch README.md .gitignore`

3. **`cd`** (Change Directory)
   * **Description :** Permet de naviguer entre les différents répertoires de l'ordinateur.
   * **Exemple :** `cd dev-de`

4. **`ls`** (List)
   * **Description :** Affiche la liste des fichiers et dossiers présents dans le répertoire courant.
   * **Option principale :** `-la` (affiche tous les fichiers, y compris cachés, sous forme de liste détaillée).
   * **Exemple :** `ls -la`

5. **`pwd`** (Print Working Directory)
   * **Description :** Affiche le chemin absolu du dossier dans lequel tu te trouves actuellement.
   * **Exemple :** `pwd`

---

## 🔀 2. Commandes Git Essentielles

1. **`git clone`**
   * **Description :** Télécharge une copie locale d'un dépôt distant existant.
   * **Exemple :** `git clone <url-du-depot>`

2. **`git status`**
   * **Description :** Affiche l'état actuel de l'espace de travail (fichiers modifiés, ajoutés, non suivis).
   * **Exemple :** `git status`

3. **`git add`**
   * **Description :** Ajoute les fichiers modifiés à l'index (zone de staging) pour préparer le commit.
   * **Option principale :** `.` (ajoute tous les fichiers modifiés du répertoire).
   * **Exemple :** `git add .`

4. **`git commit`**
   * **Description :** Enregistre officiellement les modifications de l'index dans l'historique local avec un message descriptif.
   * **Option principale :** `-m "message"` (permet d'inclure directement le message du commit).
   * **Exemple :** `git commit -m "feat: initialisation du projet"`

5. **`git push`**
   * **Description :** Envoie les commits locaux vers le dépôt distant sur GitHub.
   * **Option principale :** `-u` (associe la branche locale à la branche distante pour les futurs push/pull).
   * **Exemple :** `git push -u origin main`