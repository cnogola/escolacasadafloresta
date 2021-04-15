---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "header_sobre.jpg" #splash_frontpage_3.jpg
widget1:
  title: "Quem Somos?"
  url: '/sobre/biografia/'
  image: IMG_6188.JPG
  text: 'Somos uma escola Waldorf que segue o curriculum e os princípios da pedagogia de Rudolf Steiner e da Antroposofia. Recebemos crianças desde o jardim de infância (a partir dos 3 anos de idade) até à 6ªclasse.'
widget2:
  title: "O Que Fazemos?"
  url: '/curriculum/'
  image: curriculum.JPG
  text: 'Educamos a criança partindo do pressuposto que a nossa principal tarefa é descobrir a intenção e a aptidão individual de cada ser humano que nos chega. Caminhando com a criança e ajudando na transformação dos obstáculos e desafios trabalhamos juntos para um futuro em que cada um possa agir de modo livre e consciente no mundo.'
  #video: '<a href="#" data-reveal-id="videoModal"><img src="/images/start-video-prep-for-life.JPG" width="302" height="182" alt=""/></a>'
widget3:
  title: "Onde Estamos?"
  url: '/contactos/'
  image: onde_estamos.jpg
  text: 'Em Lisboa, Monsanto. Inspirados pela maravilhosa floresta que nos envolve e sustenta.'
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
  url: /preinscricao/
  text: Pré-inscrição ›
  style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
