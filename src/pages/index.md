---
title: Home
sections:
  - section_id: hero
    type: section_hero
    title: YCabal
    subtitle: |
      #### Monopolizing transaction flow for arbitrage batching via MEV
    image: images/ycabal.png
    image_alt: Author avatar
  - title: Text
    section_id: intro
    type: section_content
    content: "This is a strategy that realizes a profit by smart transaction batching for the purposes of arbitrage by controlling transaction ordering.\n\n\nRight now every user sends a transaction directly to the network mempool and thus gives away the arbitrage, front-running, back-running opportunities to miners(or random bots).\n\n**YCabal creates a virtualized mempool (i.e. a MEV-relay network) that aggregates transactions (batching), such transactions include:**\n\nPotential benefits including offering zero-cost trading fees (meaning profits from arbitrage are used to pay for user’s transactions). Additional benefits and potential applications are further discussed in this proposal.\n\nImportant: Note that there are\_*two*\_different uses of the concept of\_**batching**. For our purposes we use\_**batching**\_to denote the aggregation of transactions. Typically batching refers to the process of both aggregation of transactions for the purpose of reduced transactional cost.\n\n#### Forward Notes\n\n*   Multiple systems are at play, but at the most basic is the RPC permissioned network.\n\n*   Both on-chain contracts for arbitrage and off-chain infrastructure for calculating arbitrage are used to varying degrees\n\n*   Further development of a\_*interprotocol clearing and call market*\_are touched upon in this document. The initial release candidate of YCabal only concerns itself with the on-chain and off-chain components required to realize arbitrage profits.\n"
  - title: Recent Posts
    section_id: posts
    type: section_posts
    has_more_link: true
    more_link_text: Read more
  - title: A Cat
    section_id: cat
    type: section_content
    image_alt: Geometric pattern
    content: >-
      Hi this is my text and image block. Vis accumsan feugiat adipiscing nisl
      amet adipiscing accumsan blandit accumsan sapien blandit ac amet faucibus
      aliquet placerat commodo. 

      Interdum ante aliquet commodo accumsan vis phasellus adipiscing. Ornare a
      in lacinia. Vestibulum accumsan ac metus massa tempor. Accumsan in lacinia
      ornare massa amet. Ac interdum ac non praesent. Cubilia lacinia interdum
      massa faucibus blandit nullam. Accumsan phasellus nunc integer. Accumsan
      euismod nunc adipiscing lacinia erat ut sit. Arcu amet. 

      Id massa aliquet arcu accumsan lorem amet accumsan.


      Interdum ante aliquet commodo accumsan vis phasellus adipiscing. Ornare a
      in lacinia. Vestibulum accumsan ac metus massa tempor. Accumsan in lacinia
      ornare massa amet. Ac interdum ac non praesent. Cubilia lacinia interdum
      massa faucibus blandit nullam. Accumsan phasellus nunc integer. Accumsan
      euismod nunc adipiscing lacinia erat ut sit. Arcu amet.
seo:
  title: Stackbit Vanilla Theme
  description: The preview of the Vanilla theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Vanilla Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Vanilla theme
      keyName: property
    - name: 'og:image'
      value: images/vanilla-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Vanilla Theme
    - name: 'twitter:description'
      value: The preview of the Vanilla theme
    - name: 'twitter:image'
      value: images/vanilla-preview.png
      relativeUrl: true
template: advanced
---
