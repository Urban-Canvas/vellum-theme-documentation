---
layout: default
title: Vellum Theme Documentation
description: Installation, setup, customization, and support documentation for Vellum for Shopify.
---

# Vellum Theme Documentation

Vellum is a warm, editorial Shopify theme designed for independent bookshops, publishers, and literary brands. This guide covers installation, store setup, customization, product enrichment, and ongoing maintenance.

> **Theme version:** 1.0.1  
> **Platform:** Shopify Online Store 2.0  
> **Support:** [murungi.mutugi@gmail.com](mailto:murungi.mutugi@gmail.com)

## Contents

- [Before you begin](#before-you-begin)
- [Install Vellum](#install-vellum)
- [Quick-start setup](#quick-start-setup)
- [Theme settings](#theme-settings)
- [Header and navigation](#header-and-navigation)
- [Homepage sections](#homepage-sections)
- [Products and book formats](#products-and-book-formats)
- [Optional product metafields](#optional-product-metafields)
- [Collections, search, and filtering](#collections-search-and-filtering)
- [Pages, blog, and contact form](#pages-blog-and-contact-form)
- [Cart and checkout](#cart-and-checkout)
- [Languages and markets](#languages-and-markets)
- [Search engine optimization](#search-engine-optimization)
- [Accessibility and content guidance](#accessibility-and-content-guidance)
- [Demo catalogue](#demo-catalogue)
- [Troubleshooting](#troubleshooting)
- [Developer workflow](#developer-workflow)
- [Getting support](#getting-support)

## Before you begin

For the smoothest setup, prepare the following before installing the theme:

- Your logo, favicon, and social-sharing image.
- Product records with a title, author, description, price, cover image, and inventory status.
- Product variants for formats such as Paperback, Hardcover, and eBook.
- Collections for the genres or categories you plan to feature.
- Navigation menus for the header, mega menu, and footer.
- Your store policies, contact details, and social links in Shopify.

Vellum includes designed placeholders, so you can preview its layout before all store content is ready. Replace placeholders with real catalogue content before launch.

## Install Vellum

### Upload a theme ZIP

1. In Shopify admin, go to **Online Store → Themes**.
2. In the **Theme library**, select **Add theme → Upload zip file**.
3. Choose the Vellum theme ZIP and upload it.
4. When processing completes, select **Customize** to configure the unpublished theme.
5. Preview and test the theme before selecting **Publish**.

Keep an unmodified copy of the original theme package as a backup. Duplicate your live theme before applying an update or making code changes.

### Update from a newer package

Uploading a new theme package creates a separate theme and does not automatically transfer every customization. Compare settings and custom code before publishing the newer copy. Products, collections, pages, menus, files, and metafields remain in the store because they are Shopify content rather than theme files.

## Quick-start setup

Use this order to reach a launch-ready storefront efficiently:

1. Upload Vellum and open the theme editor.
2. Configure your logo, colors, typography, and preferred light/dark appearance.
3. Build the header navigation and footer links.
4. Create genre or category collections and assign products to them.
5. Connect homepage sections to products, collections, and your journal blog.
6. Configure product formats as variants and add optional book metafields.
7. Add store policies, a contact page, and blog content.
8. Test search, localization, product variants, cart updates, and checkout on desktop and mobile.
9. Review SEO titles, descriptions, image alternative text, and accessibility.
10. Duplicate the configured theme as a backup, then publish.

## Theme settings

Open **Online Store → Themes → Customize**, then select **Theme settings**.

### Logo and brand assets

| Setting | Recommended use |
|---|---|
| Logo | Upload a high-resolution image with transparent padding kept to a minimum. |
| Favicon | Use a simple square PNG or ICO that remains legible at a small size. |
| Social sharing image | Use a landscape image representing your shop for social link previews. |

If no logo is uploaded, Vellum displays the store name as text.

### Appearance

The **Color scheme** setting controls the storefront's overall appearance:

- **Light** always uses the light palette.
- **Dark** always uses the theme's dark presentation.
- **Auto** follows the visitor's operating-system preference.

After choosing **Auto**, test both system modes to make sure uploaded logos and product imagery retain sufficient contrast.

### Colors

Vellum uses six coordinated color roles throughout the storefront:

| Setting | Used for |
|---|---|
| Background | Main page background. |
| Text & headings | Primary copy, headings, and high-emphasis controls. |
| Muted text | Metadata and secondary copy. |
| Accent | Buttons, links, highlights, and emphasis. |
| Soft panel | Cards and softly contrasted editorial panels. |
| Deep panel | Stronger layered surfaces and borders. |

Check contrast after changing colors, particularly for accent-colored text, buttons, form borders, and muted copy.

### Typography

- **Heading font** controls the editorial display type used for prominent headings.
- **Label/UI font** controls navigation, metadata, buttons, and interface text.

Fonts are selected from Shopify's font library. Vellum also includes self-hosted serif and grotesk fallback fonts, ensuring the interface remains styled while selected fonts load.

## Header and navigation

Select the **Header** section in the theme editor. Header navigation is assembled with blocks, which may be reordered to suit your information architecture.

### Navigation block types

| Block | Purpose |
|---|---|
| Navigation link | Adds a direct link to a collection, page, blog, product, or external URL. |
| Dropdown menu | Connects a Shopify navigation menu beneath one top-level label. |
| Mega menu | Displays as many as three menu columns beneath one top-level label. |

For each menu block, enter a visible label and select the destination or Shopify menu. Translation-key fields are intended for stores maintaining theme translations; most merchants should use the visible label fields.

The header also provides storefront search, account access when customer accounts are enabled, localization selectors when applicable, and the cart drawer.

### Create a Shopify menu

1. In Shopify admin, go to **Content → Menus**.
2. Create a menu and add its links.
3. Return to the Vellum theme editor.
4. Add or open a dropdown or mega-menu block, then connect the menu.

Keep top-level labels short and avoid duplicating the same destination in several adjacent menu items.

## Homepage sections

Vellum's homepage is built from reorderable Online Store 2.0 sections. Open the homepage in the theme editor to add, remove, hide, or rearrange sections.

### Hero

The editorial hero supports an eyebrow, heading, accented heading text, body copy, two calls to action, and a featured collection. Connect a collection with strong cover imagery; Vellum uses its products to create the floating-book composition.

### Collection carousel

Use this section to introduce important genres or departments. Configure the eyebrow, heading, accented text, and description, then add a collection block for every card. Four to six clearly differentiated collections work well for most stores.

### Featured collection

Show between 2 and 12 products from one collection in a 3-, 4-, or 5-column layout. The section supports optional view-all navigation and several background treatments. It can be added more than once—for example, for **New releases** and **Classics**.

### Book of the Month

Select one product for a prominent editorial feature with direct purchase behavior. Choose a product that has a strong cover, complete description, available variant, and accurate price. The optional eyebrow can identify the feature as a monthly pick, staff selection, or award winner.

### Editorial quote

Add a short quotation, attribution, and optional eyebrow. Choose a color treatment that maintains strong text contrast. Confirm that you have permission to publish any third-party quotation.

### Genre tiles

This three-part feature combines two collection tiles with a journal promotion. Each collection tile supports an optional custom image and custom heading. The journal tile can connect to a Shopify blog or to a manually selected URL.

### Collection list

Add a flexible grid of collection blocks with an optional eyebrow and heading. This works well on landing pages that need more collection links than the homepage carousel.

### Newsletter

Configure the eyebrow, heading, and supporting text. Submissions use Shopify's customer form and are stored in Shopify admin. Make your marketing consent and privacy language appropriate for the countries where you operate.

## Products and book formats

Vellum uses standard Shopify product data wherever possible:

| Book information | Shopify field |
|---|---|
| Title | Product title |
| Author | Vendor |
| Synopsis | Product description |
| Cover/gallery | Product media |
| Genre | Product type, tag, and/or collection |
| Format | Variant title or option value |
| Retail price | Variant price |
| Original price | Compare-at price |
| Availability | Inventory and sales-channel availability |

### Configure formats as variants

1. Open a product in Shopify admin.
2. In **Variants**, add an option named **Format**.
3. Add values such as `Paperback`, `Hardcover`, and `eBook`.
4. Set the price, compare-at price, SKU, inventory, weight, and shipping behavior for each variant.
5. Add product media and save.

When a product has multiple variants, Vellum displays its format selector. Products with one variant display a single price and purchase action.

In the product template's **Product information** section, you can enable image zoom, show or hide the audio preview, and enter a fallback audio duration label.

## Optional product metafields

Vellum can enrich product pages with an audio sample, a review, and an author biography. Create these definitions in **Settings → Custom data → Products → Add definition**. Use the namespace and key shown below exactly.

| Name | Namespace and key | Recommended type | Purpose |
|---|---|---|---|
| Audio preview | `custom.audio_preview` | URL | Publicly accessible audio sample used by the product-page player. |
| Review quote | `custom.review_quote` | Multi-line text | Featured review excerpt. |
| Review source | `custom.review_source` | Single-line text | Publication or reviewer attribution. |
| Review badge | `custom.review_badge` | Single-line text | Short label such as “Editor's pick”. |
| Review rating | `custom.review_rating` | Integer | Star value; use a number from 1 to 5. |
| Author bio | `custom.author_bio` | Rich text or multi-line text | Author biography displayed below product information. |
| Author image | `custom.author_image` | File (image) or URL | Author portrait. |

Only populated fields are shown. Keep review excerpts concise, verify quotation rights, and use properly licensed author photography.

For the audio player, enable **Show audio preview** in the product template. Host audio over HTTPS and use a browser-compatible format such as MP3. The visible duration setting is a label; it does not edit the audio file.

## Collections, search, and filtering

### Collections

Create automated collections using product tags, product types, vendors, or other catalogue rules. Assign each collection a title, description, and image, then connect it to the appropriate Vellum section.

Collection pages include product cards, responsive layout, pagination, and Shopify-compatible filtering and sorting where configured. Manage storefront filters with Shopify's Search & Discovery app.

### Search

Vellum includes a search overlay, predictive product suggestions, and a full search-results page. Search quality depends on clear product titles, author/vendor data, descriptions, tags, and consistent identifiers.

After changing catalogue data, test searches for titles, authors, genres, and common customer terms.

## Pages, blog, and contact form

- **Standard page:** Use the default page template for About, Shipping, Returns, FAQs, and policy-supporting content.
- **Contact page:** Create a page and assign the `contact` theme template to display Shopify's contact form.
- **Blog:** Create a Shopify blog for journal entries, reading lists, interviews, and announcements.
- **Article:** Articles support editorial content, imagery, metadata, and sharing-friendly page metadata.

To assign a template, open the relevant page in Shopify admin and select it from the **Theme template** field.

## Cart and checkout

Vellum includes an AJAX cart drawer and a dedicated cart page. Customers can add products without a full-page refresh, change quantities, remove items, and proceed to Shopify Checkout.

Before launch, test:

- Available and sold-out variants.
- Quantity changes and item removal.
- Discount codes and automatic discounts.
- Shipping rates, taxes, duties, and pickup/delivery options.
- Accelerated payment methods and a complete test order.

Checkout branding and behavior are managed separately in Shopify admin and may depend on your Shopify plan.

## Languages and markets

Vellum includes English and German storefront translations and matching theme-editor translations. When more than one published language or country/region is available, the storefront can display localization controls.

Use **Settings → Languages** to add and publish languages, and **Settings → Markets** to configure countries, currencies, domains, and language availability. Review every translation before launch, including navigation labels, product content, policies, email notifications, and checkout text.

## Search engine optimization

Vellum provides technical foundations including canonical URLs, metadata output, Open Graph and social metadata, and JSON-LD structured data. Merchants remain responsible for content quality.

For every important resource:

- Write a unique, descriptive page title and meta description.
- Add meaningful alternative text to informative images.
- Use descriptive product and collection copy.
- Keep handles and internal links stable when possible.
- Configure the social-sharing image in theme settings.
- Submit the Shopify sitemap to the search engines you use.

SEO changes can take time to be recrawled and do not guarantee a particular ranking.

## Accessibility and content guidance

Vellum includes keyboard focus treatments, semantic landmarks, accessible disclosures, form labels, and a skip-to-content link. Preserve that foundation when adding content:

- Use descriptive link and button labels instead of “click here.”
- Provide alternative text that communicates the purpose of meaningful images.
- Leave decorative-image alternative text empty.
- Keep headings in a logical hierarchy.
- Do not place essential text only inside an image.
- Verify foreground/background contrast after brand-color changes.
- Add captions or transcripts for meaningful audio content.
- Test keyboard navigation, browser zoom, mobile layouts, and form errors.

## Demo catalogue

The project includes `demo/demo-products.csv`, an optional fictional catalogue of 21 books and 43 format variants. It includes public URLs for original, rights-cleared typographic cover artwork hosted with this documentation.

To use it:

1. In Shopify admin, go to **Products → Import**.
2. Upload `demo-products.csv` and import the products.
3. Create automated collections for the included genre tags: Classics, Contemporary, Science Fiction, Romance, Thriller, Biography, History, Philosophy, and Art & Design.
4. Confirm that Shopify imported the hosted cover images, or replace them with artwork you are licensed to distribute.
5. Connect the collections and a featured product in the theme editor.

Do not import demo content into a production catalogue without reviewing it first.

## Troubleshooting

### A homepage section shows placeholders

Open the section in the theme editor and connect the required product, collection, blog, or image. Also confirm that the resource is published to the **Online Store** sales channel.

### A product format cannot be selected

Confirm that the variant is available, has a price, and is published to the Online Store. Review inventory settings if Shopify is preventing out-of-stock purchases.

### The audio preview is not playing

Confirm that `custom.audio_preview` contains a public HTTPS URL, that **Show audio preview** is enabled in the product template, and that the file is a web-compatible audio format. Browser autoplay restrictions require the customer to start playback manually.

### A review or author biography is missing

Check the metafield namespace and key for exact spelling, confirm that the value is saved on the product, and make sure the metafield type matches the recommendations above.

### Navigation does not appear as expected

Verify that the selected menu contains links, then reconnect it to the relevant header block. Check that linked resources are published and available to the current market.

### Colors look incorrect in dark or automatic mode

Preview both light and dark system preferences. Uploaded raster logos do not change color automatically, so use artwork that remains visible on both appearances or choose a fixed scheme.

### Recent edits are not visible

Make sure you edited the intended theme and selected **Save**. Preview the theme in a private browser window to reduce the effect of cached assets and customer sessions.

## Developer workflow

Code customization is optional and should be performed on a duplicate theme. Vellum uses Liquid, JSON templates, JavaScript, and Tailwind CSS v4.

Prerequisites:

- Node.js and npm
- Shopify CLI
- Access to a Shopify development or merchant store

Install dependencies:

```bash
npm install
```

Watch Tailwind CSS while developing:

```bash
npm run tailwind:watch
```

Run the theme locally in a separate terminal:

```bash
shopify theme dev --store your-store.myshopify.com
```

Before release, compile minified CSS and run Shopify Theme Check:

```bash
npm run tailwind:build
shopify theme check
```

Push to a store only after confirming the target theme and store:

```bash
shopify theme push --store your-store.myshopify.com
```

Custom code can complicate future upgrades. Record every modification and test cart, search, localization, structured data, and responsive layouts after changes.

## Getting support

For help with Vellum, email [murungi.mutugi@gmail.com](mailto:murungi.mutugi@gmail.com) and include:

- Your store's `.myshopify.com` domain.
- The Vellum version shown at the top of this guide.
- A concise description of the expected and actual behavior.
- The affected page URL and steps to reproduce the issue.
- Screenshots or a short screen recording where useful.
- Whether custom code or a third-party app affects the page.

Never send passwords, full payment details, customer exports, or private API credentials by email. Shopify platform, billing, checkout, and account issues may need to be handled by Shopify Support.

---

© 2026 Urban Canvas. Vellum theme documentation.
