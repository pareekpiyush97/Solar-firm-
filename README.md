# Rooftop Solar Yojana Portal

A single-page, light-theme **rooftop solar subsidy portal** template, modelled on the
layout and workflow of India's PM Surya Ghar portal. Built as a design reference —
**generic placeholder branding, not an official government portal.**

## Live preview

Open `index.html` in a browser. With GitHub Pages enabled (deploy from this branch,
root folder), the portal is served at the site root:
`https://pareekpiyush97.github.io/Solar-firm-/`

A looping video background (`bg.mp4`) sits behind the page under a soft light veil.

## Features

- **Tricolor top bar** with social links and a demo banner
- **Header** with ministry block, sunburst logo and action buttons
- **Multi-role Login dropdown** — Administrator, Consumer, Discom, Vendor, Brand Owner,
  Agency, Government Building, Implementation Agency (ULA)
- **Dropdown navigation** — Home, What's New, Consumer, Vendor, Discom, Roof, Reports,
  Capacity Building, More
- **Map-dot hero** with headline, programme quote and attribution placeholder
- **Quick Process to Apply** — 4-step application rail
- **Get Started** — registration form (with OTP demo) + tabbed login (Consumer / DISCOM /
  Vendor / Admin)
- **Subsidy calculator** — ₹30,000/kW for the first 2 kW, ₹18,000 for the 3rd kW, capped
  at ₹78,000
- **Benefits, live counters, FAQ** and a government-style footer
- Fully **responsive**, keyboard-accessible, light theme

## Tech

- Plain **HTML + CSS + vanilla JavaScript** — no build step, no dependencies
- The page is a single file: `index.html` (plus `bg.mp4` for the background)

## Customise it

Replace the following placeholders for your own deployment:

- Logo, emblem and portal name in the header
- `[ Leader / Chairperson Name ]` and `[ Designation ]` in the hero, plus the photo
- Ministry / organisation text in the top bar and header
- State, DISCOM and vendor lists
- Colours via the CSS custom properties in `:root`

## Note

This is a front-end template only. Real authentication, role-based access, applications,
subsidy/DBT and DISCOM integrations require a backend (for example PocketBase, Supabase or
a custom API) — not included here.
