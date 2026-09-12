# Product-Page Placement

**No action needed by default.** Once the [App Embed](settings/theme-integration.md) is enabled, Product-page offers (FBT, Cross-sell, Add-on) automatically appear right below the "Add to Cart" button. The options on this page are entirely **optional** — use them only if you want to move an offer to a different spot on the product page.

{% hint style="info" %}
This only controls the **Product-page** widget's position. Cart, Post-purchase, and Thank-you page offers are placed via their own mechanisms (the cart app block / Shopify Checkout editor) — each offer's own setup links you there.
{% endhint %}

### Option 1 — Reposition with App Block (recommended)

The easiest way to move a Product-page offer: open the Theme Editor with the "UpsellSuite Offer" block ready to drag into place. No coding required, and it works on any Online Store 2.0 theme.

From the app's **How to use** page, click **Open theme editor** under "Reposition with App Block."

### Option 2 — Manual code snippet

For themes that don't support app blocks, or if you need the offer in an exact custom spot in your product template, paste this snippet directly into your theme code:

```html
<div class="offer-widget-rev-growth-app"></div>
```

The offer will render exactly where you place this `<div>`.

{% hint style="warning" %}
The manual snippet still requires the App Embed to be enabled (see [Installation Guide](../getting-started/installation.md)) — it controls *where* the offer appears, not *whether* it can appear at all.
{% endhint %}

You can copy this snippet directly from the app's **How to use** page, under "Manual code snippet."
