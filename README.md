# FUJI Group — Fujihk Platform

**Engineering storefront, customer mobile app and FUJI ADMIN**

**Public website · Two unpublished mobile apps · Private application source**

[Live storefront](https://fujihk.net/) · [Portfolio case study](https://mohamedabderrehmane.netlify.app/projects/fujihk/) · [العربية](README.ar.md)

![FUJI Group public storefront](docs/images/00-home.jpg)

FUJI is a connected product and operations platform: a public engineering catalogue, a customer shopping and services app, a staff administration app, and a private web super-admin panel. The mobile apps use Expo, React Native and TypeScript and share the platform API.

## The two mobile apps

### FUJI customer app

The customer app brings product search and discovery, product details, wishlist, cart, checkout and order history into a mobile workflow. It also connects customers with company and projects information, quotation requests, inspection checklists, logistics tracking, manuals, events and support.

### FUJI ADMIN

The separate staff app provides a permission-aware dashboard for selected operations: product editing and bulk entry, image upload, brand/category management, customer controls, shipments, manuals, expo schedule, settings and scoped sub-admin access. Available modules depend on the signed-in administrator’s configured permissions.

> Neither mobile app has been published on Google Play or the Apple App Store. This is a project showcase, not a store listing or app download.

## Web and mobile architecture

- Public storefront: catalogue discovery, product details, cart and customer entry points.
- FUJI customer app: Expo/React Native client for shopping and customer services.
- FUJI ADMIN: separate Expo/React Native client for staff operations.
- Private web administration: broader super-admin workflows.
- Shared API and business records connect the applications.

See the [architecture diagram](docs/architecture.svg), [mobile-app case study](docs/mobile-apps.md), [gallery](docs/gallery.md) and [full case study](docs/case-study.md). The source code and internal administration are private. The gallery distinguishes live website captures from source-based mobile interface preview artwork.

## Public website gallery

- [Home](docs/images/00-home.jpg)
- [Catalogue](docs/images/catalogue.jpg)
- [Product detail](docs/images/product-detail.jpg)

## Mobile app interface previews

The following images are labeled concept artwork based on the app layouts and workflows reviewed in the private source. They use synthetic demonstration data and are **not screenshots from a running app build**.

![FUJI customer app home interface preview](docs/images/customer-app-home.jpg)

![FUJI customer app product detail interface preview](docs/images/customer-app-product.jpg)

![FUJI ADMIN dashboard interface preview](docs/images/fuji-admin-dashboard.jpg)

![FUJI ADMIN product management interface preview](docs/images/fuji-admin-products.jpg)

## Status and scope

The public website is available at [fujihk.net](https://fujihk.net/). Both mobile apps are showcase-only at this time and do not have public installation links. Website images show the public storefront; mobile images are clearly labeled source-based preview artwork. Private customer, staff, order and admin records are not included.

## License and attribution

This repository is a documentation-only case study under the included MIT license. FUJI Group names, marks and product imagery remain their respective owners’ property. See [third-party notices](THIRD_PARTY_NOTICES.md).
