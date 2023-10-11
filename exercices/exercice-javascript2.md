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

    //correction sayah
    console.log("Bonjour, monde !";)

Créez une fonction qui prend deux nombres en entrée et les additionne. Appelez cette fonction et affichez le résultat dans la console.
// ma reponse

    function  add (a,b){
        let resultat = a + b;
        console.log (resultat)
    }

//corrction sayah

    function add(number1, number2){
        return number1 + number2;
    }

Écrivez un programme JavaScript qui vérifie si un nombre est pair ou impair et affiche le résultat dans la console.

//ma reponse

    function isEven(number) { 
        return number % 2 === 0; 
    }
//correction sayah

    function estPairouImpair(nombre){
        if (nombre % 2=== 0) {
            return "pair";
        }
        else {
            return "impair";
        }
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

//corerction sayah

    let prenom = prompt("Entrez votre prenom")
    alert(`Bonjour, ${prenom} !`);

Créez une fonction qui calcule l'aire d'un rectangle en prenant sa largeur et sa hauteur en entrée. Affichez le résultat dans la console.

//ma reponse
// aire d'un rectangle c'est longueur * largeur
//var longueur , var largeur, multiplier les 2var

    function multiply(longueur,largeur){
        return longueur * largeur;
    }
        multiply(10,5);

//correction sayah

    console.log("l'aire de votre rectangle est " + longueur*largeur + " metres carres.");


Écrivez un programme JavaScript qui génère un nombre aléatoire entre 1 et 10, puis demande à l'utilisateur de deviner ce nombre. Donnez des indices pour aider l'utilisateur à deviner.



    let num = prompt("Entrez un nombre", number)
    function num(number) {
        let numAleatoire = Math.floor(Math.random(number)*10);
        if (num < numAleatoire ) {
            return "le nombre est plus petit.";
        } 
        else if (num > numAleatoire) {
            return "le numéro est plus grand.";
        }
        else (num === numAleatoire) {
            return "C'est exact, " + numAleatoire + " = " num + ".";
        }
    console.log(num, numAleatoire)
    }

//correction sayah
    //nombre entre 1 et 10, nombre entier
    //math.random() et math.floor() *10 pour avoir entre0 et 10
    //math floor de math random eest 0, ar entier plus petit entre 0 et 1 est 0

<!-- +1 par ce que le math random choisira entre 0 et 10 et nous on veut 1 et 10; -->
    var randomNumber = Math.floor(Math.random()*10)+1;
    var guess;

    do{
        guess= prompt("Devinez le nombre(entre 1 et 10) que j'ai choisi !");
            if (guess < randomNumber){
            alert("Trop petit !")}
            else if (guess > randomNumber){
            alert("Trop grand !")}
            else {
            (alert("Bravo ! Vous avez trouvé la solution !")) }
    }
    while(guess !== randomNumber)
    


Créez une fonction qui prend une chaîne de caractères en entrée et retourne sa longueur. Affichez la longueur d'une chaîne donnée dans la console.

// ma reponse
//creer fonction
// determiner chaine de caracteres
//retourner length
//afficher longueur chaine console

    function myString(string){
        console.log(string.length);
    }



Écrivez un programme JavaScript qui calcule la somme des nombres de 1 à 100 et affiche le résultat dans la console.

//ma reponse
//calcul de somme
//nombres des 1 a 100
//1+2+3+4+...+100 --> x<100 --> x = x+1
//resultat console --> resultat somme --> x+

    function add(i){
        for(i = 0; i < 100; i++);{ 
          console.log(i);
        }
    }
Créez un tableau de nombres, puis utilisez une boucle pour trouver le plus grand nombre dans le tableau. Affichez ce nombre dans la console.