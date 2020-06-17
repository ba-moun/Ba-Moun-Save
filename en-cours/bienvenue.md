---
title: Bienvenue
description: Bienvenue dans la branch d'édition de Ba-Moun𓅝Save.
published: true
date: 2020-06-17T22:18:12.640Z
tags: bienvenue, guide d'édition, scribe, écrire dans ba-moun𓅝save
editor: markdown
---

# Guide d'édition Ba-Moun𓅝Save
Bienvenue, félicitations et merci pour l'nitérêt que vous portez à [<a href="/fr/home" style="font-family:'Yatra One', 'PT-Serif', serif;color: gold" >Ba-Moun𓅝Save</a>.

![interface-de-ba-moun-save.png](/images/ba-moun-save/interface-de-ba-moun-save.png)

# Créer une nouvelle page

Dans le but de créer une nouvelle page, cliquez sur le bouton *Créer une nouvelle page* (voir première image de cette page). La boite de dialogue suivante apparait.

![creation-de-nouvelle-page.png](/images/ba-moun-save/creation-de-nouvelle-page.png)

1. Choisissez la langue de la page à créer. La langue actuelle est sélectionnée par défaut.
2. Saisissez le chemin complet menant vers la page à créer.
   * Le chemin ne doit pas contenir d'espace. Utilisez des tirets à la place. Vous n'avez droit qu'à des caractères alphanumériques.
   * NE PAS mettre de barre oblique.
   * Il n'est pas nécessaire de créer des dossiers. Saisissez le chemin complet menant vers la page. Les dossiers seront créés automatiquement. Par exemple, en saisissant univers/planète/terre, les dossiers univers et planète sont créés automatiquement s'ils n'existent pas.
3. Cliquez sur *SELECT* pour poursuivre.

# Sélectionner un éditeur

À la création d'une nouvelle page, la boîte de dialogue suivante s'affichera.

![sélectionner-editeur.png](/images/ba-moun-save/sélectionner-editeur.png)

Vous avez le choix entre plusieurs éditeurs. Choisissez l'éditeur en fonction du contenu que vous souhaitez rédiger. Vous pouvez aussi choisir l'éditeur en fonction de vos préférences. Les informaticiens ont habitiellement une préférence pour l'éditeur Markdown. Les personnes non techniques ont des préférences pour l'éditeur visuel.

Référez-vous à la section suivante pour une liste complète des éditeurs. Vous y verrez comment les utiliser.

# Editeurs

Vous pouvez utiliser l'éditeur de votre choix à la création d'une page. Certains utilisateurs préfèrent l'éditeur Markdown. D'autres préfèrent l'éditeur visuel.

> Une page créée avec un éditeur sera obligatoirement modifiée avec ce même éditeur.
{.is-warning}

## Éditeur Markdown

L'éditeur Markdown fournit un système de balise. Les sites Web comme GitHub fournissent de tels éditeurs. Ci-dessous une liste non exhaustive des balises mises à disposition.

### Tabs {.tabset}

####  Onglets

Ajoutez *{.tabset}* à la fin de l'en-tête parente.

> L'en-tête parente n'est pas affichée.
{.is-info}

Vous pouvez utiliser n'importe quel niveau d'en-tête avec *{.tabset}*. Vous devez utiliser des en-têtes de niveau supérieur par la suite. Les en-têtes de niveau supérieur seront le nom des onglets.Par exemple, si l'en-tête parente est ### (h3), les onglets doivent avoir une en-tête de niveau #### (h4). Le niveau maximum d'une en-tête parente est 5. Le niveau maximum pour une en-tête enfant est 6.

##### Exemple

`# Tabs {.tabset}
## First Tab

Any content here will go into the first tab...

## Second Tab

Any content here will go into the second tab...

## Third Tab

Any content here will go into the third tab...`

## Éditeur Code
bép

## Éditeur visuel
péb

# Enter Page Metadata

Upon selecting an editor, you'll be prompted with the Page Metadata dialog:

Page Metadata Dialog

Enter a title, description and tags for your page.

Finally, click OK to close the dialog and start writing!

    You can always return to the Page Metadata dialog later by clicking the Page button, located in the upper-right corner of the page.

# Save

Your page is not created until you hit the Create button (located in the upper-right corner of the page). It will be saved and rendered, after which you'll automatically be redirected to the final result. Simply click the edit button to go back to editing!