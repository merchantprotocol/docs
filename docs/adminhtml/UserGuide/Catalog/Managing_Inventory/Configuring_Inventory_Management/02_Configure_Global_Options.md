Configure Global Options
--

Configure the default configuration options for product and stock for your websites. Some of these settings can be overridden per product through Configuring Product Options. To configure Distance Priority settings, see Configuring Distance Priority Algorithm.

## To configure product and stock options globally:

1.	On the Admin sidebar, tap **Stores**. Then under Settings, choose **Configuration**.
2.	In the panel on the left under Catalog, choose **Inventory**.
3.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Stock Options** section.

  a.	To adjust the quantity on hand when an order is placed, set **Decrease Stock When Order is Placed** to “Yes.”

  b.	To return items to stock if an order is canceled, set **Items’ Status to be in Stock When Order in Cancelled** to “Yes.”

  c.	Set **Display Out of Stock Products** to “Yes” to continue to display products in the catalog that are no longer in stock.

  If price alerts are enabled, customers can sign up to be notified when the product is back in stock.

  d.	Enter an amount for **Only X left Threshold** to start displaying the last remaining inventory amount on the product page.
  
  The message begins to appear when the quantity in stock reaches the threshold. For example, if set to 3, the message “Only 3 left” appears when the quantity in stock reaches 3. The message adjusts to reflect the quantity in stock, until the quantity reaches zero.

  e.	To display an “In Stock” or “Out of Stock” message on the product page, set **Display Products Availability In Stock on Storefront** to “Yes.”
 
  ![Stock Options](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-inventory-stock-options_thumb_0_0.png)

4.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Product Stock Options** section.

  a.	To activate inventory control for your catalog, set **Manage Stock** to “Yes.”
 
  ![Product Stock Options](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-inventory-product-stock-options_thumb_0_0.png)
  
  b.	Set Backorders to one of the following:

  * **No Backorders** To not accept backorders when product is out of stock.
  * **Allow Qty Below 0** To accept backorders when the quantity falls below zero.
  * **Allow Qty Below 0 and Notify Customer** To accept backorders when the quantity falls below zero, and notify the customer that the order can still be placed.

  c.	Enter the **Maximum Qty Allowed in Shopping Cart**.

  d.	Enter an amount for the **Out-of-Stock Threshold**:

  * **Positive amount** With Backorders disabled, enter a positive amount.
  * **Zero** With Backorders enabled, entering zero allows for infinite backorders.
  * **Negative amount** With Backorders enabled, we recommend entering a negative amount. The amount is added to the Salable Quantity. For example, enter -50 to allow orders up to this amount.

  e.	Enter the **Minimum Qty Allowed in Shopping Cart** for selected group and amounts.

  f.	In the **Notify for Quantity Below** field, enter the stock level that triggers notification that the item is out of stock.

  g.	To activate quantity increments for the product, set **Enable Qty Increments** to “Yes.” Then in the **Qty Increments** field, enter the number of the items that must be purchased to meet the requirement. For example, an item that is sold in increments of 6 can be purchased in quantities of 6, 12, 18, and so on.

  h.	For Inventory Management, Automatically Return Credit Memo Item to Stock is set to "No." When submitting a credit memo, you enter and select to return stock to sources.

5.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Admin bulk operations** section.

  a.	Set **Run asynchronously** to run bulk operations asynchronously for mass product actions including bulk assign sources, unassign sources, and transfer inventory to source. It collects bulk actions up to the Asynchronous batch size, then runs those actions. This option is disabled by default. We recommend reviewing your performance with bulk actions before enabling.

  > **Important**: To configure and support asynchronous queue managers, you need to issue a command using the command line. This step may require developer assistance. See Magento DevDocs, Start message queue consumers.

  b.	If enabled, set the **Asynchronous batch size**. The default batch size is 100. When bulk processes reach this amount, they perform them at that time.
 
  ![Admin Bulk Operations](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-inventory-admin-bulk-operations_thumb_0_0.png)
  
6.	When complete, tap  `Save Config` .