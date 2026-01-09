---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        南京理工大学 \
        智能媒体分析实验室
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **智能媒体分析实验室 Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2011.
  
  - block: people
    content:
      title: 
      user_groups:
        - Home
      sort_by: Params.index
      sort_ascending: true
      filters:
        folders:
          - people
    design:
      view: card
      columns: '3'
      show_interests: false
      show_role: true
      show_social: false

  - block: collection
    content:
      title: 
      subtitle: ''
      text: ''
      count: 5
      filters:
        # 核心修改：明确指定文件夹为 post
        folders:
          - post
        exclude_featured: false
    design:
      view: post_compact  # 推荐用 compact 或 card
      columns: '1'
    
  # - block: markdown
  #   content:
  #     text: |
  #       <div style="text-align:center; margin-top: 1rem;">
  #         <a href="/people/" class="btn btn-primary">更多...</a>
  #       </div>

  

  # - block: collection
  #   content:
  #     title: Recent Publications
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: publication
  #   design:
  #     view: citation
  #     columns: '2'

  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
