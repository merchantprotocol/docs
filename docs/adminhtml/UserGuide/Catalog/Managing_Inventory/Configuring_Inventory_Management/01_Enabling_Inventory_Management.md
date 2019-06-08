Enabling Inventory Management
--

To manage your product inventory, enable Inventory Management at the global store or product level. When the Manage Stock option is enabled, Magento Inventory Management automatically tracks product quantities available for the site through configured stocks and sources. Every feature and option begins tracking and reporting when enabled, without additional configuration.

Your business runs and inventory updates at the speed of sales. As customers shop, you receive exact, updated information for available stock per sales channel and source. Available salable quantities update per stock when customers add products to cart and complete purchases and when and you manage orders, create shipments, and issue refunds. Arrivals of new or transferred stock update to your sources, immediately available for online sales. Backorders complete up to specified thresholds without infinite orders or additional configurations. And you enter and complete partial or full shipments across one or more sources with recommendations, giving you complete control over order fulfillment and on-hand inventory.

> By default, Inventory Management is enabled by default when installing or upgrading Magento. Depending on your business needs, you may want to enable or disable Magento tracked Inventory Management.

How this setting works in Single and Multi Source inventories:

* To use Magento Inventory Management, enable Manage Stock.
* Manage Stock settings at the product level override the store configuration.
* To use Magento Order Management or third party services such as ERP, disable Manage Stock.
* If the product level configuration uses the system default, the store configuration overrides.

With Inventory Management enabled, see the following to configure all settings:

* Configuring Global Options: Settings that affect your entire catalog, considered the system default settings
* Configuring Product Options: Settings for a specific product that override global options

## To manage stock for a store:

1.	On the Admin sidebar, tap **Stores**. Then under Settings, choose **Configuration**.
2.	Select the Store View to edit:
3.	Tap **Catalog**. Then choose Catalog and Inventory.
4.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the Stock Options section, and configure Manage Stock:

  * To manage inventory and use all Magento features, select Yes.
  * To disable Magento Inventory Management, select No. You may need to clear the Use system value checkbox.

5.	When complete, tap  `Save Config` .
 
![Product Stock Options](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-inventory-product-stock-options_thumb_0_0.png)

## To manage stock for a product:

1.	On the Admin sidebar, tap **Catalog**. Then choose **Products**.
2.	Locate and open a product in **Edit** mode.
3.	In the Sources section, tap **Advanced Inventory**.
4.	Configure Manage Stock:

  * To manage inventory and use all Magento features, select Yes.
  * To disable Magento Inventory Management, select No. You may need to clear the Use system value checkbox.
  
5.	When complete, tap `Done`.
 
![Advanced Inventory for a Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-inventory-manage-stock-yes_thumb_0_0.png)