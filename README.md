# Vallore Shopify Theme

Upload the CONTENTS of this folder to your GitHub repository root: assets/, config/, layout/, locales/, sections/, snippets/, templates/.

Connect the repository through Shopify Online Store > Themes > Add theme > Connect from GitHub. Alternatively upload the supplied ZIP as a theme.

## Required store setup
- In Customize > Theme settings > Product setup, choose your actual Vallore product for the homepage.
- Create product variants for your 1-pouch, 2-pouch and 4-pouch bundles, with correct prices, inventory and shipping weights. Bundle inventory/fulfillment needs store or app configuration.
- Configure subscription selling plans with a subscription app; the theme reads real selling plans from Shopify. Check each plan's compatibility with each variant.
- The original visual purchase panels are preserved as presentation controls. The additional order form under the bundle offers is the actual Shopify purchase form; it displays live variants/prices and adds to cart. They are not synchronized. Connect/remove the presentation selectors before launching to avoid mismatched selections or prices.
- Existing reviews, stock counts, testing statements, medical claims, guarantee, contact details and shipping promises were retained from the prototype and must be verified before launch. Placeholder graphics and nonfunctional footer links remain.
- This is a custom starter theme, not a full Shopify Theme Store submission. Test in a development store: mobile layout, variant availability, selling-plan compatibility, cart, checkout, refunds and delivery cadence. No live Shopify account was available for runtime validation.

The standalone HTML is separate; this ZIP contains native Liquid/JSON theme structure. Upload folders at the repository ROOT, not inside another Vallore-Shopify-Theme folder.
