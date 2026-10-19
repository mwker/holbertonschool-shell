
# Shell, permissions

Ce projet contient des scripts Bash pour apprendre à gérer les utilisateurs, les groupes et les permissions des fichiers sous Linux.

## Scripts

- `0-iam_betty` : change l'utilisateur courant pour l'utilisateur `betty`.
- `1-who_am_i` : affiche le nom d'utilisateur effectif de l'utilisateur courant.
- `2-groups` : affiche tous les groupes dont l'utilisateur courant fait partie.
- `3-new_owner` : change le propriétaire du fichier `hello` pour l'utilisateur `betty`.
- `4-empty` : crée un fichier vide nommé `hello`.
- `5-execute` : ajoute la permission d'exécution au propriétaire du fichier `hello`.
- `6-multiple_permissions` : ajoute la permission d'exécution au propriétaire et au groupe, et la permission de lecture aux autres utilisateurs, sur le fichier `hello`.
- `7-everybody` : ajoute la permission d'exécution au propriétaire, au groupe et aux autres utilisateurs sur le fichier `hello`.
- `8-James_Bond` : définit les permissions du fichier `hello` : aucune pour le propriétaire et le groupe, toutes pour les autres utilisateurs.
- `9-John_Doe` : définit les permissions du fichier `hello` à `-rwxr-x-wx` (753).
- `10-mirror_permissions` : donne au fichier `hello` les mêmes permissions que le fichier `olleh`.
- `11-directories_permissions` : ajoute la permission d'exécution au propriétaire, au groupe et aux autres sur tous les sous-répertoires du répertoire courant, sans modifier les fichiers ordinaires.
- `12-directory_permissions` : crée dans le répertoire courant un répertoire nommé `my_dir` avec les permissions 751.
- `13-change_group` : change le groupe propriétaire du fichier `hello` pour `school`.
- `14-change_owner_and_group` : change le propriétaire pour `vincent` et le groupe pour `staff` de tous les fichiers et répertoires du répertoire courant.
- `15-symbolic_link_permissions` : change le propriétaire et le groupe du lien symbolique `_hello` pour `vincent` et `staff`, sans modifier le fichier vers lequel il pointe.
