Voici dix exercices de programmation JavaScript, répartis en trois niveaux de difficulté, ainsi que 20 questions à choix multiples (QCM) correspondantes. VOus devrez envoyer avant la fin du temps imparti les réponses sur votre propre dépôt GitHub.

Exercices
Écrivez une fonction nommée add qui prend deux paramètres (a et b) et renvoie leur somme.

    function add (a,b){
     let resultat = a+b;
        return resultat;
        //exemple: add(1,2)
    }
//correction: 

    function add(a,b){
        return = a+b;
    } 

Créez une fonction multiply qui prend deux paramètres (x et y) et renvoie leur produit par additions successives.

    function multiply (x,y){
        let compteur = 0
        let produit = (x*y);
        return
    }

    //correction:

    function multiply(x,y){
        let resullt= 0;
        let count = 0;
        while (count <= y){
            result += x;  //result = result +x
            count++;  //count = count +1
        }
        return result;
    }
Écrivez une fonction isEven qui prend un nombre en paramètre et renvoie true s'il est pair et false s'il est impair
.
//pair: divise par 2, reste 0. modulo= %

    function isEven (number){
        return number%2===0;
    }
    
Écrivez une fonction reverseString qui prend une chaîne de caractères en entrée et renvoie cette chaîne inversée.


Créez une fonction findMax qui prend un tableau de nombres en entrée et renvoie le nombre le plus élevé.


Écrivez une fonction capitalizeWords qui prend une phrase en paramètre et renvoie la même phrase avec chaque mot en majuscules.


Écrivez une fonction filterEvenNumbers qui prend un tableau de nombres en entrée et renvoie un nouveau tableau contenant uniquement les nombres pairs.


Créez une fonction calculateFactorial qui prend un nombre entier positif en paramètre et renvoie sa factorielle.


Écrivez une fonction findLongestWord qui prend un tableau de mots en entrée et renvoie le mot le plus long.


    function findLongestWord(arr){
        let arr = ["string", "string", "string"];
        return arr.length
    }


Écrivez une fonction isPalindrome qui prend une chaîne de caractères en entrée et renvoie true si la chaîne est un palindrome (se lit de la même manière de gauche à droite et de droite à gauche), sinon renvoie false.


Questions à choix multiples (QCM)

Quelle est la sortie de console.log(typeof "123") ?

a) "string" ("bonne réponse")

b) "number" 

c) "undefined"

d) "boolean"

Quelle méthode JavaScript est utilisée pour supprimer le dernier élément d'un tableau ?

a) pop() ("bonne réponse")

b) shift()

c) splice()

d) push()

Quel opérateur est utilisé pour vérifier l'égalité stricte, c'est-à-dire que les valeurs et les types doivent correspondre ?

a) ==

b) === ("bonne réponse")

c) !=

d) !==

Comment déclarez-vous une variable en JavaScript ?

a) variable x;

b) let x;

c) var x; ("bonne réponse")

d) const x;

Quelle boucle JavaScript est principalement utilisée pour parcourir les éléments d'un tableau ?

a) while 

b) for ("bonne réponse")

c) do...while

d) forEach

Quelle méthode JavaScript est utilisée pour ajouter un élément à la fin d'un tableau ?

a) pop()

b) shift()

c) push() ("bonne réponse")

d) unshift()

Quel opérateur est utilisé pour vérifier si une valeur est supérieure à une autre en JavaScript ?

a) > ("bonne réponse")

b) <

c) ==

d) ===

Quelle méthode JavaScript est utilisée pour convertir une chaîne de caractères en minuscules ?

a) toLowerCase() ("bonne réponse")

b) toUpperCase()

c) trim()

d) charAt()

Quelle fonction JavaScript est utilisée pour générer un nombre aléatoire entre 0 et 1 ?

a) random()

b) Math.random() ("bonne réponse")

c) randomNumber()

d) Math.randomNumber()

Comment accédez-vous au premier élément d'un tableau appelé myArray en JavaScript ?

a) myArray[0] ("bonne réponse")

b) myArray.first()

c) myArray[1]

d) myArray.first