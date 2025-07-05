---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >+
      # Our Mission

      Black Tech Poland aims to connect and empower Black tech professionals across Poland. Our goal is to build a thriving community where members can support each other, share knowledge, and create pathways for career growth. We're also committed to increasing the visibility of Black tech talent in the Polish tech ecosystem and helping members navigate integration into the country, both professionally and socially.

    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Black Tech Poland community
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        textAlign: left
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: 'Our Community Partners:'
    images:
      - type: ImageBlock
        url: /images/logo1.svg
        altText: Tech company logo
        caption: Tech company logo
      - type: ImageBlock
        url: /images/logo2.svg
        altText: Startup logo
        caption: Startup logo
      - type: ImageBlock
        url: /images/logo3.svg
        altText: University logo
        caption: University logo
      - type: ImageBlock
        url: /images/logo4.svg
        altText: NGO logo
        caption: NGO logo
      - type: ImageBlock
        url: /images/logo5.svg
        altText: Community logo
        caption: Community logo
    spacing: 3
    columns: 5
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    subtitle: 'Connect with us:'
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn Group
            url: 'https://www.linkedin.com/groups/10152720/'
        styles:
          self:
            textAlign: left
    columns: 1
    spacingX: 120
    spacingY: 16
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Who we welcome:'
    items:
      - type: Label
        label: 'Black Tech Professionals'
      - type: Label
        label: 'Job Seekers'
      - type: Label
        label: 'Students'
      - type: Label
        label: 'Allies'
      - type: Label
        label: 'Developers'
      - type: Label
        label: 'Designers'
      - type: Label
        label: 'Data Analysts'
      - type: Label
        label: 'DevOps Engineers'
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [info@blacktechpoland.org](mailto:info@blacktechpoland.org)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Our Events:'
        text: |-
          **Workshops**
          * Hands-on technical workshops
          * Career development sessions
          * Skill-building workshops

          **Tech Talks**
          * Industry expert presentations
          * Panel discussions
          * Knowledge sharing sessions

          **Networking**
          * Monthly meetups
          * Online community events
          * Professional networking

          **Mentorship**
          * Career guidance
          * Integration support
          * Professional development
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        subtitle: 'Our Goals:'
        text: |-
          **Community Building**
          * Connect Black tech professionals
          * Create supportive networks
          * Foster collaboration

          **Visibility**
          * Increase representation
          * Showcase Black talent
          * Promote diversity

          **Integration Support**
          * Navigate Polish tech ecosystem
          * Professional development
          * Social integration

          **Knowledge Sharing**
          * Technical expertise
          * Career insights
          * Industry knowledge
        styles:
          self:
            textAlign: left
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: CtaSection
    backgroundSize: full
    title: "Join our LinkedIn community! 💼"
    text: "Connect with fellow Black tech professionals in Poland and stay updated with our latest events and opportunities."
    colors: colors-f
    actions:
      - type: Button
        label: "Join LinkedIn Group 🚀"
        url: "https://www.linkedin.com/groups/10152720/"
        style: "primary"
        showIcon: true
        icon: "arrowRight"
        iconPosition: "right"
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        flexDirection: col
        textAlign: center
---
