# Targeting & Scheduling

Every offer (except Post-purchase, which has its own conditional rules — see [Post-purchase](offer-builder/post-purchase.md)) can be shown to everyone, or narrowed down using one or more targeting rules from Step 4 of the Offer Builder.

### Available rules

| Rule | Shows the offer when... |
|---|---|
| **Cart products** | The cart contains specific products |
| **Cart value** | The cart total is above/below a set amount |
| **Items in cart** | The cart contains a certain number of items |
| **Customer tag** | The customer has specific tags on their account |
| **Customer type** | The customer is new or returning |
| **Customer country** | The customer's country matches |
| **Past orders** | The customer has placed a certain number of previous orders |
| **Discount code** | A discount code is (or isn't) currently applied |

Multiple rules combine with AND logic — an offer only shows when every configured rule is satisfied.

{% hint style="info" %}
Customer-based rules (tag, type, country, past orders) aren't available on Post-purchase offers, since post-purchase eligibility checks don't have access to customer data.
{% endhint %}

### Scheduling

Every offer can optionally be scheduled with an **active from** and **active until** date/time, evaluated in your store's timezone. Outside that window, the offer simply doesn't render — no need to manually pause and resume it.

### Countdown timers

Where supported (FBT, Cross-sell, Cart Drawer), you can add a countdown timer on top of scheduling — either a fixed end date shared by every shopper, or a session-based timer that starts fresh per visitor.
