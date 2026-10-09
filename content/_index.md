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
        research themes of the <a href="https://www.wur.nl/en/chair-groups/section-economics/environmental-economics-and-natural-resources">**Environmental Economics and Natural Resources
        Group**</a> (ENR) at **Wageningen University & Research**.

        Across the globe, social-ecological systems such as marine environments, forests, semi-arid
        grazing lands and fisheries are under increasing pressure from climate change, overexploitation
        and other stressors. At the same time, there are notable success stories, where resources are
        managed sustainably or where conservation has led to ecosystem restoration. Understanding why
        some systems are sustainably managed while others are trapped in a state of overexploitation is
        at the heart of our work. Human behaviour and nature shape each other, and whether a system is
        used sustainably depends on the institutions that couple them: formal institutions such as
        protected areas and property regimes, and informal arrangements such as communal social norms.
        Ecological tipping points make these traps hard to escape: once a system has shifted into a
        degraded state, it may stay there. Yet social tipping points can also open windows of
        opportunity for institutional change, pushing a system towards recovery.

        Our research combines economic theory, empirical analysis and interdisciplinary collaboration to
        understand the complex dynamics of social-ecological systems, addressing questions such as:

        - Which institutions and policies enable sustainable resource use and ecosystem restoration?
        - What are the costs and benefits of alternative policy options and pathways, and who are the winners and losers?
        - How can we balance resilient ecosystems, livelihoods and income within a safe and just operating space?
        - When does better information, for example about the value of ecosystems, lead to better decisions?

        Curious about our work? Dive into our projects and publications, and please reach out to us.

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