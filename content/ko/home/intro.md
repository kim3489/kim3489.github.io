---
# Use the Intro widget of the Blog template
widget: about.avatar

# This file represents a page section.
headless: true

# Order that this section will appear in.
weight: 10

author: admin
#design:
#  background:
#    color: '#090a0b'
#    text_color_light: true
#    video:
#      path:  # enter filename of a video in /assets/media
#  css_class: fullscreen

- block: collection
    content:
      id: section-1
      title: Interest
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - football
          - baseball
          
    design:
      view: community/custom_card
      columns: '2'

- block: collection
    content:
      id: section-1
      title: music
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - rock
          - hiphop
     
   
   design:
      view: community/custom_card
      columns: '2'
---

👋 Hi, there! I'm **Alice**, a machine learning researcher at Netflix.
    안녕하세요.
{style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}

Check out my [resumé](/about/) and portfolio below 😍
