## .github/note/Code/Web/CSS/learning.md
---
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
<pre>
<!--
<TITLE>Exemple de HTML</TITLE>
<p>
Ceci est une phrase avec un <a HREF=cible.html>hyperlien</a>.
Ceci est un paragraphe sans hyperlien.
</p>
-->
</pre>
```
Cet exemple contient du texte, cinq balises et une référence d’entité :

- **<'TITLE'>** est la balise ouvrante de l’élément TITLE.
- **<'/TITLE'>** est la balise fermante de l’élément TITLE.
- Exemple de HTML est le contenu de l’élément TITLE.
- **<'A HREF=cible.html'>** est la balise ouvrante de l’élément A, avec :
- - **HREF=cible.html**, l’attribut HREF dont la valeur est cible.html.
- **<'P'>** est la balise ouvrante de l’élément P. Toutefois, elle est utilisée ici comme s’il s’agissait d’un séparateur de paragraphe, et c’est même ainsi qu’elle est souvent présentée dans les plus anciennes documentations de HTML. Il s’agit de la balise ouvrante du paragraphe dont le contenu est Ceci est un paragraphe où; il n’y a pas d’hyperlien. La balise fermante de l’élément P, qui est optionnelle, est ici omise. L’élément P est implicitement terminé lorsqu’un nouveau paragraphe commence ou que l’élément parent est fermé (cas non présent).
- Les balises peuvent être indifféremment écrites en minuscules ou majuscules. L’usage des minuscules devient plus courant car XHTML les impose.
- **<pre>< !-- {CODE OU COMMENTAIRE} -- ></pre>** est la balise "commentaire" et permet de ne pas exécuter de code ou de laisser une note
- **<'pre'>** représente du texte préformaté, généralement écrit avec une police à chasse fixe. Le texte est affiché tel quel, les espaces utilisés dans le document HTML seront retranscrits
