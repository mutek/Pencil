cambio branch con:

git checkout gh-pages

e poi applicare il normale UpdateGithub.sh

git config --global user.name "mutek"
git config --global user.email mutek@inventati.org

git add .

git commit -a -m "COMMENTO"

git push origin gh-pages

torna al branch precedente master con

git checkout master

