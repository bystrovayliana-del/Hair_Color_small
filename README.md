# Hair Color Study — GitHub Pages demo

Standalone educational static snapshot of the Russian-language hair-coloring landing page.

Website: https://bystrovayliana-del.github.io/Hair_Color_small/

## Behavior

The form validates synthetic input only. It sends and stores no contact data, creates no orders, accepts no payments and grants no access. Telegram delivery and the online editor are not included.

This public repository contains only built website assets, not the private application source, server functions, credentials or Git history. Font licenses are included under `fonts/`. Existing illustrative images and draft copy remain educational material.

## Publication and updates

GitHub Pages serves the root of `main`; `.nojekyll` preserves the Astro `_astro` asset directory. Asset paths are prefixed with `/Hair_Color_small/`.

This is a separate snapshot, built from source revision `562d8188f7fcb3826f9e69df24309ab3e561679f`. Changes in the existing Vercel editor do not automatically update this repository. To refresh it, export a new secret-free static demo build with hosted test flags disabled, remove the editor distribution, prefix project-relative asset paths and commit the reviewed assets here. Never copy `.env` files or server credentials.
