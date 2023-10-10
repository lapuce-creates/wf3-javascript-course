Écrivez un programme JavaScript qui affiche "Bonjour, monde !" dans la console.

//ma reponse

    var string1 = "Bonjour," 
    var string2 = " monde "
    var string3 = "!";
    mystring = string1 + string2 + string3;
    console.log(mystring);

 // correction
 
    var salutation = "Bonjour, monde !";
    console.log(salutation);

Créez une fonction qui prend deux nombres en entrée et les additionne. Appelez cette fonction et affichez le résultat dans la console.
// ma reponse

    function  add (a,b){
        let resultat = a + b;
        console.log (resultat)
    }


Écrivez un programme JavaScript qui vérifie si un nombre est pair ou impair et affiche le résultat dans la console.

//ma reponse

    function isEven(number) { 
        return number % 2 === 0; 
    }


Créez un tableau contenant trois noms, puis bouclez sur le tableau pour afficher chaque nom dans la console.

//ma reponse

    var array = ["Leah", "Sarah", "Slerah"];
for ( var i = 0; i < array.length; i++) {
    console.log(array[i]);
}
/*i represente le numero de l'emplacement du string du tableau, changer le i il faut determiner sa valeur, lui donner une limite de changement et le faire augmenter*/


Écrivez un programme JavaScript qui demande à l'utilisateur son prénom, puis affiche "Bonjour, [prénom] !" dans une boîte de dialogue.

//ma reponse

//inscrire prenom
//afficher Bonjour (prenom)
//alert boite de dialogue

var demande = "Entrez votre prénom";
 <!-- phrase1 + phrase2 = phrase3 -->


 function test(param1, param2, param3) {
 console.log(param1, param2, param3);
 result = (param1 + param2 + param3);
 }

 test("Bonjour, ", "prénom", " !");

//correction

var prenom = "John"; 
    // Remplacez "John" par le prénom que vous souhaitez afficher
alert("Bonjour " + prenom + " !");

Créez une fonction qui calcule l'aire d'un rectangle en prenant sa largeur et sa hauteur en entrée. Affichez le résultat dans la console.

Écrivez un programme JavaScript qui génère un nombre aléatoire entre 1 et 10, puis demande à l'utilisateur de deviner ce nombre. Donnez des indices pour aider l'utilisateur à deviner.

Créez une fonction qui prend une chaîne de caractères en entrée et retourne sa longueur. Affichez la longueur d'une chaîne donnée dans la console.

Écrivez un programme JavaScript qui calcule la somme des nombres de 1 à 100 et affiche le résultat dans la console.

Créez un tableau de nombres, puis utilisez une boucle pour trouver le plus grand nombre dans le tableau. Affichez ce nombre dans la console.