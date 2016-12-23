# Retour sur ton travail

Une idée de présentation originale et ça peut rendre pas mal! Par contre il faut affiner un peu tout ça... Et pour rappel, le portfolio c'est pour te présenter toi et pas faaire la description de technos qui ne manque pas de descriptions ;). 

# Retour sur ton design

Pour ton slider, soit tu harmonises la taille de tes images, soit tu régles ton caroussel, mais tu peux pas laisser ton site tressauter pour s'adapter à la dernière image.

Il faut que tu fasses une présentation avant ton caroussel pour qu'on sache à quoi ton site sert, parce que là c'est pas du tout clair. 

Il faut que tu revois la navigation de ton slider, là on les voient à peine (ne va pas dans l'extrême non plus hein)

Si tu décides de mettre ton site dans la classe `container` et non `container-fluid` il faut que tu exploites les marges restantes au lieu de les laisses blanches (une couleur unie, une image en mode wallpaper par exemple).

La présentation de tes technos est intéressante! Par contre il faut que tu réduises la taille de tes polices, pour info la taille de base est de 12px. Et à l'inverse, le logo des technos est trop petit. Sinon ça ne sert à rien de répéter les illustrations de ton slider dans la présentation de tes technos. Il faut que tu trouves d'autres illustrations pour varier.

Dans la navbar, il est commun que le nom du site soit aligné à ĝauche et la partie vraiment navigable aligné à droite; pour qu'on puisse savoir clairement quel est le nom de ton site.

Sur le contenu, tu n'es pas le roi de la grammaire (moi non plus, mais tu es pire que moi), du coup je te conseille TRES fortement de faire relire ton site par quelqu'un qui le soit. Et méfie toi des traducteurs, y a des endroits où ils ont traduit n'importe comment.

Il te manque les sections sur les réseaux sociaux et sur tes projets; c'est un peu le principe de base sur un portfolio!! Il va falloir rapidement intégrer ces sections et bien réfléchir à où tu les placent. De plus tu ne parles de toi à aucun moment...

Je te recommende de mettre soit un screen de ton IDE, soit utiliser une bibilio JS/CSS qui fait un contenu qui ressemble à un IDE, parce que une simple balise `pre`, ça fait pas très beau pour une démonstration de ton code. D'ailleurs au sujet de démonstration, hum, le code d'un footer n'est pas très impressionnant. Je suis sûr que tu as déjà fait mieux! 

Fait gaffe à l'utilisation de ton pseudo, actuellement on ne connait pas ton vrai prénom/nom sur ton portfolio, or ce sont des recruteurs IRL qui iront sur ton portfolio. Ce n'est pas un blog dans lequel tu parles de techno, c'est une passerelle entre ton toi IRL et ton toi ONLINE.

Il va falloir réfléchir à des couleurs et essayer de personnaliser un peu la navbar de base de bootstrap.

La séparation entre tes technos est trop fine (surtout que c'est un `hr`...)

# Retour sur ton code

Pour commencer, bon travail pour avoir réussi à utiliser le caroussel de bootstrap! Hormis les petits détails cité plus tôt, c'est une réussite!

Si tu utilises les liens vers les CDN, tu as pas besoin de tout le repo de Bootstrap sur ton projet.

Si jamais tu veux utiliser une techno et garder sa source, tu crée un dossier `vendors` dans le dossier root, et dedans tu met les repo entier. Par contre dans tes véritables dossiers de boulot, tu met uniquement les fichiers dont tu as besoin. Tout ce qui n'est pas appelé par tes fichiers est inutile et n'a pas sa place dans ton dossier de travail. 

Si tu souhaites utiliser un fichier Json et un Gruntfiles, sache qu'il sont à mettre dans ton dossier root. 

Si tu comptes faire plusieurs pages, il faut que tu crée un dossier `pages` et que tu les stocks toutes dedans, hormis le `index.html` qui doit rester dans le dossier de root.

Pour info, le dossier `dist` est le dossier dans lequel les fichiers de productions sont stockés et le dossier `src` est le dossier qui sera voué à être exploiter par les moteurs de recherches.

Félicitation, tu es le seul à avoir exploiter ton readme.md! Par contre fait le corriger au niveau de la grammaire.

La navbar de bootstrap est à mettre à l'extérieur de la `<div class="container">`. D'ailleurs, soit tu utilises le `container` et te limite à une grille de 1080px, soit tu utilises le `container-fluid` qui s'adapte à la taille de ton écran, mais pas les deux.

Pas de style dans le HTML, ça fait pas pro!

L'indentation est à revoir par endroit, des fois tu met deux tabulations au lieu de une seule, des fois tu en met pas du tout alors qu'il faut... il va falloir refaire ça proprement.

Le `hr` ça fait pas pro... une `div` avec un `border-bottom: 1px grey solid` ça fait tout de suite mieux!

Le CSS de bootstrap doit être appeler avant ton CSS perso. En effet le principe du CSS (cascading stylesheet) est que l'élément qui vient après le précédent a la priorité (d'où le principe de la cascade qui gagne en puissance au fur et à mesure qu'on descend). Du coup si tu déclares ton CSS perso avant celui de bootstrap, les classes de bootstrap passeront en prio dessus.

Tu as un fichier `redstrap.css` dont je ne sais pas trop à quoi il sert ? Sinon la structure de ton CSS ne saute pas aux yeux et manque de commentaire. D'ailleurs ton HTML manque aussi de commentaires. Et il va falloir sanitiser ton CSS.

Ton HTML est très bien démarrer, continue comme ça! Juste un effort à faire sur l'indentation. 

# Remarques finales

Des efforts ont été fait et tu es en bonne voie! Par contre tu as beaucoup d'ambition sur ton portfolio, notamment avec SASS qui est une techno utilisé par les front alors que tu veux faire du back... C'est une bonne chose d'avoir de l'ambition, mais il faut que tu sois sûr de finir dans les temps, surtout que tu as encore des réflexions graphiques à faire! Enfin c'est toi le vrai juge de ce que tu es capable ou non de faire, mais sache que la deadline sera la même pour tous...

Bon courage Red!

Sinon pour git, encore bravo pour avoir penser à utiliser le readme.md, par contre il va falloir faire un peu plus de commit et commencer à les faire en anglais. Sinon commence à te renseigner pour ta github pages.