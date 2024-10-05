---
# Homepage
title:
type: landing

sections:
  - block: features
    content:
      title: <span style="font-size:70%">Kcw Web </span>
      text: <br><span style="font-size:125%">전북대학교 컴퓨터인공지능학부 2학년 김찬우의 홈페이지에 오신 것을 환영합니다.</span> <br><br>

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

      - title: <span style="font-size:70%">프론트엔드 개발자</span>
        content: <span style="font-size:70%"> 백엔드 API에서 가져온 비즈니스 로직 구성과 UI를 작업하는 개발자 </span>
        align: center
        background:
          image:
            filename: frontend.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">백엔드 개발자</span>
        content: <span style="font-size:70%">사용자의 행동을 처리하고 정보를 저장,관리하는 개발자<span style="font-size:70%">
        align: center
        background:
          image:
            filename: backend.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">모바일 개발자</span>
        content: <span style="font-size:70%">스마트폰 어플리케이션 개발<span style="font-size:70%">
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
        - name: 음악 듣기
          icon: music
          icon_pack: fas
        - name: 영화 시청
          icon: video
          icon_pack: fas
        - name: 여행
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
      title: project
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - gameproject
          - backendproject
    design:
      view: community/card
      columns: '2'
    advanced:
      css_style: "text-align: center;"
  
  - block: collection
    content:
      id: section-3
      title: teaching
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - teaching
    design:
      view: article-grid
      columns: '3'

keywords: ["전북대 김찬우"]
---
