Installation du hook pre-commit :

1) Copier le hook dans .git/hooks :
   cp hooks/pre-commit .git/hooks/pre-commit

2) Rendre le hook exécutable :
   chmod +x .git/hooks/pre-commit

Le hook propose de générer suivi/commitInfo.txt à chaque commit (y/n).
