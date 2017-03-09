/REVISIONS

// Declarez une variable nommée "boucler" contenant true

// Declarez un tableau members contenant Aida67, lapie002, anneserrano, Jennysmille, nunkabuk, RCosson, kaonb-ax, FerEmilie, crazychouwi, KiluaZoldyc, patatobeur, Sam11360, elo062, hermeline, Biciclet,

// SI la variable boucler vaut true ALORS

  // Bouclez sur le tableau que vous avez déclaré ci-dessus

  // Mettre un switch pour qu'au moment où la boucle se trouve sur votre pseudo cela ajoute "Affiche " devant votre pseudo dans la console et sur l'écran et par defaut seulement le pseudo des autres

// FIN REVISIONS

// COURS AJAX
  // AJAX Jquery .ajax() ou .get()
  // Faites une requete vers l'API REST de Github pour récupérer les informations de votre compte


// FIN COURS AJAX


var boucler = true;

var tab=["Aida67", "lapie002", "anneserrano", "Jennysmille", "nunkabuk", "RCosson", "kaonb-ax", "FerEmilie", "crazychouwi", "KiluaZoldyc", "patatobeur", "Sam11360", "elo062", "hermeline", "Biciclet"];

for (var i=0; i<tab.length;i++) {

/*console.log(tab[i]);*/

switch (tab[i]) {

  case "Aida67":

  console.log("Affiche "+"Aida67");

  break;

  default:

  console.log(tab[i]);

  break;
}
}

