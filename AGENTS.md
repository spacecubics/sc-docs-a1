# Repository layout

This repository contains the SC-OBC Module A1 Product Manual.
Antora builds the manual from AsciiDoc.

`en/` contains English content. `ja/` contains Japanese content.
Both have `modules/` with:

- `ROOT/`: Product overview and module hardware
- `dev-board/`: Development board
- `software/`: Zephyr setup, samples, applications, and drivers
- `fpga/`: FPGA documentation

Within modules, `pages/` contains pages, `partials/` shared content,
and `assets/` images and downloads. `nav.adoc` defines navigation.
Each language has an `antora.yml` component descriptor.
`.github/workflows/` contains build and validation workflows.
