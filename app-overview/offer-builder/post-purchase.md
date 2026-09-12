# Post-purchase (One-Click Upsell)

Post-purchase offers appear immediately after checkout, before the shopper reaches their order confirmation — letting them add one more item with a single click and no re-entry of payment details.

### How it works

The shopper sees the offer, clicks accept, and the item is added to their existing order via a checkout extension — no new cart or repeated checkout.

### Targeting

Post-purchase offers can be shown to everyone, or conditionally based on:

- Specific products, collections, vendors, or product types in the completed order
- Minimum order value or minimum item count

Offers with no rules configured show on every order.

### Variant & quantity

Shoppers can pick a variant and quantity (1–99) with live price updates before accepting.

### Discounts

Percentage, fixed-amount off, or fixed price (a fixed-price offer will never charge more than the stated price, even if the underlying product price changes).

### Reviews

If you use a supported reviews app (Judge.me, Loox, or Yotpo), star ratings can display on the offer automatically.

### Sequencing & suppression

If you run multiple post-purchase offers, you can set the order they're evaluated in and choose to hide an offer from a shopper who's already purchased that product.

### Scheduling

Optional start/end dates, same as other offer types.

{% hint style="warning" %}
Post-purchase offers are not shown when the buyer's checkout currency differs from your store's base currency — this is a Shopify checkout platform behavior, not something UpsellSuite can override.
{% endhint %}

### Requirements

Post-purchase offers require Shopify's post-purchase checkout extension capability to be available on your store (see [Requirements & Compatibility](../../getting-started/requirements.md)).
