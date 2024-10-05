---
# Homepage
title:
type: landing

sections:
  - block: features
    content:
      title: <span style="font-size:70%">Kcw Web </span>
      text: <br><span style="font-size:125%">Welcome to the website of Kim Chan-woo, a sophomore computer artificial intelligence student at Jeonbuk University.</span> <br><br>

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">My Interests</span>
      items:
        - name: Front-end
          icon: sitemap
          icon_pack: fas
        - name: Back-end
          icon: laptop
          icon_pack: fas
        - name: DB
          icon: database
          icon_pack: fas


  - block: features
    content:
      title: <span style="font-size:70%">My goals </span>

        
  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">front-end developer</span>
        content: <span style="font-size:70%"> Developers working on business logic configurations and UIs imported from the backend API </span>
        align: center
        background:
          image:
            filename: frontend.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">back-end developer</span>
        content: <span style="font-size:70%">Developers who process and store and manage user behavior<span style="font-size:70%">
        align: center
        background:
          image:
            filename: backend.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">mobile developer</span>
        content: <span style="font-size:70%">Development of smartphone applications<span style="font-size:70%">
        align: center
        background:
          image:
            filename: mobile.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      loop: true
      interval: 3000

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">My hobby</span>
      items:
        - name: Listening to music
          icon: music
          icon_pack: fas
        - name: watching movies
          icon: video
          icon_pack: fas
        - name: traveling
          icon: map
          icon_pack: fas




  - block: collection
    content:
      id: section-1
      title: interest
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
      id: section-2
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
  
  - block: collection
    content:
      id: section-3
      title: project
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - project1
          - project2
          - project3
    design:
      view: community/custom_card
      columns: '3'

keywords: ["전북대 김찬우"]
---
