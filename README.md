Cathy Lachapelle - Site Web
===========================

Site statique publié sur GitHub Pages à l'adresse <https://www.cathylachapelle.com>.

Structure
---------

    index.html                    Cours de piano (page d'accueil)
    biographie/index.html         Biographie
    initiation-aupiano/index.html Initiation au piano
    tarifs-et-calendrier/         Tarifs et calendrier
    coordonnees/index.html        Coordonnées

    assets/style.css              Feuille de style unique du site
    assets/images/                Photo d'en-tête + illustration de chaque page
    assets/favicon.ico            Icône affichée dans l'onglet du navigateur

    calendrier-2014-2015/         Anciennes adresses du calendrier :
    calendrier-2017-2018/         redirigent vers tarifs-et-calendrier/

Modifier le contenu
-------------------

Le texte de chaque page se trouve entre les balises `<main id="texte">` et
`</main>`. Chaque paragraphe est entouré de `<p>` et `</p>`.

Le menu et le pied de page sont recopiés dans les cinq pages : une modification
au menu (nouvelle page, changement d'année dans « Tarifs et calendrier ») doit
être répétée dans chacune d'elles.

Aperçu local
------------

    python3 -m http.server 8000

puis ouvrir <http://localhost:8000> dans un navigateur.
