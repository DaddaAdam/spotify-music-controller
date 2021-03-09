# Spotify Music Controller

Une application web qui permet de changer la musique en direct sur un compte Spotify le tout par un système de votes.
Un hôte crée et paramêtre un salon, et reçoit un code qu'il peut partager pour que d'autres personnes puissent l'y rejoindre.
L'hôte a d'office le droit de mettre en pause et de changer de musique comme bon lui semble, mais les invités peuvent voter pour changer de musique.
Une fois le quota de vote atteint, la musique est changée automatiquement.

## Instructions d'installation

### Installer les modules Python nécessaires

```bash
pip install -r requirements.txt
```

### Démarrer le serveur Web

Pour démarrer le serveur web, vous devrez vous munir d'un terminal et lancer une suite de commande.

Dans le dossier principal, lancer le serveur DJango.

```bash
python manage.py runserver
```

### [Installer Node.js](https://nodejs.org/en/)

### Installer les modules Node

Rendez-vous dans le dossier `frontend`.

```bash
cd frontend
```

Puis installer les dependencies.

```bash
npm i
```

### Compiler le Front-End

Pour lancer le script de compilation pour la production.

```bash
npm run build
```

ou pour le developpement:

```bash
npm run dev
```
