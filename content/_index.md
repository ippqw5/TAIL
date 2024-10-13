---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      image:
        filename: logo_tail.png
      cta:
        label: Meet Us
        url: people
      text: |

        TAIL（Trustworthy AI Lab）是一个致力于可信人工智能研究的实验室，来自华东师范大学滴水湖国际软件工程学院。我们的目标是开发安全、可靠、透明的AI系统。

        我们的研究方向包括：
        - 神经网络鲁棒性
        - 强化学习系统鲁棒性
        - 大模型测试

    # design:
    #   # Choose an optional background color, gradient, image, or video
    #   background:
    #     gradient_end: '#1976d2'
    #     gradient_start: '#004ba0'
    #     text_color_light: true

  - block: collection
    content:
      title: Latest News
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
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: disei.jpg
          filters:
            brightness: 1
          parallax: false
          position: right
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

---
