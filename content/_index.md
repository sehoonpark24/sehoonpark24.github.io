---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      text: |
        <span class="custom-title" style="color: white; font-size: 48px; font-weight: bold;"> Welcome to</br>Gender Politics Research Group </span>
    design:
      columns: '1'
      background:
        image: 
          filename: meeting.JPG
          filters:
            brightness: 1
          parallax: false
          position: center
          #size: cover
          text_color_light: true
      spacing:
        padding: ['100px', '0', '150px', '0']
      css_class: text-white text-left

  - block: markdown
    content:
      text: |
        <span style="color: black;font-weight: bold;">젠더정치연구회</span>는 한국 사회에서 점점 심화되고 있는 젠더 갈등을 정치학적 관점에서 분석하고, 이를 해결하기 위한 제도적·정책적 대안을 모색하는 연구 모임입니다. 젠더 갈등은 단순한 사회적 이슈를 넘어 정당정치, 선거, 입법 과정에서 중요한 정치적 균열로 작용하며, 정책 결정과 공공 여론 형성에도 큰 영향을 미치고 있습니다. 최근 미투 운동, 디지털 성범죄 근절 시위, 그리고 정치적 논쟁을 거치면서 젠더 이슈는 사회적 차원을 넘어 정치적 쟁점으로 확대되었습니다. 그러나 이에 대한 체계적인 정치학적 연구와 해결 방안 마련은 아직 미흡한 실정입니다. 젠더정치연구회는 이러한 문제의식을 바탕으로 젠더 갈등이 정치 과정에 미치는 영향을 규명하고, 이를 해결할 수 있는 제도적 접근을 탐색하는 것을 목표로 합니다. </br></br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;본 연구회는 “선호”, “과정”, “제도와 정책”이라는 세 가지 핵심 연구 영역을 중심으로 활동합니다. 개인의 젠더 인식과 태도를 분석하고, 성인지 감수성 지수를 개발하여 사회적 태도의 변화를 측정하는 것은 물론, 선거 및 입법 과정에서 나타나는 여성 대표성의 변화를 연구합니다. 또한, 성평등 증진을 위한 제도적 개혁 방안을 모색하고, 국내외 사례를 비교 연구하여 효과적인 정책 대안을 제시합니다. 이를 통해 젠더 갈등을 보다 과학적으로 이해하고, 사회적 공론화를 촉진하며, 실질적인 변화를 이끌어내고자 합니다. </br></br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;젠더정치연구회는 연구 논문을 작성하고 투고하는 것과 더불어, 다양한 학술 행사와 정책 제안을 통해 사회적 영향력을 확대해 나가려고 합니다. 연구회에서 개발한 성인지 감수성 지수, 젠더 다양성 지수, 실질 대표성 지수 등을 기반으로 젠더 관련 데이터를 구축하고, 이를 바탕으로 젠더 갈등의 정치적 영향을 분석하는 연구를 지속적으로 수행하고 있습니다. 또한, 정기적인 워크숍과 세미나를 통해 연구 성과를 공유하고, 후속 연구자들을 양성하여, 학계와 정책 결정자들이 젠더 문제에 대해 보다 심층적이고 지속적으로 논의할 수 있는 장을 마련하는 것을 목표로 합니다.
    design:
      columns: '1'
  
  - block: people
    content:
      title: 연구진
      user_groups:
          - 공동연구원
      sort_by: Params.custom_number
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_organizations: true
      show_social: false

  - block: collection
    content:
      title: 강연시리즈
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: lecture
    design:
      view: grid
      columns: '1'
  
  - block: collection
    content:
      title: 교육
      text: ""
      count: 5
      filters:
        folders:
          - education
    design:
      view: grid
      columns: '1'

  - block: collection
    content:
      title: 연구성과
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'

 # - block: markdown
 #   content:
 #     title:
 #     subtitle:
 #     text: |
 #       {{% cta cta_link="./people/" cta_text="구성원 더보기 →" %}}
 #  design:
 #     columns: '1'
---

