---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # Full-width image section
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <div class="welcome-image">
          <img src="/media/welcome.jpg"
               alt="Economics of Social-Ecological Systems">
        </div>
    design:
      columns: '1'
      css_class: welcome-image-section
      spacing:
        padding: ["0", "0", "0", "0"]

  # Introduction text section
  - block: markdown
    content:
      title: Economics of Social-Ecological Systems
      subtitle:
      text: |
        The **Economics of Social-Ecological Systems** is one of the four
        research themes of the **Environmental Economics and Natural Resource
        Group** at **Wageningen University and Research**.

        At the **Economics of Social-Ecological Systems Lab**, we investigate
        the economic drivers of social-ecological systems. Our research examines
        how policies, institutions, and trade-offs influence sustainable
        resource management, ecosystem resilience, and socio-economic outcomes.
    design:
      columns: '1'
      css_class: welcome-description

  - block: portfolio
    content:
      title: Research Domains
      filters:
        folders:
          - themes

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---