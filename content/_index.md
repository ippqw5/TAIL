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
---
吳恩達 is a professor of artificial intelligence at the Stanford AI Lab. His research interests include distributed robotics, mobile computing and programmable matter. He leads the Robotic Neurobiology group, which develops self-reconfiguring robots, systems of self-organizing robots, and mobile sensor networks.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.
