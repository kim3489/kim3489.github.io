---
# Homepage
title:
type: landing

sections:

  - block: features
    content:
      title: <span style="font-size:70%">Kcw Web </span>
      text: <br><span style="font-size:125%">전북대학교 컴퓨터인공지능학부 2학년 김찬우의 홈페이지에 오신 것을 환영합니다.</span> <br><br>
        
  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">Back-end 개발, DB개발 </span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Interest</span>
        content: <span style="font-size:70%">football, baseball <span style="font-size:70%">
        align: center
        background:
          image:
            filename: football.jpg
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
      title: <span style="font-size:75%">My Interests</span>
      items:
        - name: Back-end
          icon: laptop
          icon_pack: fas
        - name: DB
          icon: database
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
---
