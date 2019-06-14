Configuring Product Options
--

These configurations apply only to the edited product, overriding all configurations at the global website level. Modify these settings when editing a product, through the Sources section and Advanced Inventory page.

* Configure product options by source
* Configure product Advanced Inventory options

## To configure product options by source:
Configure the quantities and additional settings per added source for the product.

1.	On the Admin sidebar, tap **Catalog**. Then choose **Products**.
2.	Locate and open a product in **Edit** mode.
3.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the Sources section, and configure product settings per source:

  a.	Enter a Quantity amount.
  
  b.	Set the Stock Status as In Stock or Out of Stock.

  c.	To modify the Notify for Quantity Below per source, clear or select the **Notify Quantity Use Default** checkbox. If cleared, enter the stock level that triggers notification that the item is out of stock. This amount is subtracted from the Salable Quantity at the stock level.

OPTION | DESCRIPTION
-- | --
Select to use Default | Magento checks the product Advanced Inventory options for configuration settings.
Clear to Modify | Enter a value for the Notify Quantity, overriding Advanced Inventory and Store configuration settings.

4.	When complete, tap  `Done` , then `Save`.
 
![Sources Section for Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-product-quantities_thumb_0_0.png)

5.	When complete, tap  `Done` , then `Save`.

### Field Descriptions

FIELD | SCOPE | DESCRIPTION
-- | -- | --
Source Code | Global | The unique code for a source.
Name | Global | The unique name for a source.
Status | Global | Product is enabled or disabled in the catalog.
Source Item Status | Global | Determines the current availability of the product. Options:
 | | **In Stock** Makes the product available for purchase.
 | | **Out of Stock** Unless Backorders are activated, prevents the product from being available for purchase and removes the listing from the catalog.
Qty | Global | On-hand stock amounts for each source, or location
Notify Quantity | Global | An amount for the Notify for Quantity Below for this specific source if Notify Quantity Use Default is not selected.
Notify Quantity Use Default | Global | Indicates to use the default setting for Notify for Quantity Below in the product Advanced Inventory or global setting in Store configuration.

## To configure advanced product options:

1.	On the Admin sidebar, tap **Catalog**. Then choose **Products**.
2.	Locate and open a product in **Edit** mode.
3.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the Sources section, tap Advanced Inventory and configure:

  a.	To activate inventory control for your catalog, set **Manage Stock** to “Yes.”
 
  ![Advanced Inventory for a Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-inventory-manage-stock-yes_thumb_0_0.png)

  b.	Enter an amount for the **Out-of-Stock Threshold**:

  * **Positive amount** With Backorders disabled, enter a positive amount.

  * **Zero** With Backorders enabled, entering zero allows for infinite backorders.

  * **Negative amount** With Backorders enabled, we recommend entering a negative amount. The amount is added to the Salable Quantity. For example, enter -50 to allow orders up to this amount.

  c.	Enter the **Minimum Qty Allowed in Shopping Cart**.

  d.	Enter the **Maximum Qty Allowed in Shopping Cart**.

  e.	Set **Qty uses Decimals** to Yes/No if customers can use a decimal value rather than a whole number when entering the quantity ordered.

  f.	Set **Allow Multiple Boxes for Shipping** to Yes/No if the product can be sold separately, in many boxes.

  g.	Set **Backorders** to one of the following. For complete information on backorders, see Configuring Backorders.

  * **No Backorders** To not accept backorders when product is out of stock.

  * **Allow Qty Below 0** To accept backorders when the quantity falls below zero.

  * **Allow Qty Below 0 and Notify Customer** To accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.

  h.	In the **Notify for Quantity Below** field, enter the stock level that triggers notification that the item is out of stock. This amount is subtracted from the Salable Quantity at the stock level.
  
  i.	To activate quantity increments for the product, set **Enable Qty Increments** to “Yes.” Then in the **Qty Increments** field, enter the number of the items that must be purchased to meet the requirement. For example, an item that is sold in increments of 6 can be purchased in quantities of 6, 12, 18, and so on.
  
4.	When complete, tap  `Done` , then `Save`.


### Field Descriptions

FIELD | SCOPE | DESCRIPTION
-- | -- | --
Manage Stock | Global | Determines if inventory control is used to manage this product in your catalog. Options:
 | | **Yes** Enables all Magento Inventory Management features.
 | | **No** Disables all Magento Inventory Management features.
Out-of-Stock Threshold | Global | Determines the stock level at which a product is considered to be out of stock.
 | | **Positive amount** With Backorders disabled, enter a positive amount.
 | | **Zero** With Backorders enabled, entering zero allows for infinite backorders.
 | | **Negative amount** With Backorders enabled, we recommend entering a negative amount. The amount is added to the Salable Quantity. For example, enter -50 to allow orders up to this amount.
Minimum Qty Allowed in Shopping Cart | Global | Determines the minimum number of the product that can be purchased in a single order.
Maximum Qty Allowed in Shopping Cart | Global | Determines the maximum number of the product that can be purchased in a single order.
Qty Uses Decimals | Global | Determines if customers can use a decimal value rather than a whole number when entering the quantity ordered. Options:
 | | **Yes** Permits values to be entered as decimals, rather than whole numbers, which is suitable for products sold by weight, volume or length.
 | | **No** Requires quantity values to be entered as whole numbers.
Allow Multiple Boxes for Shipping | Global | Determines if parts of the product can be shipped separately. Options: Yes / No
Backorders | Global | Determines how backorders are managed. Backorders do not change the processing status of the order. Funds are still authorized or captured immediately when the order is placed, regardless of whether the product is in stock. Products are shipped as they become available.
 | | `When enabled, we recommend entering a negative amount for the Out-of-Stock Threshold.`
 | | Options:
 | | **No Backorders** Does not accept backorders when product is out of stock.
 | | **Allow Qty Below 0** Accepts backorders when the quantity falls below zero.
 | | **Allow Qty Below 0 and Notify Customer** Accepts backorders when the quantity falls below zero, but notifies customers that orders can still be placed.
Notify for Quantity Below | Global | Sets the quantity that triggers a Quantity Below notification, warning of low stock. This amount is deducted from the Salable Quantity, not from the inventory Quantity.
Enable Qty Increments | Global | Determines if the product can be sold in quantity increments. Options: Yes / No