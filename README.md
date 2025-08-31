[README.md](https://github.com/user-attachments/files/22066969/README.md)
# Site Evenartliive

Ce dossier contient un site web statique complet pour l’association **EvenArt'live**. Il est composé de plusieurs pages HTML, de feuilles de style CSS et d’images. Le site permet :

- de présenter l’association et ses valeurs ;
- de lister les événements à venir et de proposer une réservation ;
- de recueillir des dons via un formulaire simple ;
- d’offrir un formulaire de contact et des informations pratiques.

## Structure des fichiers

* `index.html` : page d’accueil avec une section de présentation, un aperçu des prochains événements et un appel à soutenir l’association.
* `events.html` : liste détaillée des événements (titre, description, date, lieu) avec un bouton pour réserver.
* `reservation.html` : formulaire de réservation pour choisir l’événement, renseigner vos coordonnées et le nombre de places.
* `donations.html` : présentation des raisons de soutenir EvenArt'live et formulaire de don (non connecté à un moyen de paiement). La bannière utilise l’illustration `images/artwork.jpg`.
* `contact.html` : formulaire de contact et informations de contact de l’association.
* `style.css` : styles communs à toutes les pages. Les couleurs principales sont définies via des variables CSS en début de fichier et peuvent être facilement adaptées à votre charte graphique.
* `images/` : ce dossier contient :
  * `logo.png` : logo fourni par l’utilisateur pour l’association EvenArt'live.
  * `artwork.jpg` : illustration fournie par l’utilisateur servant de bannière dans la page des dons.
  * `event1.png`, `event2.png`, `event3.png` : illustrations abstraites générées pour représenter respectivement un concert, un atelier d’arts plastiques et une soirée caritative.

## Personnalisation

* **Logos et images** : vous pouvez remplacer les fichiers du dossier `images/` par vos propres visuels en conservant les mêmes noms de fichiers pour éviter de modifier le code. Pour ajouter de nouveaux événements, dupliquez un bloc `.event-card` dans `events.html` et ajustez l’image, le texte, la date et le lieu.
* **Couleurs et typographie** : modifiez les variables CSS en haut de `style.css` (`--primary-colour`, `--accent-colour`, etc.) pour adapter l’identité visuelle à vos préférences.
* **Formulaires** : les formulaires HTML actuels ne sont pas reliés à un serveur de traitement. Pour les rendre fonctionnels, vous devrez intégrer un backend (PHP, Node.js, etc.) ou un service tiers (Google Forms, Typeform, PayPal, etc.) et ajuster l’attribut `action` des balises `<form>`.

## Aperçu

Pour visualiser le site en local, ouvrez simplement `index.html` dans votre navigateur. Les liens de navigation vous permettront de parcourir les différentes pages.
