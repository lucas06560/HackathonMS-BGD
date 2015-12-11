# HackathonMS-BGD


## Description
<p> Je suis PDG de la W.B, quel est le prochain film que je dois financer ? </p>
<p> Durée -> 9h </p>
<p> 2 étudiants -> <a href="https://github.com/Lahw">Yann Carbonne</a> / <a href="https://github.com/lucas06560">Lucas Weissert</a> </p>

### Notre objectif
"Décris-moi un film, je te prédis sa rentabilité"
<br/>

### Axes d'etudes
<p> Recuperation / Crawling : </p>
<ul>Site the-numbers.com pour les statistiques financières sur des films</ul>

  <ul><ul><li> http://www.the-numbers.com/movie/budgets/all </li></ul></ul>
  <ul><ul><li> http://www.the-numbers.com/market/{year}/top-grossing-movies </li></ul></ul>
<ul>Site imdb pour toutes les informations sur les films (acteurs, genre, notation ...)</ul>
  <ul><ul><li> http://www.imdb.com/ </li></ul></ul>

<br/>

### Prédiction de la rentabilité : Combien de $ gagnés pour 1$ dépensé ?
<p>Exemple :</p>
<code>getRentability('Action', ['Clint Eastwood','Evangeline Lilly', 'Charlie Sheen'])</code>
<p>Film d'action avec <u>Clint Eastwood</u>, <u>Evangeline Lilly</u> et <u>Charlie Sheen</u> : <b>4.53</b> de rentabilité </p>
### Analyse graphique
<p> Popularité des differents genres : </p>
![alt tag](https://github.com/lucas06560/HackathonMS-BGD/blob/master/tendance.png)

<p> Importance du genre de film dans notre algorithme de prédiction  </p>
![alt tag](https://github.com/lucas06560/HackathonMS-BGD/blob/master/prediction.png)

<br/>

### Améliorations :
  <ul><ul><li> Plus de données => Meilleure prédiction </li></ul></ul>
  <ul><ul><li> Permettre une prédiction sur une description texte d'un film </li></ul></ul>
