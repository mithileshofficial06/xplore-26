# XPLORE'26 Symposium Website

The website for **XPLORE'26**, a college technical symposium themed on the Spider-Verse. It opens with a dimensional-portal loading screen and moves into a layered 3D parallax hero with a rotating spider emblem.

![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?logo=threedotjs&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?logo=greensock&logoColor=black)

## Highlights

- **Portal loading screen** that hands off into the hero section
- **3D centrepiece:** a rotating spider emblem built with React Three Fiber
- **City parallax:** layered skyline that moves with scroll, driven by GSAP ScrollTrigger and Lenis smooth scrolling
- Comic-book styling with Bangers, Anton and Space Grotesk, plus clip-path and blend-mode effects

## Repository layout

```
spider-verse-symposium/   Next.js app (App Router, TypeScript, Tailwind CSS v4)
  src/components/         LoadingScreen, HeroSection, SpiderEmblem3D, CityParallax, ...
implementation_plan.md    Design and build plan
images/, Resourses/       Artwork and reference material
```

## Running it

```bash
cd spider-verse-symposium
npm install
npm run dev               # http://localhost:3000
```
