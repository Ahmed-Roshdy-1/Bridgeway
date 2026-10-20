# Bridgeway

Bridgeway is a responsive landing page for a payments platform, built with Vue 3, TypeScript, Vite, and Tailwind CSS.

## Run the project

Use Node.js and npm, then install dependencies and start the Vite development server:

```sh
npm install
npm run dev
```

Open the local URL printed by Vite. To create and serve a production build:

```sh
npm run build
npm run preview
```

## Project structure

```text
src/
  App.vue                  Composes the landing page sections
  main.ts                  Creates and mounts the Vue application
  style.css                Global styles and Tailwind setup
  assets/                  Images and fonts used by the page
  components/
    header/                Site header and navigation
    home/                  Hero and brand strip
    Benefits/              Benefits section, feature cards, and icons
    contact/                Contact call to action
    footer/                 Social links and decorative footer
    buttons/               Shared button component
  layouts/                 Shared page shell, including header and footer
```

The page is split into section-level Vue components so each part of the landing page can be developed and adjusted independently. `DefaultLayout.vue` owns the shared page frame, while `App.vue` composes the page sections in their display order. Reusable elements such as feature cards and buttons live alongside their related components. Images and fonts are kept in `src/assets` and imported by the components that use them.

## Hardest part

The most challenging part was keeping the hero composition legible across screen sizes while preserving the artwork-led desktop layout. The implementation uses separate mobile and desktop hero imagery and Tailwind responsive utility classes to change positioning and visibility at larger breakpoints. This keeps the small-screen layout in normal document flow and allows the desktop artwork and text to overlap intentionally.

## What I would improve with more time

- Add automated component and browser tests, including checks at mobile and desktop viewport sizes.
- Complete an accessibility review for keyboard navigation, focus states, and decorative or interactive elements.
- Connect the call-to-action and social links to their real destinations; the current social links are placeholders.
- Review image loading and responsive image sizes to reduce the amount of media downloaded on smaller screens.

## Design differences

There are no intentional content or visual deviations from the supplied design. The layout does adapt responsively for smaller screens, where the desktop composition is rearranged into a vertical flow and the alternate hero image is used.
