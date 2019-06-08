Configuring Backorders
--

Backorders allow your store to continue selling products after the quantity reaches zero, or is effectively out of stock. When a customer order is a backorder, the funds are authorized and captured immediately, the processing status of the order does not change, and the shipping remains on-hold until stock is available.

Depending on your store and sales, you may want to enable or disable backorders at the following levels:

* Global - All products in your catalog at the site level
* Source - All products with the assigned source
* Product - Specific products overriding settings for site, source, and stock

## Understand Backorder Settings
We recommend configuring specific thresholds and settings to best support backorders.

### Out-of-Stock Threshold

Use a negative value for this threshold to set the maximum amount of products that can be backordered before the product is truly considered out of stock. This amount adds to the salable quantity. The value set at the product level overrides any value set at the global level.

The formula for the Salable Quantity is: (Quantity - (out-of-Stock Threshold).

The following is an example:

* Quantity: 25
* Notify for Quantity Below: 10
* Only X left Threshold: 5
* Out of Stock Threshold: -50

The Salable Quantity for this product is 75 (25 - (-50)).

![Example Salable Quantity before backorders enabled](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-backorders-before_thumb_0_0.png)
 
![Example Salable Quantity after backorders enabled](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-backorders-after_thumb_0_0.png)

When customers purchase over 25 products, new orders enter as backorders. As the product's salable quantity reduces to 5 (70 items have been sold), the product page will display a message "Only 5 left" on front-end. When the salable quantity reaches 0, the product displays as Out of Stock in the storefront.

### Notify for Quantity Below

The Notify for Quantity Below configuration option is configurable at the global, source, and product levels. It sends an email notification when a product's quantity reaches a low quantity. For this example, the notification sends when the product has a quantity of 10 or less. When backorders are enabled, the Notify for Quantity Below is not deducted from the Salable Quantity.

### Stock Status

Products must be set to In Stock status when enabling backorders. You can set this through the Product page. For multi source merchants, you must have at least one source marked as In Stock. Access and set the status through the product page and assigned sources grid.

## Configure Backorders Globally

These steps enable backorders for all products at the site level.

1.	On the Admin sidebar, tap **Stores**. Then under Settings, choose **Configuration**.
2.	Select Default Config for the Store View.
3.	Tap **Catalog**, then choose **Inventory**.
4.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the Product Stock Options, and locate Backorders. Clear the **Use system value** checkbox and select an option from the drop-down menu:

OPTION | DESCRIPTION
-- | --
No Backorders | To not accept backorders when product is out of stock.
Allow Qty Below 0 | To accept backorders when the quantity falls below zero.
Allow Qty Below 0 and Notify Customer | To accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.

5.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the Product Stock Options, and locate Out-of-Stock Threshold. Clear the **Use system value** checkbox to enter a different amount.

OPTION | DESCRIPTION
-- | --
Positive amount | With Backorders disabled, enter a positive amount.
Zero | With Backorders enabled, entering zero allows for infinite backorders.
Negative amount | With Backorders enabled, we recommend entering a negative amount. The amount is added to the Salable Quantity. For example, enter -50 to allow orders up to this amount.

6.	Tap `Save Config`.

## Configure Backorders for a Product

Product level configurations override global configurations. You may want to configure backorders at the product level to override the settings at the global store or source level. For example, your store may globally support backorders. With product settings, you can disable backorders or change the Out-of-Stock threshold without affecting other products and sources.

1.	On the Admin sidebar, tap **Catalog**. Then, choose **Products**.
2.	Locate and open a product in **Edit** mode. Scroll down the page to the Sources area.
3.	Tap **Advanced Inventory**. A page of product specific configurations displays. Any setting listed as global displays the current global setting for the store.
4.	Locate **Backorders** and clear the **Use Config Setting** checkbox and select an option from the drop-down menu:

OPTION | DESCRIPTION
-- | --
No Backorders | To not accept backorders when product is out of stock.
Allow Qty Below 0 | To accept backorders when the quantity falls below zero.
Allow Qty Below 0 and Notify Customer | To accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.

5.	Locate Out-of-Stock Threshold and clear the **Use Config Setting** checkbox to enter an amount:

OPTION | DESCRIPTION
-- | --
Positive amount | With Backorders disabled, enter a positive amount.
Zero | With Backorders enabled, entering zero allows for infinite backorders.
Negative amount | With Backorders enabled, we recommend entering a negative amount. The amount is added to the Salable Quantity. For example, enter -50 to allow orders up to this amount.

6.	Tap `Done`, then tap `Save`.
 
![Advanced Inventory configured for Backorders](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-backorders-product-settings_thumb_0_0.png)