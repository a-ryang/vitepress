---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "vitepress-example"
  text: "A VitePress Site"
  tagline: My great project tagline
  actions:
    - theme: brand
      text: Markdown Examples
      link: /markdown-examples
    - theme: alt
      text: API Examples
      link: /api-examples

features:
  - title: Feature A
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
  - title: Feature B
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
  - title: Feature C
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
---

<style>
  :root {
  --vp-home-hero-name-color: transparent;
  --vp-home-hero-name-background: -webkit-linear-gradient(60deg, #8CBA35 40%, #FFB400);
  --vp-home-hero-image-background-image: linear-gradient(-45deg, #8CBA35 50%, #FFB400 50%);
  --vp-home-hero-image-filter: blur(44px)
  }
</style>
