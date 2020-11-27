# pieddepage
Je code ici un pied de page de site web avec affichage pour petits écrans
# Principe
- on utilse le script function showSMenu(id)
- on ajoute la balise <span> suivante, là où l'on souhaite que le ménue se déploit sur les petits ecrans 
  <span id="showMorecot" class="showMe" onclick="showSMenu('cot');">+</span>
 - les éléments qui se déplient doivent avoir la class class="menupied", qui est en display:none par défaut dans la feuille de style pour petits ecrans.
 - On fait bien attention à ce que les noms correspondent (showMorecot, showSMenu('cot') et <div id="cot" ...>
  Lors d'un affichage pour petits écrans, seule la croix apparait, et si on clique sur la croix, le menue se déplie
