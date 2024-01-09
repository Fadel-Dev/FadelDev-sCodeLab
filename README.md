# FadelDev-sCodeLab
🌟 Qu'offre FadelDev'sCodeLab ?  🤝 Initiation à GitHub : Plongez dans les bases de GitHub. Apprenez à forker, cloner,creer branch,switcher, committer et créer des pull requests - les fondations essentielles pour travailler ensemble.


Voici un exemple de README expliquant la création de branche pour ajouter des informations au fichier `students.json` :

---

# Entraînement GitHub pour les étudiants

Ce dépôt est destiné à vous familiariser avec les étapes de base pour contribuer à un projet sur GitHub. Suivez ces instructions pour ajouter vos informations au fichier `students.json`.

## Étapes à suivre :

### 1. Forker ce dépôt

- Cliquez sur le bouton "Fork" en haut à droite pour copier ce dépôt dans votre espace GitHub personne.

### 2. Cloner votre fork en local

- Sur votre ordinateur, ouvrez un terminal.
- Utilisez la commande `git clone [URL de votre fork]` pour cloner votre fork localement.

### 3. Créer une nouvelle branche

- Sur le terminal, naviguez dans le répertoire cloné avec `cd nom-du-repertoire`.
- Créez une nouvelle branche en utilisant `git checkout -b ajout-nom-specialite` en remplaçant `nom-specialite` par vos propres informations.

### 4. Éditer le fichier `students.json`

- Ouvrez le fichier `djambar.json` dans un éditeur de texte ou un IDE.
- Ajoutez vos informations au format JSON comme ceci :
```json
{
  "djambars": [
    {
      "name": "Votre Prénom Nom",
      "speciality": "Votre Spécialité"
    }
  ]
}
```

### 5. Ajouter, commit et push vos modifications

- Enregistrez vos modifications en utilisant `git add djambars.json` pour ajouter le fichier modifié.
- Effectuez un commit avec `git commit -m "votre Nom"`.
- Poussez vos changements vers votre fork avec `git push origin ajout-nom-specialite`.

### 6. Ouvrir une pull request

- Retournez sur la page de votre fork sur GitHub.
- Vous verrez un bouton "Compare & pull request". Cliquez dessus.
- Expliquez brièvement vos modifications et envoyez la pull request.

---

Ce guide devrait aider les étudiants à comprendre comment créer une branche, apporter des modifications et soumettre une contribution via GitHub. N'oubliez pas d'adapter les instructions en fonction des besoins spécifiques de votre dépôt.😎
