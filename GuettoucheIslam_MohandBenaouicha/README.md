// Pour la compilation et la génération des exécutables :
$user: make


// Pour générer un texte qui prendra deux paramètres (la longueur du texte à générer puis la taille de lalphabet) :
$user : cd document_teste
$user : ./genere-texte longueurTexte tailleAlphabet
//Le texte s'affichera sur la sortie stantard et il va également être créer dans un fichier "Texte.txt"


// Pour générer un ensemble de mots dont le générateur prendra 4 paramètres (le nombre de mots à générer puis la longueur minimale et la longueur maximale
 des mots et enfin la taille de lalphabet) :
$user : cd document_teste
$user : ./genere-mots NombreMots longueureMin longueurMax tailleAlphabet
//L'ensemble de mots s'affichera sur la sortie stantard et il va également être créer dans un fichier "Mots.txt"


// Pour appliquer l'algorithme d'Aho Corasick en utilisant les 3 méthodes :
$user : cd document_teste
$user :./ac-matrice Mots.txt Texte.txt

$user : cd document_teste
$user :./ac-liste Mots.txt Texte.txt

$user : cd document_teste
$user :./ac-mixte Mots.txt Texte.txt