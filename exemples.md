# Exemples de requêtes sur Google

[Retour au README](./README.md)

## Opérateurs logiques

|  Type | Description           | Exemple                                                                                                                                                    |
| ----: | --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `AND` | L'un ET l'autre       | <a href="https://www.google.com/search?q=d%C3%A9veloppement+AND+web" target="_blank">`développement AND web`</a>                                           |
|  `OR` | L'un OU l'autre       | <a href="https://www.google.com/search?q=HTML+OR+CSS" target="_blank">`HTML OR CSS`</a>                                                                    |
|   `-` | Exclusion d'un terme  | <a href="https://www.google.com/search?q=d%C3%A9veloppement+-web" target="_blank">`développement -web`</a>                                                 |
|   `~` | Termes similaires     | <a href="https://www.google.com/search?q=~programmation" target="_blank">`~programmation`</a>                                                              |
|   `*` | Remplacement d'un mot | <a href="https://www.google.com/search?q=d%C3%A9veloppement+*+web" target="_blank">`développement * web`</a>                                               |
|  `""` | Phrase exacte         | <a href="https://www.google.com/search?q=d%C3%A9veloppement+web+avanc%C3%A9" target="_blank">`développement web avancé`</a>                                |
|  `()` | Regroupement          | <a href="https://www.google.com/search?q=(d%C3%A9veloppement+OR+programmation)+AND+mobile" target="_blank">`développement OR programmation AND mobile`</a> |

## Opérateurs de filtrage

|        Type | Description                                    | Exemple                                                                                                                                     |
| ----------: | ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
|     `site:` | Limite la recherche à un site spécifique       | <a href="https://www.google.com/search?q=JavaScript+site:developer.mozilla.org" target="_blank">`JavaScript site:developer.mozilla.org`</a> |
|    `inurl:` | Recherche des termes dans l'URL des pages      | <a href="https://www.google.com/search?q=inurl:API" target="_blank">`inurl:API`</a>                                                         |
|  `intitle:` | Recherche des termes dans les titres de pages  | <a href="https://www.google.com/search?q=intitle:%22guide+CSS%22" target="_blank">`intitle:"guide CSS"`</a>                                 |
|   `insite:` | Recherche des termes dans le contenu des pages | <a href="https://www.google.com/search?q=insite:CSS" target="_blank">`insite:CSS`</a>                                                       |
| `filetype:` | Recherche des fichiers d'un type particulier   | <a href="https://www.google.com/search?q=guide+filetype:pdf" target="_blank">`guide filetype:pdf`</a>                                       |

## Opérateurs arithmétiques

|               Type | Description    | Exemple              |
| -----------------: | -------------- | -------------------- |
|                `+` | Addition       | `1+2`                |
|                `-` | Soustraction   | `1-2`                |
|                `*` | Multiplication | `1*2`                |
|                `/` | Division       | `1/2`                |
|                `^` | Exposant       | `2^3`                |
| `sqrt()` ou `^1/2` | Racine carree  | `sqrt(4)` ou `4^1/2` |
|             `^1/3` | Racine cubique | `8^1/3`              |
|                `%` | Modulo         | `5%2`                |
|                `!` | Factorielle    | `5!`                 |
