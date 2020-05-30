# Chime - Umbraco Starter Kit

Chime is an opinionated Umbraco Starter Kit based on Tailwind CSS. It is intended to use as a starting point for new Umbraco projects that want to use Tailwind CSS.

## Technologies

- [Tailwind CSS](https://www.tailwindcss.com) via CDN
- [Alpine](https://github.com/alpinejs/alpine) via CDN

Note: to keep it as portable as possible I made the decision to include the CDN version of Tailwind CSS. This is not optimal as Tailwind CSS comes with many classes by default. The ideal situation would be to make your own buildproces when using Chime in production. You can read more about it [here](https://tailwindcss.com/docs/controlling-file-size) in the official documentation.

## Features

Chime ships with:

- Responsive first design
- Blog overview and detail pages
- Hero elements
- SEO optimization features
- Search functionality
- Settings page
- Best-practice Umbraco setup

### Modularity

Almost everything you see is modular. I've used partial templates to chop up pages to re-use components as much as possible. This makes it really easy for you to build your own custom pages with existing code.

## Roadmap

- [x] Blog overview and detail page
- [x] Basic search functionality
- [x] Basic content page
- [ ] Home page
- [ ] Contact page
- [ ] Proprietary social media meta tags
- [ ] Google Tag Manager integration
- [ ] Site map

### Considering

- [ ] Grid layout support
- [ ] Extend search functionality: multiple keywords
- [ ] GTM: Auto-tagging events via DataLayer

More to come, stay tuned!

## Other stuff Chime uses

- [HeroIcons](https://heroicons.dev/)

## What is the purpose of this repo?

This repository is for the development of the starter kit. You can not install Chime with this repository. This repository houses only the source files for the Chime project.
