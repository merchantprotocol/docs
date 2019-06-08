Managing Stock
--

Stock represents a virtual, aggregated inventory of products for sources of your sales channels (currently these are websites). Depending on your site configuration, the stock may be assigned to one or more sales channels. Each sales channel can only have a single stock assigned to it, and a single stock can be assigned to multiple websites. Through the stock, you can modify the prioritization of sources used as orders come through a website.

You start with a Default Stock that cannot be removed or disabled. You can add additional sales channels to the stock only. The only assigned source is Default Source. This stock is used by Single Source Merchants, 3rd party integrations, and imported products.

Sales Channels represent entities selling your inventory. By default, Magento provides your store websites as sales channels. Sales channels can be extended to support additional channels such as B2B customers groups and store views. Each sales channels can only be associated to one Stock.

* **Sales Channel Support** - Sales channels currently include websites out-of-the-box. You can extend sales channels to include custom options like B2B customers groups and store views. Each sales channel can only have a single stock assigned to it. A single stock can be assigned to multiple websites.
* **Map to Sources** - Each stock can have one or more enabled or disabled sources assigned, calculating the virtual aggregated inventory per product.
* **Priority Order Fulfillment** - The out-of-the-box Priority algorithm for the Source Selection Algorithm uses the stock's source list from top-to-bottom when fulfilling orders.

The following diagram helps define how a Stock works in relation to Sources and Sales Channels for a Bicycle Shop merchant.

![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-diagram-stock.png)

All stores start with a Default Stock. It must remain "Enabled" for the following:

* It is used when importing new products, automatically assigning products to the default source and stock for immediate access to Inventory Management.
* You cannot add additional sources beyond the Default Source to this stock.
* It is required and used by Single Source merchants, Bundle products, and Grouped products.

For Multi Source merchants, create and configure stocks as needed to best fit your stores and order fulfillment. When you assign new stock to a sales channel, any pre-existing stock in that sales channel becomes unassigned.

For a multisite installation, the Default Stock is initially assigned to the Main Website and default store.

![Manage Stock](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-stock_thumb_0_0.png)

### Button Bar

COLUMN | DESCRIPTION
-- | --
`Add New Stock` | Opens the New Stock form that is used to enter a new inventory stock for mapping inventory to sales channel.

### Manage Stock Column Descriptions

COLUMN | DESCRIPTION
-- | --
ID | Unique, numeric ID generated for the stock entry.
Name | Unique name that identifies the inventory stock.
Sales Channels | Defines the scope of the stock by assigning the stock to specific website(s) as “sales channels.”
Assigned sources | Sources assigned to the stock that supply all product quantities.
Action | **Edit** Opens the inventory stock record in edit mode.