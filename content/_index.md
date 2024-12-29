---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        젠더정치연구회
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        성평등 증진과 여성대표성 향상에 대한 국제적, 국내적 관심의 증가에도 불구하고, 이에 대한 국내의 학문적 논의는 아직까지 미흡한 실정이다. 젠더에 관한 사회과학 인접 학문의 논의가 없었던 것은 아니지만, 정치적 대표성에 대한 기존 연구들은 다소 제한적이다. 최근 한국사회에서 젠더갈등이 주요한 사회적 갈등으로 부각되었다는 점을 감안하면, 젠더갈등과 여성대표성에 관한 문제들을 학술적으로 분석하는 것이 반드시 필요하다. 이에 본 연구단은 ‘젠더갈등의 미시적 기반’, ‘선거와 입법과정에서 나타나는 여성대표성’, ‘성평등 증진을 위한 제도와 정책의 효과’라는 세 개의 트랙으로 연구를 진행하는 동시에 각 트랙별로 중장기 연구를 위한 데이터를 구축하고자 한다.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
