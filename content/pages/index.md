---
title: Home
layout: PageLayout
sections:
  - colors: colors-a
    elementId: ''
    title: Featured items section
    subtitle: Featured items section example subtitle
    items:
      - type: ItemBlock
        title: Item Title
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
      - type: ItemBlock
        title: Item Title
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
      - type: ItemBlock
        title: Item Title
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
    actions:
      - type: Button
        label: Apply Now
        url: '#'
        style: primary
      - type: Button
        label: Learn More
        url: '#'
        style: secondary
    columns: 3
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
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-4
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
        margin:
          - mt-0
          - mb-6
      actions:
        justifyContent: flex-start
    type: FeaturedItemsSection
  - colors: colors-a
    elementId: ''
    title: Gallery
    subtitle: Gallery subtitle
    images:
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-1.jpeg'
        altText: image alt text
        caption: image caption
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-2.jpeg'
        altText: image alt text
        caption: image caption
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-3.jpeg'
        altText: image alt text
        caption: image caption
      - type: ImageBlock
        url: 'https://assets.stackbit.com/components/images/default/image-4.jpeg'
        altText: image alt text
        caption: image caption
    spacing: 1
    columns: 2
    aspectRatio: '1:1'
    imageSizePx: 300
    showCaption: true
    enableHover: true
    styles:
      self:
        width: full
        height: auto
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-2
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-12
    type: MediaGallerySection
  - elementId: ''
    colors: colors-f
    title: Where did everyone go?
    text: >
      Learn how top tech companies have learned working remote using our
      product.
    actions:
      - type: Button
        label: Sign Up
        url: /
        style: secondary
      - type: Button
        label: Watch Video
        url: /
        style: link
        showIcon: true
        icon: arrowRight
    feature:
      type: ImageBlock
      url: /images/hero-3.jpg
      altText: Hero section image
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
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
        margin:
          - mb-6
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - colors: colors-h
    elementId: ''
    title: Remote doesn’t mean alone. Here are so great features
    subtitle: >-
      These are all excellent features that will provide exactly the things
      you’re looking for.
    items:
      - type: ItemBlock
        title: Faster
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/faster.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          title:
            textAlign: center
          text:
            textAlign: center
      - type: ItemBlock
        title: Smarter
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/smarter.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          title:
            textAlign: center
          text:
            textAlign: center
      - type: ItemBlock
        title: Focused
        text: >
          Learn how top tech companies have learned working remote using our
          product.
        featuredImage:
          url: /images/focused.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          title:
            textAlign: center
          text:
            textAlign: center
    columns: 3
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
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
        margin:
          - mb-6
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-start
    type: FeaturedItemsSection
  - elementId: ''
    colors: colors-a
    title: 'A great feature, we’re proud of'
    text: >
      Share WIP, comment on each other’s work, approve what’s ready to go, ship
      together
    feature:
      type: ImageBlock
      url: /images/hero-1.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-36
          - pb-6
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderColor: border-primary
        borderWidth: 0
        borderStyle: solid
      title:
        textAlign: left
        margin:
          - mb-6
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    colors: colors-a
    title: And a strong value proposition
    text: >
      Share WIP, comment on each other’s work, approve what’s ready to go, ship
      together
    feature:
      type: ImageBlock
      url: /images/hero-2.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-6
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
        margin:
          - mb-6
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    colors: colors-a
    text: >+
      ## “We sometimes write things. You should read it, it might shed some
      light on why we’re doing what we’re doing”

      [See all posts](/blog)

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
          - pt-22
          - pb-0
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: center
      text:
        textAlign: left
    type: TextSection
  - elementId: ''
    variant: variant-b
    colors: colors-a
    posts:
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
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
          - pt-12
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPostsSection
  - colors: colors-f
    elementId: ''
    title: Need Answers?
    items:
      - type: ItemBlock
        title: How it this different from what we have today?
        text: >
          At the office, working together is often a distruction, on remote, it
          could be motivation, At the office, working together is often a
          distruction, on remote, it could be motivation, At the office, working
          together is often a distruction, on remote, it could be motivation
        styles:
          title:
            textAlign: left
            margin:
              - mb-6
          text:
            textAlign: left
      - type: ItemBlock
        title: How it this different from what we have today?
        text: >
          At the office, working together is often a distruction, on remote, it
          could be motivation, At the office, working together is often a
          distruction, on remote, it could be motivation, At the office, working
          together is often a distruction, on remote, it could be motivation
        styles:
          title:
            textAlign: left
            margin:
              - mb-6
          text:
            textAlign: left
      - type: ItemBlock
        title: How it this different from what we have today?
        text: >
          At the office, working together is often a distruction, on remote, it
          could be motivation, At the office, working together is often a
          distruction, on remote, it could be motivation, At the office, working
          together is often a distruction, on remote, it could be motivation
        styles:
          title:
            textAlign: left
            margin:
              - mb-6
          text:
            textAlign: left
      - type: ItemBlock
        title: How it this different from what we have today?
        text: >
          At the office, working together is often a distruction, on remote, it
          could be motivation, At the office, working together is often a
          distruction, on remote, it could be motivation, At the office, working
          together is often a distruction, on remote, it could be motivation
        styles:
          title:
            textAlign: left
            margin:
              - mb-6
          text:
            textAlign: left
    columns: 2
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
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
        margin:
          - mb-6
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-start
    type: FeaturedItemsSection
  - elementId: ''
    colors: colors-a
    testimonials:
      - quote: >
          ## Such a great experience to be using this product. It really helped
          with what I needed help with.
        name: Carla Rogers
        title: Happy customer
        image:
          type: ImageBlock
          url: /images/carla.jpg
          altText: Photo of Isabelle Parks
        styles:
          self:
            margin:
              - mt-0
              - mb-0
            flexDirection: row-reverse
          quote:
            textAlign: left
          name:
            textAlign: left
          title:
            textAlign: left
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
    type: TestimonialsSection
  - type: ContactSection
    colors: colors-f
    title: Get early access
    text: >
      Sign up your team today to be the first to try out our new product to
      increae your team’s productivity
    form:
      type: FormBlock
      elementId: contact-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: email
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
      submitLabel: Sign Up
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-36
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      text:
        textAlign: left
---
