Dans la console, j'ai effectué les commandes suivantes:

cd //emplacement du dossier
git init

J'ai ensuite créé un nouveau repository sur GitHub

git remote add origin https://github.com/Chaos-Potatoe/PartielGitHub.git

git add PartielGitHub

git add PartielGitHub.sln

git add README.txt

git commit -m "Premier envoi Partiel GitHub"

git push -u origin master

J'ai entré mon nom d'utilisateur et mon mot de passe

git checkout -b dev

git add PartielGitHub

git add PartielGitHub.sln

git add README.txt

git commit -m "Second Envoi Partiel GitHub"

git push -u origin dev

git checkout master

git merge dev

git fetch

git pull origin master



