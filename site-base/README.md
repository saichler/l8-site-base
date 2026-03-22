# site-base

Shared base assets and templates for Layer 8 ecosystem marketing and documentation sites.

## Contents

- `css/style.css`: global tokens, layout, nav, hero, buttons, and reveal rules
- `css/sections.css`: aggregator for reusable section styles
- `css/sections-navigation.css`: navigation cards, statement cards, problem lists, decay timeline
- `css/sections-structure.css`: rules grid, pipeline, compare layouts, and structural content sections
- `css/sections-architecture.css`: architecture diagram, founders, CTA, and footer styles
- `css/components.css`: reusable component catalog card system
- `css/detail.css`: shared component detail page content styles
- `css/illustrations.css`: reusable hero and section illustration animations
- `js/nav.js`: mobile nav toggle behavior
- `js/reveal.js`: intersection-based reveal behavior
- `images/`: shared Layer 8 brand and founder images
- `templates/company.html`: base shell for company/about pages
- `templates/component-detail.html`: base shell for component detail pages

## Intent

This project is for shared website infrastructure, not app UI. It should stay separate from `l8ui`, which is the Layer 8 application UI library.

## Integration

Projects should consume this repository as a git submodule or copied base during site setup, then provide project-specific:

- page content
- navigation data
- component catalog data
- product-specific links and copy
