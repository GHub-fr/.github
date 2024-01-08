Sur ce guide on va vous expliquer le HTML  

HTML (**Hypertext Markup Language** ; "langage de balisage d’hypertexte") dans sa dernière version "HTML5", est le langage de **balisage** conçu pour représenter et structurer [sémantiquement](https://fr.wikipedia.org/wiki/Sémantique) une page web.  

Il est souvent utilisé conjointement avec le langage de programmation [JavaScript](https://fr.wikipedia.org/wiki/JavaScript) et des [feuilles de style en cascade](https://fr.wikipedia.org/wiki/Feuilles_de_style_en_cascade) (CSS).  

HTML est inspiré du [Standard Generalized Markup Language](https://fr.wikipedia.org/wiki/Standard_Generalized_Markup_Language) (SGML). Il s'agit d'un format ouvert.

**Développé par**	[World Wide Web Consortium](https://fr.wikipedia.org/wiki/World_Wide_Web_Consortium) "W3C" & [WHATWG](https://fr.wikipedia.org/wiki/Web_Hypertext_Application_Technology_Working_Group)
- 1989-1992 : Origine
- 1993 : Apports de [NCSA Mosaic](https://fr.wikipedia.org/wiki/NCSA_Mosaic)
- 1994 : Apports de [Netscape Navigator](https://fr.wikipedia.org/wiki/Netscape_Navigator)
- 1995-1996 : HTML 2.0
- 1997 : HTML 3.2 et 4.0
- 2000-2006 : [XHTML](https://fr.wikipedia.org/wiki/Extensible_Hypertext_Markup_Language)
- De 2007 à nos jours : HTML 5 et abandon du XHTML 2

---

# Syntaxe de HTML

```
<TITLE>Exemple de titre</TITLE>
<p>
Ceci est une phrase avec un <a HREF="cible.html">hyperlien</a>.
Ceci est un paragraphe sans hyperlien.
</p>
<!-- Commentaire non visible -->
<pre> AB   C (permet de conserver les espaces)</pre>
```

---

## Explication
Cet exemple contient du texte, cinq balises et une référence d’entité :
- **<'TITLE'>** est la balise ouvrante de l’élément TITLE.
- **<'/TITLE'>** est la balise fermante de l’élément TITLE.
- Exemple de HTML est le contenu de l’élément TITLE.
- **<'A HREF="cible.html"'>** est la balise ouvrante de l’élément A, avec :
  - **HREF=cible.html**, l’attribut HREF dont la valeur est cible.html.
- **<'P'>** est la balise ouvrante de l’élément P. Toutefois, elle est utilisée ici comme s’il s’agissait d’un séparateur de paragraphe, et c’est même ainsi qu’elle est souvent présentée dans les plus anciennes documentations de HTML. Il s’agit de la balise ouvrante du paragraphe dont le contenu est Ceci est un paragraphe où; il n’y a pas d’hyperlien. La balise fermante de l’élément P, qui est optionnelle, est ici omise. L’élément P est implicitement terminé lorsqu’un nouveau paragraphe commence ou que l’élément parent est fermé (cas non présent).
- Les balises peuvent être indifféremment écrites en minuscules ou majuscules. L’usage des minuscules devient plus courant car XHTML les impose.
- **< !-- {CODE OU COMMENTAIRE} -- >** est la balise "commentaire" et permet de ne pas exécuter de code ou de laisser une note
- **<'pre'>** représente du texte préformaté, généralement écrit avec une police à chasse fixe. Le texte est affiché tel quel, les espaces utilisés dans le document HTML seront retranscrits

---

## Consulter le code d'une page

![d2tl4Oi0I7](https://github.com/GHub-fr/.github/assets/84735589/096b576d-3f49-4761-a132-7963769e28b4)

(Menu "clique droit" sur Chrome v.100+)

---

[view-source:](view-source:https://doc.ghub.fr/cours/html) (Peut être bloqué car il n'est pas censé être utilisé depuis une page web comme lien)  

- Ce lien permet de charger le **code source d'une page** (de la même façon que vous la créerez)
- Ouvrez le via "clique droit", puis "Afficher le code source"
- Vous retourne le fichier de base permettant de charger ce site

![chrome_Zf8S87O7vL](https://github.com/GHub-fr/.github/assets/84735589/aff1b890-46d5-40e1-8f1f-f4a0fb62d3ca)

---

Vous pouvez aussi **inspecter et modifier le code en direct** avec un **clique droit sur la page** (A.K.A "**DevTools**")  

- Il peut changer en fonction de votre navigateur
- Ouvrez le via un "clique droit" et "inspecter"
- Celui là permet de voire et modifier le code du site en temps réel

![chrome_Mgov4xW9UC](https://github.com/GHub-fr/.github/assets/84735589/d6272fe4-38a2-426b-941f-218f233d9976)

---

# Liste des éléments HTML

[MDN Qu'est ce qu'un élément HTML](https://developer.mozilla.org/fr/docs/Glossary/Element)

![image d'un élément HTML](https://developer.mozilla.org/fr/docs/Glossary/Element/anatomy-of-an-html-element.png)

- __**Liste complète des éléments**__ [sur le MDN Mozilla](https://developer.mozilla.org/fr/docs/Glossary/Element) "mozilla developer network"

---

## Exemple

[Liste MDN des éléments HTML](https://developer.mozilla.org/fr/docs/Web/HTML/Element)

- **<'html'>**	Représente la **racine d'un document HTML**. Tout autre élément du document doit être un descendant de cet élément.
- **<'head'>**	Fournit des informations générales (**métadonnées**) sur le document, incluant son titre et des liens ou des définitions vers des scripts et feuilles de style.
- **<'link'>**	Définit la **relation entre le document courant et une ressource externe**. Cet élément peut être utilisé pour définir un lien vers une feuille de style, vers les icônes utilisées en barre de titre ou comme icône d'application sur les appareils mobiles.
- **<'meta'>**	Représente toute information de métadonnées qui ne peut pas être représentée par un des éléments (**<'base'>, <'link'>, <'script'>, <'style'> ou <'title'>**)
- **<'style'>**	Contient des informations de **mise en forme** pour un document ou une partie d'un document. Par défaut, les instructions de mise en forme écrites dans cet élément sont écrites en **CSS**.
- **<'title'>**	L'élément **<'title'>** définit le **titre du document (qui est affiché dans la barre de titre du navigateur ou dans l'onglet de la page)**. Cet élément ne peut contenir que du texte, les balises qu'il contiendrait seraient ignorées.
- **<'body'>**	Représente le contenu principal du document HTML. **Il ne peut y avoir qu'un élément <'body'> par document.**
- **<'footer'>**	Représente le pied de page de la section ou de la racine de sectionnement la plus proche. **Un élément <'footer'> contient habituellement des informations sur l'autrice ou l'auteur de la section**, les données relatives au droit d'auteur (copyright) ou les liens vers d'autres documents en relation.
- **<'header'>**	L'élément HTML **<'header'>** représente du contenu introductif, **généralement un groupe de contenu introductif ou de contenu aidant à la navigation**. Il peut contenir des éléments de titre, mais aussi d'autres éléments tels qu'un logo, un formulaire de recherche, le nom d'auteur, etc.
- **<'h1'>, <'h2'>, <'h3'>, <'h4'>, <'h5'>, <'h6'>**	Les éléments **<'h1'>** à **<'h6'>** représentent six niveaux de titres dans un document, **<'h1'>** est le plus important et **<'h6'>** est le moins important.
