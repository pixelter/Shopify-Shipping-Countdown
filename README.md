# Shopify Shipping Countdown

### How To Use It
1. Copy all files to your theme

```
/assets/moment.min.js
/assets/moment-timezone.min.js
/sections/shipping-countdown.liquid
```

2. Load scripts from your assets 

```
{{ 'moment.min.js' | asset_url | script_tag }}
{{ 'moment-timezone.min.js' | asset_url | script_tag }}
```

3. Add the section to the bottom of your theme

```
{% section 'shipping-countdown' %}
```

4. Configure options in your theme settings

5. Add a target element to your product page or shopping cart (example, you can use your own)

```
<div class="js-shipping-countdown"></div>
```
