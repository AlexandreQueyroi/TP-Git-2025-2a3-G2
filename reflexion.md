# 1 Structure du projet
Plusieurs branches (Ethan, Kylian-GIRARD, Alexandre-Queyroi) avec commits de création/modif (tp.md, README). Des merges successifs (parfois avec conflits), des reverts, et des fusions via Squash & Merge pour garder un historique.

# 2 git fetch vs git pull
- fetch : récupère les mises à jour distantes sans fusionner.
- pull : fait un fetch + merge automatique.
Exemple : fetch si on veut inspecter les changements avant de les intégrer, pull si on veut directement mettre la branche à jour.

# 3 git reset vs git revert
- reset : réécrit l’historique, peut supprimer des commits.
- revert : crée un nouveau commit qui annule un ancien, sans toucher à l’historique.
Risque : reset --hard peut effacer définitivement des commits utiles. Risqué si le projet est partagé.
