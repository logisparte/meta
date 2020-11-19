# Guide de contribution

> Read in [English](/docs/en/contribution-guidelines.md)

## Discussions générales

Les contributeurs se doivent d'être respectueux envers leurs pairs, sous peine d'être bannis.

Les issues, les pull requests, le code source et la documentation doivent être rédigés en
anglais. Une version française de la documentation peut être fournie. Dans le cas contraire,
elle sera rédigée par un _hómoioi_

## Issues

3 types d'issues sont acceptées :

- **BUG** (ça devrait fonctionner, mais ça ne fonctionne pas)
- **REQUEST** (ça n'est pas présentement supporté, mais ça devrait l'être)
- **DOCUMENTATION** (la documentation devrait l'expliquer clairement, mais elle ne le fait pas)

### Titres d'issues

Les titres des issues devraient avoir le format suivant :

`[TYPE_ISSUE] titre`

> Le titre devrait être concis mais clair

### Descriptions d'issue

Si le dépôt ne spécifie pas de gabarit d'issue, utiliser les règles générales suivantes :

#### BUG

- Résumé du problème
- Message d'erreur et trace d'exécution
- Étapes pour reproduire

#### REQUEST

- Résumé de la requête
- Pours
- Contres

#### DOCUMENTATION

- Expliquer ce qui n'est pas clair
- Citer le paragraphe problématique, s'il y lieu
- Proposer une amélioration

## Pull requests

4 types de pull requests sont acceptées :

- **FIX** (correction pour une issue BUG)
- **POC** (preuve de concept pour une issue REQUEST)
- **FEAT** (implementation pour une issue REQUEST)
- **DOCUMENTATION** (modifications pour une issue DOCUMENTATION)

> Toutes les pull requests devraient avoir une issue reliée

### Titres de pull requests

Les titres de pull request devraient avoir le format suivant :

`[TYPE_PULL_REQUEST] titre`

> Le titre devrait être concis mais clair

### Descriptions de pull requests

- Lien vers l'issue reliée
- Résumé du changement
