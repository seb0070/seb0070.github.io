---
# Homepage configuration
title: ""
type: landing

sections:
  # Intro section
  - block: features
    content:
      title: ""
      text: "<br><span style='font-size:130%'>안녕하세요 👋 <b>UX와 성능에 집중하는 프론트엔드 개발자 정세빈</b>입니다.</span>"

  # Slider section
  - block: slider
    content:
      slides:
        - title: "<span style='font-size:100%'>사용자 경험과 성능에 집중하는 프론트엔드 개발자</span>"
          content: ""
          align: center
          background:
            image:
              filename: "https://images.unsplash.com/photo-1669023414162-5bb06bbff0ec?auto=format&fit=crop&q=80&w=1932"
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: "<span style='font-size:100%'>빠르고 반응형이며 접근성 높은 웹 서비스를 만듭니다</span>"
          content: ""
          align: center
          background:
            image:
              filename: "https://images.unsplash.com/photo-1607706189992-eae578626c86?auto=format&fit=crop&q=80&w=2070"
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: "<span style='font-size:100%'>사용자의 요구를 의미 있는 인터페이스로 구현합니다</span>"
          content: ""
          align: center
          background:
            image:
              filename: "https://images.unsplash.com/photo-1522542550221-31fd19575a2d?auto=format&fit=crop&q=60&w=1000"
              filters:
                brightness: 0.4
            position: center
            color: "#000"

    design:
      # Slide height (in viewport height units)
      slide_height: "65vh"
      # Set to true for fullscreen slider
      is_fullscreen: false
      # Enable automatic looping
      loop: true
      # Transition interval (milliseconds)
      interval: 4000
---
