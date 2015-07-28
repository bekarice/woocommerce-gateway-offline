=== WooCommerce Offline Gateway ===

 - Contributors: skyverge, beka.rice
 - Tags: woocommerce, payment gateway, gateway, manual payment
 - [Donate link](https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=paypal@skyverge.com&item_name=Donation+for+WooCommerce+Offline+Gateway)
 - Requires at least: 3.8
 - Tested up to: 4.3
 - Requires WooCommerce at least: 2.1
 - Tested WooCommerce up to: 2.4
 - Stable Tag: 1.0.1
 - License: GPLv3
 - License URI: http://www.gnu.org/licenses/gpl-3.0.html

Automatically generate WooCommerce product SKUs from the product slug and/or variation attributes.

== Description ==

> **Requires: WooCommerce 2.1+**

This plugin clones the Cheque gateway to create another offline payment method. This can be used to create a testing payment method if you use the Cheque gateway for something else. For example, this could be used for manual invoices or other offline payment methods.

When an order is submitted via the Offline payment method, the order will be placed "on-hold".

= More Details =
 - See the [product page](http://www.skyverge.com/product/woocommerce-offline-gateway/) for full details and documentation
 - View more of SkyVerge's [free WooCommerce extensions](http://profiles.wordpress.org/skyverge/)
 - View all [SkyVerge WooCommerce extensions](http://www.skyverge.com/shop/)

== Installation ==

1. Be sure you're running WooCommerce 2.1+ in your shop.
2. You can: (1) upload the entire `woocommerce-gateway-offline` folder to the `/wp-content/plugins/` directory, (2) upload the .zip file with the plugin under **Plugins &gt; Add New &gt; Upload**
3. Activate the plugin through the **Plugins** menu in WordPress
4. Go to **WooCommerce &gt; Settings &gt; Checkout** and select "Offline" to configure

== Frequently Asked Questions ==

**What is the text domain for translations?**
The text domain is `wc-gateway-offline`.

**Can I fork this?**
Please do! This is meant to be a simple starter offline gateway, and can be modified easily.

== Changelog ==

= 2015.07.27 - version 1.0.1 =
 * Misc: WooCommerce 2.4 Compatibility

= 2015.05.04 - version 1.0.0 =
 * Initial Release