Adding a New Stock
--

Stocks map your sources to sales channels (or websites), providing a direct link to salable quantities and product inventories.

When creating a custom stock, you assign websites and sources. Sources can include enabled and disabled sources. For example, you may add a new warehouse to your stock, preparing to open the location for managing inventory and completing shipments.

After adding sources, you need to prioritize the order for the sources from top (first) to bottom (last). This order affects recommendations during order shipment.

![New Stock](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-stock-new_thumb_0_0.png)

## To add new stock:

1.	On the Admin sidebar, tap **Stores**. Then under **Inventory**, choose **Stock**.
2.	Tap `Add New Stock`.
3.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **General** section. Then, enter a unique **Name** to identify the new stock.
![General](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-stock-general_thumb_0_0.png)
4.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Sales Channels** section. Then, select the **Websites** where this stock is available. For a multisite installation, hold the Ctrl key and tap each website.

> If you select a website or sales channel assigned to another stock, it will be unassigned from that stock. Any Sales Channels not assigned to a custom stock are assigned to the Default Stock.

![Sales Channels](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-stock-sales-channel_thumb_0_0.png)

5.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Sources** section. For any stock other than the default, do the following:

  a.	Tap `Assign Sources`.

  ![Assigned Sources](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-stock-sources_thumb_0_0.png)
  
  b.	Select checkboxes for all sources you want to assign to the stock.

  c.	Tap `Done`. The added sources display in Assigned Sources.
 
  ![Assign Sources to Stock](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-stock-assign-sources_thumb_0_0.png)
  
6.	Use ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-sort-3_10x18.png) to drag and drop the sources into a priority from top (first) to bottom (last). This order is important when shipping orders.
![Assigned Sources Example](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-stock-priorityafter_thumb_0_0.png)
7.	On the Save  () menu, choose Save & Close.

### Field Descriptions

FIELD | DESCRIPTION
-- | --
**GENERAL** | 
Name | Name for the stock. For example: UK Stock, US Stock
**SALES CHANNELS** | 
Websites | Defines the scope of the stock by assigning the stock to specific website(s) as “sales channels.” Select one or more websites per stock. Each website can only be assigned to one stock.
**SOURCES** | 
Assign Sources | Assigns inventory sources to this stock. `Custom sources cannot be assigned to Default Stock.`
Assigned Sources | List of assigned sources. Drag and drop the sources using ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-sort-3_10x18.png) into a prioritized order for order fulfillment and shipping.
 | **Code** Unique code id for the source.
 | **Name** Name description for the source.
 | **Unassign** Remove the assigned source from the stock using .