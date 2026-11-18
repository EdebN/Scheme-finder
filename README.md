# Scheme Finder

A small, static theme browser. Browse schemes, preview each one on a sample interface, and copy a portable JSON design specification.

## Use

Open `index.html` in a browser or publish the repository with GitHub Pages.

1. Browse or search the theme library.
2. Select a theme to update the live preview.
3. Press **Copy theme code**.
4. Paste the code into ChatGPT and ask it to apply the theme to your project.

The copied `SCHEME/1.0` object contains the palette, typography, shape, component guidance, and an explicit instruction to treat those values as the styling source of truth.

## Add a theme

Add another object to the `themes` array in `index.html`. Each theme has an `id`, `name`, `type`, `mood`, `desc`, and a `c` colour object. The code generator automatically includes it in the copied specification.

No build step or dependencies.
