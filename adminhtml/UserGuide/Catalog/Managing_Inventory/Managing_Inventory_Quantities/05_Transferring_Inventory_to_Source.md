Transferring Inventory to Source
--

Depending on your business needs and status of location, Multi Source merchants may need to transfer product inventory from one source location to another. For example, you may be closing a warehouse location or no longer ship specific products from a location, moving all operations for those products to a new location.

This option allows you to select one or more products, the origin source to transfer inventory, and the destination source to receive quantities:

* Inventory quantities, Source Item Status (In Stock/Out of Stock), and the Notify Quantity for the selected source are moved per product.
* If a product does not have that source, it is skipped.
* All product inventory for the source is moved. You cannot transfer a partial quantity.

> **Important**: If the origin and destination sources are in different stocks, this will affect the aggregated Salable Quantity and reservations for in-progress orders.

You have an option to also unassign the source when transferring inventory quantities.

> **Important**: Unassigning a source clears all quantity data. Reassigning a source with quantity data can potentially cause issues with pending orders with reservations and affect stock salable quantity counts. Keep in mind, all product quantities in shopping carts and submitted orders have associated reservations. If you unassign the only sources providing those products to the stock, orders cannot be completed and shipped for that sales channel.

> **Recommendation**: We recommend processing all pending orders and sending shipments prior to removing sources or transferring all inventory.

## To transfer inventory to source:

1.	On the Admin sidebar, tap **Catalog**. Then, choose **Products**.
2.	Select the products you want to modify sources. Browse or search to find products and select checkboxes for transfer.
3.	Tap the **Actions** drop-down menu, and choose Transfer Inventory to Source. Tap OK to verify.
![Select products to transfer inventory](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-bulk-transfer-source_thumb_0_0.png)
4.	Select the origin source to transfer products to a new destination. Tap `Continue`.
5.	Select the destination source to transfer products to a new destination.
6.	To remove the source from the products, select the optional checkbox **Unassign from origin source after transfer**.
![Select origin and destination for transfer](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-bulk-transfer-complete_thumb_0_0.png)
7.	Tap **Inventory Transfer**. All product quantities are deducted from the origin source and added to the destination source. The Quantity and Salable Quantity automatically update.