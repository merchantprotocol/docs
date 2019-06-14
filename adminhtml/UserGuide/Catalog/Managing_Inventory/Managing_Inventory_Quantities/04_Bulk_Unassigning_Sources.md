Bulk Unassigning Sources
--
When unassigning a source from a product, you are indicating the product will no longer be stocked at that location. This process will completely clear all inventory data for source currently assigned to the product. If you need to move the existing inventory to a new location, consider using the Transfer inventory option.

> **Important**: Unassigning a source clears all quantity data. Reassigning a source with quantity data can potentially cause issues with pending orders with reservations and affect stock salable quantity counts. Keep in mind, all product quantities in shopping carts and submitted orders have associated reservations. If you unassign the only sources providing those products to the stock, orders cannot be completed and shipped for that sales channel.

> **Recommendation**: We recommend processing all pending orders and sending shipments prior to removing sources or transferring all inventory.

We strongly recommend completing all orders and shipments for those products prior to removing the source.

## To update quantities:

1.	On the Admin sidebar, tap **Catalog**. Then, choose **Products**.
2.	Select the products you want to modify sources. Browse or search to find the products and select those checkboxes.
3.	Tap the **Actions** drop-down menu, and choose Unassign Inventory Source. Tap OK to verify.
![Select products to remove sources](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-bulk-unassign-sources_thumb_0_0.png)
4.	Select the source you want to remove from the products.
5.	Tap **Unassign Sources**. An alert displays that unassigning will remove all specific source and quantity data from the product.
6.	To complete, tap [**Unassign Sources**.
![Remove sources from selected products](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-bulk-unassign-sources2_thumb_0_0.png)