ETAPES JS #1

1. Créer le bouton Dark/Mode Sombre (récupérer un bouton sur Bootstrap et l'inclure dans votre navbar)

2. Créer un fichier main.js et le lier à votre HTML

3. Créer une première variable isClicked let isClicked = false; 
-> Cette variable va nous permettre de définir l'état du bouton 'Dark'

4. Créer les variables qui vont récupérer vos différents éléments HTML à modifier (titres, body, image, logo, bouton etc) avec soit getElementById si vos éléments HTML ont des id, soit querySelector (ou querySelectorAll si vous voulez changer plusieurs éléments HTML d'un meme type, par exemple toutes vos balises <h2>)

5. Faire un addEventListener sur le bouton 'Dark'
-> Au clic, notre fonction contiendra une condition du type :  

 if (isClicked == false) {
    isClicked = true;
    // on change tous nos éléments HTML avec soit des classList.add(), classList.replace(), ... pour activer le mode sombre
 }

 else {
    isClicked = false
    // on repasse tous nos éléments HTML à l'état initial avec classList.remove(), classList.replace() pour revenir au mode light
 }


Aide -> voir les Codepen suivants que l'on a fait ensemble :
- changer une image au clic (trotro)
- ajouter ou retirer une class
- utiliser getElementById