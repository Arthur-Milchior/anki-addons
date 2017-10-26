---
title: Deck name in title
main_file: deck_name_in_title.py
status: update planned
layout: addon
permalink: Deck_name_in_title.html
status_color: yellow
status_text_color: black
abstract: >
 Show the name of the deck you are currently learning in the window
 title.
first_image: deck_title.png
first_alt: "A window title: “Lernen::1 日本語::1 和独::VHS – Anki”"
ankiweb_id: 3895972296
extra_jq_script: dit_tips.js
---
Show the name of the deck you are currently <span class="qtbase
andprofile">learning</span> in the window title.

Taking a hint from some other applications, the <span class="qtbase
orprofile">deck</span> name is shown *before* the application name.

<blockquote class="nb">This is an Anki 2.0 plugin. I think i will update it to 2.1, but don’t know when i will get around to it. If you are impatient, you can of course do the update yourself. Please let me know which way you want your version published.</blockquote>


### Setup

The behavior of the add-on can be changed in a few points by editing
the
[source file](https://github.com/ospalh/anki-addons/blob/master/deck_name_in_title.py):

* `title_separator`: What to print between the deck name and program
  name. Normally a spaced en-dash.
* `show_subdeck`: Whether to show the subdeck you have descended into
  during learning or only the deck you clicked on in the deck
  browser.
* `subdeck_format`: How the point between the selected deck and the one
  descended into is marked. Standard is an en-dash between the two
  colons.
