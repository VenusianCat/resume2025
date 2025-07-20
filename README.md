# Resume 2025

This is a redo of my previous resume 2024, only flattened out to be plain HTML styled with Tailwind, and a drop of vanilla JS. Thus Svelte was removed entirely, and the build process has been reduced to Tailwind compilation. What could be lighter than Svelte? No JS framework whatsoever.

The code is published at <https://richardtammar.com>

## Tailwind compilation

To have Tailwind compile the CSS, use the following command:

`npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch`
