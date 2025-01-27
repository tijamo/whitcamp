---
type: PageLayout
title: Pricing
sections:
  - type: PricingSection
    title:
      type: TitleBlock
      text: 2025 Prices
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: This is the subtitle for the pricing section
    plans:
      - type: PricingPlan
        title: ''
        price: Early Bird
        details: Pre April 28th 2025
        description: >-
          Sed ut perspiciatis unde omnis, iste natus error sit voluptatem
          accusantium doloremque.
        features:
          - Adults (18+) - £81 Weekend / £27 Day
          - Concession - £69 Weekend / £23 Day
          - Students - £60 Weekend / £20 Day
          - Children (5-13) - £51 Weekend / £17 Day
          - Under 5's - Free
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Pricing plan 1
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
      - type: PricingPlan
        title: ''
        price: Regular
        details: After April 28th 2025
        description: >-
          Sed ut perspiciatis unde omnis, iste natus error sit voluptatem
          accusantium doloremque.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Pricing plan 2
        actions:
          - type: Button
            label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
slug: Pricing
seo:
  type: Seo
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  metaTags: []
---
