# Bulletins & relevés — version web

App 100 % navigateur (aucun serveur) : rapproche bulletins de paie et relevés
par nom, fusionne en un PDF par chauffeur, prépare l'envoi. Fonctionne sur Mac
et Windows, dans n'importe quel navigateur.

Les documents ne quittent jamais le navigateur. L'envoi automatique avec pièce
jointe n'est pas possible depuis une page web (sécurité) : l'app prépare l'email
(bouton « Écrire l'email ») et vous joignez le PDF téléchargé.

## Déploiement (GitHub Pages)

1. Publier ce dossier comme dépôt **public** sur GitHub.
2. Repo → Settings → Pages → Source : branche `main`, dossier `/ (root)` → Save.
3. L'app est en ligne à `https://<compte>.github.io/<repo>/`.
