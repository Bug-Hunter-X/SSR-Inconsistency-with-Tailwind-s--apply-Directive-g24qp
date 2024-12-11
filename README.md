# SSR Inconsistency with Tailwind's @apply Directive

This repository demonstrates a bug where Tailwind CSS's `@apply` directive behaves inconsistently when used within components rendered server-side with frameworks like Next.js or Nuxt.js.

## Bug Description
When `@apply` is used within a component's template, the styles might not be applied correctly during server-side rendering, leading to inconsistencies between the initial server-rendered output and the fully rendered client-side version. This often manifests as missing or incorrect styles after the initial render.

## Steps to Reproduce
1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the development server (instructions vary depending on the framework used).
4. Observe the visual inconsistencies in the UI between the initial render and subsequent renders.