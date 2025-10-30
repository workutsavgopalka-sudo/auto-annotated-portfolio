---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/generated-image (6).png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 60
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'Hi, I am Utsav Gopalka'
    subtitle: >-
      I am a Mechatronics engineer with 3+ years of experience in CAD, GD&T, and
      PLC programming, specializing in designing and coordinating the
      development of machinery and workstations with advanced mechatronic
      systems. Having driven impactful engineering projects at Bosch, I am now
      expanding my expertise in strategy and management as an MSc candidate at
      the University of Bristol. I am drawn to consulting because it offers a
      unique opportunity to combine my technical background with strategic
      problem-solving—allowing me to influence how engineering innovations shape
      business success, create value across industries, and help organizations
      navigate complex, high-impact decisions at the intersection of technology,
      finance, and operations
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions:
      - type: Button
        label: About me!
        altText: ''
        url: /info
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Button
        label: My Blogs
        altText: ''
        url: /blog
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Button
        label: My CV
        altText: ''
        url: >-
          https://drive.google.com/file/d/1Yil6TaTVkuwTf-G-5lBYU3asAnOc7xx8/view?usp=sharing
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-one.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-two.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-five.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-0
          - pl-4
          - pr-4
        textAlign: left
---
