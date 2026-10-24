# Studio OS

## Le site

**`index.html`** — un seul fichier, 1,4 Mo. Double-clic : il s'ouvre dans ton navigateur. Pas de serveur, pas d'installation, pas de dossier. Le JavaScript, le CSS, les polices et les icônes sont à l'intérieur.

La base Supabase est déjà configurée dans le fichier. Ton compte admin existe déjà : connecte-toi avec ton email et ton mot de passe.

- Nouveau membre : **Gestion d'équipe → Inviter**, puis envoie-lui le **code** (pas le lien, qui pointerait vers ton disque). Il ouvre le même fichier, va sur « Activer mon compte », colle le code, crée son compte avec l'email invité.

## Le reste du dossier

- `studio-os-source.zip` — le code source complet (React/TypeScript, migrations SQL, tests). Nécessaire uniquement si tu veux modifier l'application.
- `.freebuff` — dossier technique de l'outil, à ne pas toucher.

Pour modifier l'app plus tard : décompresse l'archive, `npm install`, `npm run dev`, puis `npm run build` régénère `index.html`. Tout est expliqué dans le README à l'intérieur de l'archive.
