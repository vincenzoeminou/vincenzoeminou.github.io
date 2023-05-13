---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "vm.jpg"
widget1:
  title: "Luogo cerimonia"
  url: 'https://vincenzoeminou.github.io/cerimonia/'
  image: chiesa.jpg
  text: 'La cerimonia si svolgerà a Pisa, nella chiesa di Santa Croce in Fossabanda'
widget2:
  title: "Location?"
  url: 'https://vincenzoeminou.github.io/location/'
  image: cafaggio.jpeg
  text: 'Festeggeremo il nostro matrimonio tra il verde delle colline di San Miniato, presso l'Azienda Agricola e Agrituristica Cafaggio'
widget3:
  title: "Il nostro viaggio di nozze"
  url: 'https://vincenzoeminou.github.io/viaggio'
  image: viaggio.jpg
  text: 'Abbiamo deciso di fuggire qualche giorno a fine settembre. Qui puoi scoprire le tappe del nostro viaggio e, se vuoi, aiutarci a realizzare questo sogno'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
