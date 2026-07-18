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
      title: Welcome!
      subtitle:
      text: |
        The **Economics of Social-Ecological Systems** (EconSES) is one of the four
        research themes of the **Environmental Economics and Natural Resource
        Group** (ENR) at **Wageningen University and Research**.

        We study how people, institutions, markets, and ecosystems interact to shape 
        the sustainable use of natural resources. Our research combines economic 
        theory, empirical analysis, and interdisciplinary collaboration to better 
        understand the complex dynamics of social-ecological systems.

        Our work addresses questions such as:
        - How can environmental policies promote both ecological sustainability and human well-being?
        - What economic incentives drive resource use and conservation?
        - How do institutions, governance, and collective action influence environmental outcomes?
        - How can societies balance competing objectives, such as food production, biodiversity conservation, climate resilience, and equitable development?

        By working across disciplines and with partners from academia, government, NGOs, and practice, we aim to generate knowledge that supports evidence-based decision-making and contributes to more resilient and sustainable social-ecological systems.

        Whether you are a researcher, student, policymaker, or practitioner, we invite you to explore our projects, publications, and opportunities for collaboration.

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