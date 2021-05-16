---
title: Launch That's Design System
subtitle: Creating a multi-brand design system
date: '2021-01-10'
thumb_image: /images/DS Feature Image.png
thumb_image_alt: 3 wireframes in different color themes
sections:
  - type: image_section
    image: /images/DS Feature Image.png
    image_alt: 3 wireframes in different color themes
    width: wide
  - type: text_section
    content: "When I mention Launch That, most people think - oh, another 'cool' agency. What most people don't know is Launch That owns the brands they create. They currently own 7 brands. So how do you create and maintain seven brands at once, consistently?\n\n### **Defining a Clear Process**\n\nBefore I started working as a Design System Lead, I worked as a developer & designer for 3 of the brands. The work process in the dev/design team unquestionably needed some improvement.\n\nDesigners used to create mockups without any guidelines. Every mockup was unique, and each designer would try to give a particular style to their creations.\n\n##### This process wasn't sustainable and brought two notable issues:\n\n1.  Design inconsistencies\n\n2.  Reinventing the wheel syndrome\n\nWe reached a point where some brand websites had more than thirty different shades of grey, and some icons would have more than five different variations. \U0001F92F Yikes!\n\nThese inconsistencies were a genuine concern, hurting the user experience. Still, it was hurting both designers and developers as they would spend a tremendous amount of time recreating the same components repeatedly.\n\nWhen we began our design system, Launch That had 4 brands, Asbestos.com, Drugwatch.com, Annuity.org, and DrugRehab.com. It wouldn't be surprising to see this number going up through the years. This is great for the business side, but as a small, scrappy team of designers and developers, how can we possibly keep up?\n\nThis work process or I should say lack of process, wasn't acceptable anymore, and it was time to create a proper design system.\n\nTo help us get started, we recruited [Brad Frost](https://bradfrost.com/), a leader in standardization and design systems. Brad was asked to come give a 2-day workshop to help our team better understand how we can implement design systems into our current plan for standardization.\_\n\nThe workshop was incredibly effective as it helped validate our efforts and plan for standardization, better understand the type of team structure we need to accomplish it.\n\n### **Foundations is Key**\n\nDesign Systems is a futuristic idea rooted in ancient tradition.\n\nAlexander's A Pattern Language is described as a practical architectural system; it's not an Ikea manual meant to provide the exact directions for building a room, building, or town. It's a simple guide filled with the proven elements any ordinary person could use to create a living world that best serves the humans that interact with it. Think Sims, but for the real world.\n\n> fundamental view of the world. It says that when you build a thing you cannot merely build that thing in isolation, but must also repair the world around it, and within it, so that the larger world at that one place becomes more coherent, and more whole; and the thing which you make takes its place in the web of nature, as you make it.\n>\n> \\- A Pattern Language\n\nDefining the foundations is the first step of the process, and just like a house, it is crucial to have solid foundations if you don't want the system to collapse later on.\_\n\nSo we started at the foundational problem, our makeshift tech stack.\_\n\nDevelopers worked closely with IT and Systems Administrators to help standardize our technical stack, servers, and development environments.\_\n\nWe rebuilt our servers and back-end from the ground up. This included building a brand new server environment and deployment system, a fresh WordPress install, and moving to Timber, a new templating engine that has significantly increased the time it takes to develop and manage WordPress templates.\_\n\nThese new standards were essential in helping improve security, reduce server downtime and technical debt and increase overall development efficiency.\_\n\n### **Components**\n\nAs soon as the tech stack is aligned, the work for Designers can start.\n\nOne of the goals of a Design System is to bring order by removing inconsistencies, so before creating anything, a good practice is to make a complete inventory of what already exists, what is missing, what is consistent, and what is not.\_\n\nAccording to Pattern Library (yes, I'm going to reference it again, I love this book!)\n\n> Each pattern describes a problem which occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice.\n>\n> \\- A Pattern Language\n\nPatterns range in scale, adapting their solutions to local circumstances and synthesizing those into larger designs ensures that all forces are balanced in a way that facilitates the emergence of quality without a name.\n\nWe can't start our audit with individual components - buttons, cards, tables, etc because it's not just about the interface.\n\nA successful audit starts with content and people to understand the patterns of what we are producing, what our users are consuming, and how that all balances with revenue goals.\_\n"
  - type: image_section
    image_alt: >-
      How to audit existing brands with users, editors, content and goals in
      mind. 
    width: regular
    image: /images/DS Process.png
  - type: text_section
    content: "I created an audit based on how the component is visually seen by the user and how the Editorial team creates the component in our custom page builder.\n\n#### Questions I asked: \n\n*   Does the editorial team use this component to communicate content?\_\n\n*   Is this component frequently used, or is it a one-off variant?\n\n*   Does this component help funnel the user to a goal?\n\n*   Does the Marketing team need to track this component for KPIs?\_\n\n*   If so, what are the jsclicks events, and are they aligned correctly?\_\n\n*   Are tracked events correctly routed to Salesforce, Mixpanel, and Google Analytics?\n\nI used a simple Figma file to place screenshots of every pattern combination of modifiers, variants, and layouts our page builder would allow me to.\_\n"
  - type: image_section
    image: /images/DS Page Builder Audit.png
    image_alt: Dropdowns showing variants in our custom WordPress page builder.
    width: wide
    caption: An audit of the many variants in our custom WordPress page builder.
  - image_alt: Comparing layouts to identify patterns.
    caption: "Comparing layouts to identify patterns. \U0001F645\U0001F3FD‍♀️ for the hideous layouts."
    width: wide
    type: image_section
    image: /images/DS Patterns Audit.png
  - image_alt: lorem-ipsum
    caption: lorem-ipsum
    width: wide
    type: image_section
    image: /images/DS Audit Comparison.png
  - type: text_section
    content: "This document quickly became essential as it gave me a holistic view of what was missing or not; when you have to deal with multiple brands, you need to keep things organized.\_\n\nNow that the inventory is done, building the Design System work can start.\n\nWe created a foundation boilerplate that could be duplicated and to be rebranded for each brand.\n\nHere is the boilerplate foundations of Launch That design system we call Ares:\n\n*   Color\n\n*   Type-scale\n\n*   Spacing\n\n*   System Fonts\n"
  - image_alt: lorem-ipsum
    width: wide
    type: image_section
    image: /images/DS Color Scale.png
  - image_alt: lorem-ipsum
    width: wide
    type: image_section
    image: /images/DS Type-scale.png
  - image_alt: lorem-ipsum
    width: wide
    type: image_section
    image: /images/DS Spacing and Icons.png
  - content: >
      Ares is the parent Design System that contains the main components. Each
      main component is a wireframe crafted with its non-negotiable atoms and
      molecules along with its responsive mobile counterpart. Also, I built it
      with Figma's auto layout feature.
    type: text_section
  - image_alt: lorem-ipsum
    caption: '2 components, a vertical and horizontal direction.'
    width: regular
    type: image_section
    image: /images/DS Action List Component.png
  - image_alt: lorem-ipsum
    caption: From 2 components I made 148 variants.
    width: wide
    type: image_section
    image: /images/DS Action List Variants.png
  - content: >
      Finally, I shared the Ares library, where it can be extended by all
      designers for the brands they work on.


      ### Templates


      With a complete set of components ready to be consumed, the next step is
      to build the templates and QA that everything works flawlessly.


      Building templates from scratch can be very long and tedious, but the
      beauty of using a Design System is that you don't need to recreate
      anything; all the components are already built. The power of auto-layout +
      variations allows the components to snap perfectly inside the template
      container: no more nudging or adjusting space. Designers can now spend
      more time testing & irritating layouts quickly.
    type: text_section
  - image_alt: lorem-ipsum
    caption: lorem-ipsum
    width: regular
    type: image_section
    image: /images/DS autolayout.gif
  - content: "## Documentation\n\nA design system needs to be open and accessible to everyone, so having a platform where each member of the company can read the guidelines and consume the system's content is highly important.\n\nI decided the best starting place for documentation would be in Figma since everyone at the organization has read access. In time, I would love to see our code documented alongside the components. When we get closer to that reality, I plan on moving our documentation from Figma to a more robust documentation platform like Zeroheight.\n\n## Outcomes\n\nThe Ares Design System will always be a work in progress. Since our time with Brad Frost in 2018, we have added 3 more brands to our portfolio, Consumernotice.org, MesotheliomaPrognosis.com, Retireguide.com.\_\n\nWe indeed had our moments of frustration with launching new brands with Ares. But with each time, we got better \U0001F4AA\U0001F3FD .\n\nRetireguide.com was our latest launch. It took us 3 months to build Retireguide's content, marketing strategy, design, and development from scratch. That process would have usually taken 6 months. Our design system decreased our time to launch by 50%.\n\n\_I'm passionate about design systems and could talk about multiple brand design systems for days. If you are interested and would like to know more about my work on Ares, do not hesitate to contact me.\n"
    type: text_section
seo:
  type: stackbit_page_meta
  title: Nature Magazine
  description: This is the sample project description
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Nature Magazine
      keyName: property
    - name: 'og:description'
      value: This is the sample project description
      keyName: property
    - name: 'og:image'
      value: images/work-magazine-1.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Nature Magazine
    - name: 'twitter:description'
      value: This is the sample project description
    - name: 'twitter:image'
      value: images/work-magazine-1.jpg
      relativeUrl: true
layout: project
---
