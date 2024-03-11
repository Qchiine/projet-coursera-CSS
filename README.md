// Tableau de noms
var noms = ["Jean", "Jane", "Bob", "Alice", "Jack"];

// Fonction pour déterminer la salutation en fonction de la première lettre du nom
function saluer(nom) {
  // Obtenir la première lettre et la convertir en majuscule
  var premiereLettre = nom.charAt(0).toUpperCase();

  // Vérifier si la première lettre est 'J'
  if (premiereLettre === 'J') {
    console.log("Adieu " + nom);
  } else {
    console.log("Bonjour " + nom);
  }
}

// Boucler sur le tableau et appeler la fonction saluer pour chaque nom
for (var i = 0; i < noms.length; i++) {
  saluer(noms[i]);
}
