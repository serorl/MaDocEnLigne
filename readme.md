## Madocumentation en ligne

## sommaire

   Git
   markdown

# Git
*****

…création d'un repository on ligne de commande

echo "# MaDocEnLigne" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git remote add origin https://github.com/serorl/MaDocEnLigne.git
  git push -u origin master

... envoyer sur un repository existant sur la branch master 

git remote add origin https://github.com/serorl/MaDocEnLigne.git
  git push -u origin master

... copier un repository existant 

