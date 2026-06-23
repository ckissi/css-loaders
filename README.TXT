==============================================================================
CSS LOADER LIBRARY
==============================================================================

A single-page library of 100 loading spinners built with pure CSS — no
JavaScript, no dependencies. Click any loader to view and copy its CSS.

Each snippet is self-contained, paints with a single --ink colour token, and
respects prefers-reduced-motion.

------------------------------------------------------------------------------
REQUIREMENTS
------------------------------------------------------------------------------

  - Node.js 18 or newer
  - npm (bundled with Node.js)

------------------------------------------------------------------------------
GETTING STARTED
------------------------------------------------------------------------------

  Install dependencies:

      npm install

  Start the dev server (http://localhost:4321):

      npm run dev

  Build the static site to ./dist:

      npm run build

  Preview the production build:

      npm run preview

------------------------------------------------------------------------------
PROJECT STRUCTURE
------------------------------------------------------------------------------

  src/
    pages/
      index.astro        Home page — the full loader grid + copy modal
    layouts/
      Layout.astro       HTML shell, fonts, global styles
    components/
      Loader.astro       Renders a single loader by type
    data/
      loaders.ts         The list of 100 loaders (name, type, index)
    utils/
      loaderCss.ts       CSS + required markup for each loader type
    styles/
      global.css         Site styles and design tokens

------------------------------------------------------------------------------
USAGE
------------------------------------------------------------------------------

  Open the site, click any loader in the grid, then press "Copy CSS" in the
  modal. Paste the snippet into your own project. The leading comment in each
  snippet shows the minimal HTML markup the loader needs.

------------------------------------------------------------------------------
TECH
------------------------------------------------------------------------------

  Astro 4 · Pure CSS · No runtime dependencies

------------------------------------------------------------------------------
LICENSE
------------------------------------------------------------------------------

  MIT

------------------------------------------------------------------------------
HOSTING
------------------------------------------------------------------------------

  Hosted on Sevalla: https://sevalla.com
