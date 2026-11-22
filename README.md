# GitHub Repo Viewer

Mini-intégration qui interroge l’API REST publique de GitHub et affiche les informations d’un dépôt : description, étoiles, forks et issues ouvertes.

## Utilisation

1. Ouvre `index.html` dans un navigateur, ou publie le dépôt avec GitHub Pages.
2. Saisis un dépôt au format `propriétaire/nom`.
3. Clique sur **Afficher**.

Aucun jeton d’accès ni secret n’est nécessaire : l’application ne consulte que les données publiques via `GET https://api.github.com/repos/{owner}/{repo}`.

## Développement

L’application est volontairement sans dépendance : HTML, CSS et JavaScript natifs. Elle gère les dépôts introuvables, les erreurs HTTP et la limite de requêtes de l’API.

## GitHub Developer Program

Ce projet est un exemple d’intégration de l’API GitHub. Son existence ne garantit pas l’acceptation au GitHub Developer Program : consulte les critères et l’accord officiels avant toute inscription.

- [GitHub Developer Program](https://docs.github.com/en/developers/overview/github-developer-program)
- [REST API — Get a repository](https://docs.github.com/en/rest/repos/repos#get-a-repository)
