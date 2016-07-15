# x - code - code-management - git

Git est un système de contrôle de version. Sa force réside dans sa simplicité
d'utilisation et la possibilité de traquer n'importe quels changements de
manière non destructrice ce qui en fait un atout idéal pour la gestion de
versions dans un projet.

Git est le concurrent, notamment, d'[SVN](https://subversion.apache.org)
d'Apache.

## Commits

Les **commits** sont au coeur de Git, ce sont eux qui font l'historique du
projet et traquent toutes les modifications. Ils représentent chaque étape du
projet.

De manière générale, un commit doit:

*   Avoir un message (nom) concis et auto-explicatif

*   Contenir uniquement les changements d'une et une seule tâche (résolution
    d'un bug, ajout d'une nouvelle fonctionnalité, correction de typos...).
    Dans le cas d'une nouvelle fonctionnalité de taille conséquente, on doit
    diviser la fonctionnalité en plusieurs commits plus petits.

## Branchs

Les **branchs** sont au coeur du travail collaboratif; il faut voir les
branches comme des routes qu'emprunte le code. On peut alors faire diverger ces
routes, les faire se rejoindre à nouveau... Les branches sont déterminées par
le **workflow** choisi pour le projet. On peut cependant cités quelques règles:

*   La branche *master* est TOUJOURS déployable.

*   La branch *develop* est la branche utilisée pour le serveur de *staging*
    (serveur de test). Quand les tests sont bons, que la branche develop est
    déployable, alors on peut la merger dans la branch *master* et créer une
    nouvelle *release*.

*   Les branches de **fix** (intitulées idéalement `fix/#18` où
    `fix/menu-link-bug`) sont des embranchements servant à résoudre un voir des
    bugs. Une fois le bug résolu et validé, on merge la branche dans *develop*.

*   Les branches de **feature** (intitulées idéalement `feature/nouveau-menu`)
    sont des embranchements servant à développer une nouvelle fonctionnalité.
    Une fois la fonctionnalité développée et validée, on merge la branche dans
    *develop*.

## Ressources

*   [Git](https://git-scm.com)
*   [Git Book - FR](https://git-scm.com/book/fr/v2)
*   [Aide-mémoire Git par GitHub - FR](https://training.github.com/kit/downloads/fr/github-git-cheat-sheet.pdf)
