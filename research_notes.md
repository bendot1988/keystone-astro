# Reference Research Notes

## GitHub repository: bendot1988/keystone-astro

- URL reviewed: https://github.com/bendot1988/keystone-astro
- Observed state on GitHub web interface: **the repository appears empty**.
- Resulting implication: the live website URL will be the primary source for structure, copy, imagery, and brand presentation unless the repository contents become available through another access path.

## Immediate next step

Inspect the live reference site in detail and extract visible branding, layout patterns, typography cues, section order, imagery, and calls to action for faithful recreation.

## Live reference site: keystone-renovations-352229086770.us-west1.run.app

### Observed page identity

- Browser title: **Keystone Renovations | Pre-Sale Renovations Focus**
- The page includes a version-switcher UI with **Version 1, Version 2, Version 3, Version 4** and Version 1 shown.
- Brand presentation uses a **Keystone Renovations** logo in the top-left and a strong dark hero section.

### Visible hero structure

- Header with logo, version buttons, and a **Get a Quote** CTA.
- Large uppercase hero headline: **MAXIMISE YOUR SALE PRICE WITH EXPERT PRE-SALE RENOVATIONS.**
- Supporting paragraph focused on Leicester homeowners and agents.
- Two primary hero CTAs: **View Our Projects** and **Get a Quote**.
- Three trust-stat blocks immediately below hero: **Specialist Focus**, **Rapid Delivery**, **Proven ROI**.

### Section order extracted from page text

1. Hero
2. Your Partner in a Successful Sale
3. High-Impact Updates for Modern Buyers
4. From Consultation to Completion (3-step process)
5. Why Sellers Trust Keystone
6. Project Gallery with before/after cases
7. Where We Work
8. Testimonials
9. Final contact / conversion section

### Service and locality emphasis

- Positioning is strongly focused on **pre-sale renovations** rather than general construction.
- Geographic emphasis: **Leicester**, **Oadby**, **Wigston**, **Loughborough**, **Hinckley**, **Market Harborough**, **Melton Mowbray**, **Coalville**, **Blaby**, **Lutterworth**.
- Contact items visible in page extraction: phone number, email address, and Instagram handle.

### Visual direction observed in first viewport

- Hero uses a **dark charcoal background** with white uppercase typography.
- Below the hero is a **warm taupe / stone feature strip** with icon-led value propositions.
- The overall tone is premium, architectural, and restrained rather than playful.

### Assets and font sources extracted from bundled files

- Google Fonts used by the live site:
  - **Montserrat** with weights 400, 600, 700, 800
  - **Open Sans** with weights 400, 500, 600, 700
- External logo source found in JavaScript bundle:
  - `https://storage.googleapis.com/shutquote/keystone-logo%20Large.png`
- External social link found in bundle:
  - `https://facebook.com/keystonerenovationsuk`
- Unsplash image sources found in bundle include kitchen, living room, exterior, and renovation imagery, indicating the live site relies on remote image URLs rather than local assets.

### Implementation implication

To reproduce the site faithfully, the replica should use the same font families and should either reuse or rehost the discovered remote logo and image assets through the project asset workflow.

### Mid-page visual observations

A viewport review lower on the page confirms that the site uses a very clean, centered editorial rhythm outside the hero. The section titled **Your Partner in a Successful Sale** sits on a bright white background with a large uppercase heading and narrow text measure centered beneath it. The following section, **High-Impact Updates for Modern Buyers**, introduces a pale off-white panel and a four-card service grid.

The service cards use thin warm-gray top borders, soft shadows or subtle separation, generous padding, and monochrome line icons. Heading typography remains bold, uppercase, and tightly tracked, while supporting body copy is lighter and more spacious. This reinforces that the site balances dark dramatic hero treatment with clean, trust-building informational sections below.

### Lower-page visual observations

Further down the page, the **From Consultation to Completion** section uses a minimalist three-step timeline. Each step number appears inside a slightly rotated square tile, creating a more bespoke editorial detail than a standard icon row. Beneath that, the **Why Sellers Trust Keystone** section switches back to a dark background with a split layout: trust-point text on the left and photography on the right. This alternating light-dark rhythm is an important structural characteristic of the site.

The observed composition suggests that later sections continue the same pattern of bold uppercase headings, narrow paragraph widths, and carefully framed imagery rather than dense interface chrome. The overall page is closer to a polished brochure site than a conventional contractor template.

### Extracted palette cues from the live CSS

The downloaded stylesheet indicates a restrained palette centered on **#1A1A1B** for the dark hero and dark trust sections, **#FAF9F6** for warm off-white backgrounds, **#F4F4F4** for lighter support surfaces, and **#A39682** for the taupe/stone accent used in value strips and decorative details. This confirms that the visual language is built around charcoal, warm white, and muted stone rather than high-saturation brand color.

## Local preview verification

The Astro reconstruction now renders successfully in the managed preview environment. The page structure, content hierarchy, dark-light section rhythm, logo usage, and core conversion points all match the reference site closely. The remaining differences are primarily visual nuance: the current hero background image is darker and more construction-led than the reference's interior-led treatment, and the recreated design is slightly more expansive in spacing than the source.

These observations indicate the implementation is functionally complete and suitable for final refinement and delivery, with only optional polish adjustments remaining.
