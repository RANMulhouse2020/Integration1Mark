# Integration1Mark

Bonjour à tous ! Voici ma version de ce projet d'intégration où le but était de découvrir le plus Bootstrap et vous sensibiliser au sujet du responsive ! 

Pour faire cela j'ai donc employé le plus possibles des **classes Bootstrap existantes** pour obtenir ce que je désirais (c'est à dire que ce soit responsive et le plus provhe de la maquette d'origine).

## Marging et Padding

Par exemple, j'ai beaucoup quelques **mb-x**, **mt-x** et **pl-x** ou autres, qui sont des classes de Bootstrap permettant de gérer les margins et paddings (avec *t = top*, *r = right*, *b = bottom* et *l = left* ) même si ce ne sont pas les tailles de marges et paddings désirées (dans le **but de découvrir Bootstrap**). Quand les classes de Bootstrap ne suffisaient pas, j'ai ajouté mes propres classes pour que tout aille bien.

## Background-image (pour la première partie/section/header, peut importe comment vous l'appelez)

Vous l'aurez sans doute remarquez, nous avions une image de fond pour le début de notre maquette (nos *fameseuse bottes de foin*). J'ai **fait le choix (car je n'ai pas de collègues web-designer avec qui parler sur ce projet)** d'avoir la première *section* de notre site qui doit avoir une hauteur égale à celle de l'écran, de ce fait, dans mon HTML, via Bootstrap j'ai pu écrire : 
```html
 <div class="row vh-100">
```
et de ce fait utiliser une classe Bootstrap existante pour faire qu'un *morceau de notre structure HTML* fasse toujours *la hauteur de l'écran sur lequel on voit le site*
