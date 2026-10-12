# FUJI mobile apps

This document covers the two private mobile applications associated with the FUJI platform. It describes implemented app flows from the project source; it does not distribute application code or credentials.

## FUJI — customer app

- Built with Expo SDK 54, React Native 0.81 and TypeScript.
- Account entry includes login, sign-up, password recovery and token-backed API sessions.
- Main navigation links home, shopping, activity, account and cart with stack destinations for product details, checkout, orders, company, projects and service flows.
- Product journey includes search, product details, wishlist, cart quantity controls, checkout and order summaries/history.
- Customer-service modules include company profile, projects and quote request, inspection checklist, shipment list/details, manuals, expo schedule and support.
- Theme, language and currency state are provided at the app level. Biometric-assisted sign-in is available on supported devices.

## FUJI ADMIN — staff app

- A separate Expo/React Native application with its own authentication provider and navigation.
- A module-aware dashboard leads to products, brands, categories, bulk entry, events, manuals, logistics, customers, sub-admins and settings.
- Product tools cover create/edit/delete, image upload, search/filter and batch creation.
- Staff tools include customer records, shipment create/edit/delete, logistics content, manual library and expo schedule.
- The app computes available modules from administrator role, page permissions and product/category scopes; sub-admin management is reserved for full administrators.

## Shared services

Both apps call the platform API for authenticated business operations. Image uploads use a multipart request. Customer and staff flows are backed by the same FUJI catalogue and operations system; the web administration remains the broader control surface.

## Store availability

Neither FUJI nor FUJI ADMIN has been published on Google Play or the Apple App Store. This repository does not provide installation files or source code. No app-store listing, download link, review status or release date is claimed.

## Interface preview artwork

The gallery includes four labeled concept previews: customer home, customer product detail, FUJI ADMIN dashboard and product management. They are drawn from the source-reviewed screen structure and design tokens with synthetic records. They are not screenshots from a running app build. No store listing or installation link is available.

If runtime captures are added later, capture a sanitized build with synthetic catalogue, customer and shipment data. Avoid account names, phone numbers, addresses, order references, credentials, device prompts and internal admin records. Keep runtime screenshots distinct from preview artwork in captions and the capture manifest.
