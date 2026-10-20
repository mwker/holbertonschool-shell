# Shell, redirections d'E/S et filtres

Ce projet contient des scripts Bash pour apprendre à utiliser les redirections d'entrée/sortie, les pipes et les filtres sous Linux.

## Scripts

- `0-hello_world` : affiche `Hello, World` suivi d'un saut de ligne sur la sortie standard.
- `1-confused_smiley` : affiche le smiley perplexe `"(Ôo)'`.
- `2-hellofile` : affiche le contenu du fichier `/etc/passwd`.
- `3-twofiles` : affiche le contenu des fichiers `/etc/passwd` et `/etc/hosts`.
- `4-lastlines` : affiche les 10 dernières lignes du fichier `/etc/passwd`.
- `5-firstlines` : affiche les 10 premières lignes du fichier `/etc/passwd`.
- `6-third_line` : affiche la troisième ligne du fichier `iacta`.
- `7-file` : crée un fichier nommé `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` contenant le texte `Best School` suivi d'un saut de ligne.
- `8-cwd_state` : écrit le résultat de la commande `ls -la` dans le fichier `ls_cwd_content`, en le créant ou en l'écrasant.
- `9-duplicate_last_line` : duplique la dernière ligne du fichier `iacta`.
- `10-no_more_js` : supprime tous les fichiers ordinaires ayant l'extension `.js` dans le répertoire courant et ses sous-dossiers, sans toucher aux répertoires.
- `11-directories` : compte le nombre de répertoires et sous-répertoires du répertoire courant, y compris les répertoires cachés, sans compter `.` et `..`.
- `12-newest_files` : affiche les 10 fichiers les plus récents du répertoire courant, un par ligne, du plus récent au plus ancien.
- `13-unique` : affiche, triés, les mots de l'entrée qui n'apparaissent qu'une seule fois.
- `14-findthatword` : affiche les lignes du fichier `/etc/passwd` contenant le motif `root`.
- `15-countthatword` : affiche le nombre de lignes du fichier `/etc/passwd` contenant le motif `bin`.
- `16-whatsnext` : affiche les lignes du fichier `/etc/passwd` contenant le motif `root`, ainsi que les 3 lignes qui suivent chacune d'elles.
- `17-hidethisword` : affiche les lignes du fichier `/etc/passwd` qui ne contiennent pas le motif `bin`.
- `18-letteronly` : affiche les lignes du fichier `/etc/ssh/sshd_config` qui commencent par une lettre, minuscule ou majuscule.
- `19-AZ` : remplace dans l'entrée tous les caractères `A` par `Z` et `c` par `e`.
- `20-hiago` : supprime toutes les lettres `c` et `C` de l'entrée.
- `21-reverse` : inverse l'entrée.
- `22-users_and_homes` : affiche tous les utilisateurs et leur répertoire personnel à partir du fichier `/etc/passwd`, triés par nom d'utilisateur.
