<h1>Plugins Jquery intéressants</h1>

<p>Animstition : https://github.com/blivesta/animsition</p>
<p>ScrollMe : https://github.com/nckprsn/scrollme</p>
<p>Vide : https://github.com/vodkabears/Vide/</p>

<h2>Créer un commit</h2>

<p>Après avoir modifié un fichier (et en partant du principe que le repository existe sur ma machine) :</p>
<ul>
<li>Je lance une commande <code>git status</code> pour voir quels fichiers ont été modifiés.</li>
<li>Je lance une commande <code> git add README.md</code> pour ajouter le fichier aux modifications validées.</li>
<li>Je vérifie que la modification sera bien prise en compte en lançant un second <code>git status</code>.</li>
<li>Je fais un commit pour décrire quel type de modification a été effectuée, ici par exemple <code>git commit -m "Création de la liste explicative et ajout du plugin VIDE"</code>.</li>
<li>J'envoie mon fichier sur le serveur distant grace à un <code>git push</code> (ou un <code>git push -u origin master</code> si c'est la première fois que j'effectue un push vers ce repository)</li>
<li>J'entre mes identifiants dans la console.</li>
</ul>