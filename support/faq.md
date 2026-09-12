# Troubleshooting & FAQ

### My offer isn't showing on my storefront

1. Confirm the [App Embed](../app-overview/settings/theme-integration.md) is enabled on your **live, published** theme — embed status is per-theme, so a draft or unpublished theme won't reflect it.
2. Confirm the offer's status is **Active/Published**, not Draft.
3. Check any [targeting rules](../app-overview/targeting.md) or scheduling dates — an offer outside its active window, or one whose rules aren't currently met, won't render.
4. For Product page / Cart page offers, confirm you're viewing the actual placement the offer is configured for.

### I enabled the App Embed but the Dashboard still shows it as disabled

Return to the UpsellSuite tab after saving in the Theme Editor — the status updates automatically within moments of switching back to the tab. If it still hasn't updated after a few seconds, use the **Check again** action in Setup Status to force a refresh.

### Post-purchase offer isn't showing

- Confirm your store's checkout supports post-purchase extensions (see [Requirements](../getting-started/requirements.md)).
- Post-purchase offers don't show when the buyer's checkout currency differs from your store's base currency — this is expected Shopify platform behavior.
- Check any conditional targeting rules on the offer.

### Why isn't my discount code offer showing the discount I expect?

Check the offer's discount mode (percentage, fixed amount, or fixed price) in the Offer Builder's design step — each behaves differently, and fixed price will never exceed the stated price regardless of the product's current price.

### Still stuck?

Reach out via [Contact Support](contact.md) — include your store domain and the offer name/ID if possible, so we can look it up quickly.
