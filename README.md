# IG2I - Semestre 2 Module WEB - TP1

## Objectif
Manipuler la syntaxe des langages XHTML et CSS ; découvrir les bonnes pratiques de mise en forme à l'aide de (X)HTML et CSS.

## Plan de la séance
### Préambule :
1. Test (15 minutes)

2. Discussions autour des IDE pour le WEB, chaque élève doit avoir la maîtrise de son IDE préféré

3. Installation & Présentation de l'outil Firebug / Console Web :
	*visualisation de la structure HTML d’un des fichiers d’exemple
	*modification dynamique du CSS depuis Firebug
	
4. Rappel des bons sites de documentation : W3schools, Alsacréations, A list apart

5. Pour chaque exercice du TP, un fichier HTML de base est fourni, il faut le compléter en suivant les indications de l'énoncé.

6. Pour chaque exercice du TP, une fois terminé, vous validerez votre travail à l'aide du validateur du W3C et appellerez l'enseignant pour débriefer. Vous sauvegarderez vos exercices pour pouvoir les retrouver plus tard.

7. Les exercices libellés 'TNE' devront être terminés à l'occasion du TNE

8. Vous devrez rendre un CV en HTML/CSS/JS “valide” d’ici la fin du module de Frontend

### Exercice 1 : Paragraphes
**Objectif : mise en forme de base par CSS ; utilisation des identifiants et des classes**

1. Styliser des paragraphes en leur associant identifiants et classes. Changer leur style par des sélecteurs. Faire apparaître leurs boites. Supprimer les retours à la ligne de leur contenu.

2. Déplacer le code CSS dans un fichier de style séparé.

### Exercice 2 : Les copains d'abord (exemple 1)
**Objectif : mise en forme de base par CSS ; utilisation d'un style interne à la page**

1. Ajouter le titre « Fluctuat Nec Mergitur ! » à la fenêtre de ce document

2. Insérer un titre de premier niveau dans le corps du document, comportant le texte 'Fluctuat Nec Mergitur'

3. Placer chaque paragraphe dans une balise de paragraphe HTML

4. Insérer une balise de style interne dans le document, utiliser cette balise pour mettre en oeuvre les modifications ci-dessous. On ne modifie rien au contenu HTML à partir de maintenant :
	*Les paragraphes sont justifiés de chaque côté
	*Le titre est centré, en italique, transformé en majuscules ; sa marge en bas est de 50px;
	*Chaque paragraphe est indenté de 30px Pour faciliter la lecture et économiser de l'énergie, on soigne le contraste : le fond est noir, le texte n'est pas tout à fait blanc (couleur #ddd) ce qui le rend moins agressif pour les yeux.
	*Une marge de 30 px sépare le contenu des bords de la fenêtre horizontalement, 50px verticalement;
	
5. On souhaite mettre en place une lettrine pour le premier paragraphe : Le « L » est d'une taille beaucoup plus grande ; il est dans une boite avec des bordures apparentes, de couleur de fond gris clair, qui flotte à gauche du premier paragraphe.

6. Nous souhaitons l'écrire dans une police de caractères cursive, que nous venons de télécharger du site 1001freefonts.com. Pourquoi n'est-ce pas une bonne idée ? Comment être sûr que notre navigateur choisira effectivement une police cursive ?

7. Nous souhaitons supprimer l'indentation du paragraphe associé à notre lettrine. Comment faire ? Visualiser le style de ce paragraphe dans Firebug. Que remarquez-vous ? Comment est calculé le style du premier paragraphe ?

### Exercice 3 : Figures (exemple 2)

8. Nous souhaitons pouvoir placer une image et sa légende avant chaque paragraphe de l'article précédent, de sorte que l'image se place par défaut à droite du paragraphe. Ces images porteront la classe « figure ». L'image ne devra pas faire plus de 150px ; être encadrée par une bordure ; être centrée ; sa légende sera centrée également.

9. On souhaite parfois placer des images à gauche. Comment proposer cette fonctionnalité en utilisant une seconde classe ? Expliquer les règles de cascade qui permettent d'imposer le bon style.

10. Validez votre page ou consultez la documentation de référence sur la balise image. Quels sont ses deux attributs obligatoires ? A quoi servent-ils ?

11. Nous souhaitons que la légende apparaisse uniquement lorsque la souris se déplace sur cette image, comment le définir directement en utilisant la structure XHTML ?

12. Nous souhaitons finalement qu'un clic dans la figure mène à une page différente, à l'aide d'un lien hypertexte. Définir les propriétés de ce lien pour qu'il ne change pas d'apparence si l'utilisateur a déjà visité la page cible.

13. Nous voulons mettre en forme une signature pour l'article, dans un bloc d'identifiant « signature », qui sera affiché sous une barre horizontale, à 10px du bas de la page. Proposer une solution sans utiliser de balise `<hr />`

14. Changer le facteur de zoom de votre page pour y faire apparaître un ascenseur vertical. Déplacer l'ascenseur. Que se passe-t-il ? Comment éviter ce phénomène ? Développer une solution permettant de donner l'impression que le texte disparaît sous une signature semi-transparente.

15. Valider, tester dans chrome et IE

16. Question subsidiaire (TNE) : comment faire numéroter automatiquement les légendes des figures de la page ? Renseignez-vous sur les compteurs et le code généré par CSS.

### Exercice 4 : Galerie d'images
**Objectif : approfondissement des attributs de position**

1. Créer une galerie d'images à partir d'un ensemble de balises images, sans rien changer à la structure du fichier XHTML fourni. On produira des cadres de 200x250 pixels.

2. 2ème version : les cadres d'images « s'allument » lorsque la souris les survole, le curseur de la souris change de forme comme s'il s'agissait d'un lien.

### Exercice 5 : Structure de navigation
**Objectif : définir une structure de navigation à l'aide de listes ; étudier le mécanisme d'import de fichiers css par type de média**

On utilise le fichier joint, qui définit deux listes de liens, nommées respectivement « banniere » et « sommaire ». L'intérêt de procéder à l'aide de ce type de structures simples est que la page est encore fonctionnelle en désactivant la feuille de style, ce qui permet à des navigateurs peu évolués, ou très contraints d'offrir un rendu satisfaisant.

1. Dupliquer la page fournie et compléter les liens hypertextes à l'aide d'adresses relatives pour avoir un site fonctionnel. Compléter également les titres des pages

2. Styliser la bannière pour lui donner l'apparence d'une barre d'onglets horizontale. L'élément portant la classe « selectionne » devra être repérable facilement.

3. Styliser le sommaire pour lui donner l'apparence d'une barre d'onglets verticale. L'élément portant la classe « selectionne » devra être repérable facilement.

4. Définir une feuille de style alternative pour l'impression qui cache les listes sommaire et banniere.

5. Étudier et comprendre les 4 structures de navigation proposées dans les fichiers joints

6. TNE : on mettra en œuvre des styles de menu déroulants, avec javascript
