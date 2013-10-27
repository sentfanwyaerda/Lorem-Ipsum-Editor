Lorem Ipsum Editor
==================

*(for short: LIE)*

A generic CMS plug-in to provide an **WYSIWYEdit** approach to static HTML and templates. In fact, it allows to edit the (dummy) Lorem Ipsum texts most webdesigners place in their design to show how the texts at particular features will be visualized. Just *double-click* and edit, and edit again and again.

Implemented restrictions and capabilities:
- allows only edit of textual area's (identified by Xpath, or even only of particular *class*es)
- allows only bold, italic, strike-through, underline, links and a minimal selection of multi-markdown
- allows changing the *class* to a defined style
- supports qTranslate-styled multi-lingual editing, e.g.: ``[:en]English[:nl]Nederlands[:it]Italiano``
- uses a JSON/AJAX API to communicate with the implented CMS/plug-in (which authenticates the rights to edit)
- live preview
