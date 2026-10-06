# Rooftop Solar Yojana Portal

A single-page, light-theme **rooftop solar subsidy portal** template, modelled on the
layout and workflow of India's PM Surya Ghar portal. Built as a design reference —
**generic placeholder branding, not an official government portal.**

## Live preview

Open `rooftop-solar-portal/index.html` in a browser, or enable GitHub Pages and serve
from `/rooftop-solar-portal`.

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
- Everything is in one file: `rooftop-solar-portal/index.html`

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
