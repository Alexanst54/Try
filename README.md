# À mots chantés

Petit jeu musical autonome pour une animation d'équipe. Ouvrez `index.html` dans un navigateur moderne : aucune installation, connexion Internet ou piste audio nécessaire. Vous pouvez copier ce fichier seul sur une clé USB.

## Préparer une partie

1. Dans **Préparer les chansons**, ajoutez le titre, l'artiste et un extrait de paroles.
2. Classez chaque extrait par difficulté et catégorie. Pour la catégorie anglaise, saisissez les paroles traduites en français.
3. Prévoyez une chanson par catégorie et difficulté : 6 chansons pour un niveau, 18 pour les trois niveaux. Plusieurs chansons par catégorie permettent de varier le tirage.
4. Exportez une sauvegarde JSON. Les données locales dépendent du navigateur et de l'emplacement du fichier ; importez la sauvegarde sur l'ordinateur utilisé pour l'animation. L'import ajoute les chansons dont l'identifiant est nouveau et conserve les chansons existantes.

Aucune chanson protégée n'est fournie. Ajoutez des extraits que vous êtes autorisé à utiliser. Les difficultés dépendent des extraits choisis par l'animateur.

## Animer

Choisissez une difficulté et lancez la manche. Chaque manche tire une chanson par catégorie, dans l'ordre : années 80, 90, 2000, 2010, 2020, puis chanson anglaise traduite. Lisez l'extrait à voix haute sans chanter ; les participants cherchent le titre. Révélez la réponse, puis passez à la chanson suivante.

Le **mode projecteur** masque l'en-tête et le pied de page et demande le plein écran. Si le navigateur refuse le plein écran, l'affichage épuré reste disponible. Les commandes restent accessibles en bas de la page. L'éditeur de chansons est séparé de l'écran de jeu ; il n'y a pas de score ou de panneau de supervision.

Raccourcis lorsque le fond de la page a le focus : **Espace** pour révéler/avancer, **F** pour le mode projecteur, **Échap** pour le quitter. Les boutons restent utilisables au clavier avec Tab et Entrée.

## Vérification et développement

Application HTML/CSS/JavaScript sans dépendances ni compilation. Aucun serveur requis. Pour une vérification HTTP facultative : `python3 -m http.server 8000` depuis le dossier du dépôt.

Parcours à vérifier : ajout et modification d'une chanson, sauvegarde après réouverture, export/import, six catégories requises pour démarrer, révélation et progression sur six chansons, plein écran, retour à l'accueil.
