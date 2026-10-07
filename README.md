# Toolbox – JEDHA AI Fullstack FT-02

Snippets VS Code, templates et autres partagés entre nous.

## Règles pour s'y retrouvé si on est plusieurs à pousser des snippets
- Un fichier de snippets par personne : `snippets/<prenom>-<theme>.code-snippets`
- Chacun son préfixe (ex. `thierry-ml.` pour Thierry) pour éviter les doublons
- Uniquement notre propre code : pas d'énoncés ni de corrigés JEDHA
- Jamais de clé d'API ni de fichier `.env`
- `git pull` avant chaque `git push`

## Utiliser les snippets 
Copier le fichier voulu dans le dossier `.vscode/` de son propre projet.
Dans une cellule Python, taper le préfixe puis Tab.

## Dossiers
- `snippets/` : fichiers `.code-snippets`
- `templates/` : fichiers `.py` réutilisables
- `notebooks/` : exemples perso
- autres a créer

## Contribuer
1. Cliquer **Fork** (en haut à droite) pour copier le dépôt sur son compte
2. Ajouter son fichier dans `snippets/`, `templates/` ou `notebooks/` ou autre
3. **Contribute → Open pull request** : Thierry valide et fusionne

Contributeurs réguliers : donnez-moi votre pseudo GitHub, je vous ajoute en accès direct.
EOF
git add README.md && git commit -m "README : comment contribuer" && git push