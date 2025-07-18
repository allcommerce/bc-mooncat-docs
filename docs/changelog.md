# Release Notes

## 1.10.0 (07-18-2025)
- [CORNERSTONE] PAYPAL-5000 Quick pay buttons are seen on PDP before 'required' option selection (#683)
- [CORNERSTONE] Update to support multiple date fields and remove blank space (#684)
- Add login with email link feature.

## 1.9.1 (02-21-2025)
- Fix undefined share link in PDP (#679)

## 1.9.0 (01-20-2025)
- [CORNERSTONE] Add nonce to scripts in checkout and account pages [#2525](https://github.com/bigcommerce/cornerstone/pull/2525)
- [CORNERSTONE] Use fetch when updating variants in cart ([#2521](https://github.com/bigcommerce/cornerstone/pull/2521))

## 1.8.1 (11-08-2024)
- Fix browser crash when editing options in Bulk Order layout with products that have an empty file
- Fix undefined 'input-font-color' in add payment methods account page

## 1.8.0 (09-06-2024)
- Change Twitter icon to X #672 (#673)
- Update code from Kansha 1.4.0:
  - Delete all card--alternate
  - Fix spacing of wallet buttons & add to cart later button on PDP
  - Fix card button width on product 1-column layout on category page
  - Remove xlink attributes on svg
  - Tweak estimate form on cart page
  - Fix disabled carousel of image gallery on PDP overflow on mobile
  - Tweak card buttons when no qty
  - Fix incorrect price symbol displayed in product cards generated by GraphQL
  - [CORNERSTONE] feat(payment): ADYEN-729 updated initialization interface of the storefront-account-payments lib, added theme styles
  - Fix Frequently Bought Together overlap product image on Safari
  - Fix faceted filter price range not collapse by default
  - Limit shop by brands strictly on the left sidebar
  - Fix jstree color
  - Update Bulk Order layout support choosing product options
  - Fix main image not display on PDP when BC encode HTML incorrect
  - Update quick search to display results after typing 2 letters
  - Fix product schema snippet error when product has not description
  - [CORNERSTONE] replace twitter image
  - [CORNERSTONE] feat(checkout): CHECKOUT-7557 display fees on cart page
  - Add icon ACH
  - [CORNERSTONE] feat(payment): PAYPAL-2495 added ACH payment method section to My Account -> Payment Methods page
  - [CORNERSTONE] chore: DATA-11047 Bump stencil-utils version
  - [CORNERSTONE] feat(payment): PAYPAL-2039 added style configs to payment buttons
  - [CORNERSTONE] feat(payment): BOLT-576 Add Bolt SPB support to cornerstone
  - [CORNERSTONE] feat(payment): PAYPAL-2195 added classes for applepay button
  - [CORNERSTONE] refactor(payment): PAYPAL-2079 removed accelerated checkout integration from theme
  - Fix to prevent mega menu from overflowing right edge of page
  - Fix cart quantity input change not working
  - Fixed unavailable options' strikeout display during cart edit
  - Fix quick payment button process incorrect product when frequently bought together enabled
  - Fix mini popup not open again when adding to cart from product cards
  - Fix Add to Cart button display for out of stock products in the recently viewed products section
  - Fix homepage blank display when products by category are not visible for specific customers due to permission restrictions
  - Update @bigcommerce/stencil-utils 6.15.0
  - Fix queryData.hasOwnProperty is not a function in url-utils
  - [CORNERSTONE] fix(storefront): BCTHEME-1346 Gift certificate CSS properties are applied to page after previewing Gift certificate on storefront
  - [CORNERSTONE] fix(storefront): BCTHEME-1112 Translation Gap: Submit Return Request button
  - [CORNERSTONE] feat(payment): ADYEN-313 improved interface of payment widget
  - [CORNERSTONE] fix(storefront): BCTHEME-1184 form.serialize() ignores dropdown option elements that have the disabled attribute
  - [CORNERSTONE] fix(storefont): BCTHEME-34 refactor svg attributes
  - [CORNERSTONE] STRF-10366 Webpack 5
  - [CORNERSTONE] fix(storefront): BCTHEME-1198 Product panels with scrolling/arrows prevent contextual menu on mobile devices
  - [CORNERSTONE] fix(storefront)L: BCTHEME-1366 Customer order summary with both physical and digital items shows shipping as null
  - [CORNERSTONE] feat(storefront): STRF-10056 Remove all amp related templates
  - [CORNERSTONE] feat(storefront): STRF-10309 Refactor Cornerstone for show_cart_action behavior
  - [CORNERSTONE] DATA-10380 Add remote_api_scripts into cart preview template


## 1.7.4 (06-14-2024)
- Fix webfont cannot load Google font with multiple weights

## 1.7.3 (05-03-2024)
- Fix NaN of quantity box on product cards #661 (#662)
- Fix default image not showing in search result page for product don't have image thumbnail #664 (#665)
- Fix infinite loading not working when there are 2 filter values selected #669 (#670)
- Fix infinite loading: not working select the default sort again #671 (#672)

## 1.7.2 (03-29-2024)
- Fix widget layout not center
- Remove unused files
- Fix jstree color

## 1.7.1 (03-21-2024)
- Remove footer heading link on desktop #657 (#658)
- Fix sort not working at search result page when turn off faceted filter #659 (#660)

## 1.7.0 (02-02-2024)
- Add config to show/hide button Buy Now on PDP (PR-#640)
- Fix brand link on product card link to 404 page ISSUE-#641 (PR-#642)
- Fix styling of sale label on PDP ISSUE-#644 (PR-#646)
- Tweak sale badge and you save on PDP (PR-#647)
- Fix Buy Now button style broken on Baby style ISSUE-#648 (PR-#654)
- Change FBT display 1 item per row when left sidebar is enabled ISSUE-#649 (PR-#654)
- Fix product description background padding on Quick View ISSUE-#650 (PR-#654)
- Fix price alignment on purchase options popup on mobile ISSUE-#651 (PR-#655)

## 1.6.0 (11-10-2023)
- Update Product Page to enhance sale countdown, add buy now button (#638)

## 1.5.1 (10-20-2023)
- Fix duplicate web link in ask question #635 (#636)
- Update default theme settings: show card swatches, FBT = related, infinite product loading = button
- Update default config to display more products
- Change popular search keywords type from text to input

## 1.5.0 (09-22-2023)
- Fix preventing YouTube video iframe affecting browser history.
- Fix view cart on mini cart not working (#629)
- Fix product image gallery thumbnail cannot swipe to left
- Fix graphQL product error when viewing more than 50 products
- Fix unable to scroll to the last thumbnail on PDP
- Fix Footer logo cause Layout Shift and image size not properly set (#633)
- Fix: Move product thumbnail's slick dots down (#634)

## 1.4.2 (08-31-2023)
- Fix pre-order product should hide shipping countdown and in stock ready icon #623 (#624)
- Fix incorrect quantity adding to cart when typing (#627)

## 1.4.1 (08-11-2023)
- Fix logo displayed in footer contact us #617 (#618)
- Fix unavailable cross out. Fix spacing of Ask Question link #619 (#620)
- Fix spacing of subcategories in new/featured/bestselling homepage sections #620 (#622)

## 1.4.0 (08-04-2023)
- Fix price label, RRP price not display properly. Fix paypal button display on preview cart popup - #605 (#607)
- Add option to display SKU & brand on product card - #598 (#599)
- Add option to display custom field on product cards #611 (#612)
- Add option to display categories tab on new, bestselling products on homepage #613 (#614)
- Fix accessibility of display type radios on category pages #600 (#602)
- Fix long category name on products by category on homepage #603 (#609)
- Fix whapsapp link #608 (#610)
- Fix Wishlist still shows up when disabled in Settings #615 (#616)
- Fix edit cart item display incorrect message when product is unavailable / out of stock
- Fixed unavailable options' strikeout display during cart edit
- Fix cart quantity input change not working when apply unavailable options fix
- Hide out of stock if product cannot purchase and inventory is not track

## 1.3.0 (06-23-2023)
- Fix #586: Sale badge percent calculated from msrp price (#589)
- Fix #587 Cart page "you may also like" not consistent spacing (#590)
- Fix #588 Spacing of add to cart button in product card (#591)
- Fix #578 CLS issue of product options on product cards (#584)
- Fix #592 Cart buttons not show up on recently viewed products and similar products on cart page (#593)
- Fix sticky header hidden when open menu on mobile occasionally
- Add recently viewed products on the left sidebar when layout is left #575 (#585)
- Fix #594 dropdown menu not display using Enter key (#595)
- Fix bulk order category template to match theme style
- Correct recently viewed products tab name in my account page (#597)

## 1.2.0 (06-16-2023)
- Fix Choose Options open new window when Quick View is disabled
- Add theme option: Enable quick search (show_quick_search)
- Remove padding from the left column of the home carousel #571
- Add name & price to aria-label to product cards #567
- Fix #577 carousel top widget region overflow
- Fix #576 blog break layout on load
- Fix #579 New / Featured / Bestselling Tabs display incorrect column number
- Remove unused Newsletter section on homepage #569

## 1.1.2 (06-02-2023)
- Fix sub-categories at pbcst section (#565)

## 1.1.1 (06-02-2023)
- #560 Fix Cart button missing quantity (#561)
- Fix Cart image #562
- Fix title spacing #540 (#563)
- Fix layout break when container max width is empty

## 1.1.0 (05-12-2023)
- Fix #538: Also bought images overlap in quick view
- Fix #539: Layout shift on Flash Sale countdown on PDP
- Fix #540: Increase spacing below heading of products by category and the left sidebar
- Fix #546: Widgets do not display in quick view
- Fix missing product schema
- Fix rating not display on product card
- Fix #547:
  - Update main navigation full width.
  - Fix mega menu prevent adding widgets in page builder.
  - Fix third-level sub-category menu cannot hover.
  - Fix invalid HTML tag (span) of recently blog post section.
  - Fix menu open on mobile incorrect position when changing from desktop to mobile breakpoint.
  - Fix incorrect z-index of submenu.
- Fix #553: Products by Category - Empty widget region should be hidden in Preview mode in Page Builder
- Fix #556: Fix GraphQL syntax in Quick-View
- Fix #555: popup cart sale badge

## 1.0.1 (05-02-2023)
- Increase file size warning to 500KB

## 1.0.0 (04-17-2023)
