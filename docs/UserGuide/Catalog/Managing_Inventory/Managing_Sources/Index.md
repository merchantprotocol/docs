Managing Sources
--

Sources represent locations storing and shipping your product stock. Any location with available stock and capable of order fulfillment can be added as a source such as warehouses, brick-and-mortar stores, distribution centers, and drop shippers.

Sources are the physical locations where product inventory is managed and shipped for order fulfillment, or where services are available. These locations can include warehouses, brick-and-mortar stores, distribution centers, and drop shippers. You allocate inventory quantities to these sources, and Magento automatically aggregates the total salable products for your stocks. For large companies, add multiple sources for all of your locations: in different geographic locations by country and continent, locations in a city, based on the type of inventory, even based on services.

You start with a Default Source you can update but not disable. This source is used by Single Source Merchants and for product migration. You always need a default source.

* **Location Information** - Each source includes the name, country, physical address of the location, and a point of contact.
* **Enabling Resources** - You can enable and disable sources as needed. Only enable a source if it accepts and fulfills orders and backorders.
* **Available Inventory** - Assign and update inventory quantities for each source through the product page. The inventory quantities are calculated, provided, and reserved through the source and stock mapping. See Managing Inventory Quantities.

The following diagram helps define the Sources for a Bicycle Shop merchant selling a mountain bike, available to stocks and accessible by the SSA for shipments.

![Example Sources for a Mountain Bike](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-diagram-sources.png)

All stores begin with a Default Source that must remain enabled:

* All new products imported into Magento require a source and stock, automatically assigned for immediate access to inventory management.
* Single Source merchants use the Default Source as their single point of inventory location and shipments.
* Bundle products currently do not support multi-sourcing and must be assigned to Default Source and Default Stock.

## Editing Sources

You can update the name, address, GPS location, and point of contact information. The source's code is a protected value, acting as a unique ID associating the source with your product quantities and stocks.

If editing the Default Source, you can edit all configurations except the code. We recommend Single Source merchants add information for their location, including the address, a contact, and GPS coordinates.

The **Manage Sources** page lists all available inventory locations and fulfillment facilities. You can add new inventory sources, and edit existing locations.

### To manage inventory sources:

1.	On the Admin sidebar, tap **Stores**. Then under **Inventory**, choose **Sources**.
2.	To add a new inventory location, see Adding a New Source.
3.	Find the inventory source and open in **Edit** mode. Then, update the information, and save the changes.
 
![Manage Sources](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-sources_thumb_0_0.png)

### Button Bar
COLUMN | DESCRIPTION
-- | --
Add New Source | Opens the New Source form that is used to enter a new inventory source, fulfillment facility, or location.

### Column Descriptions
COLUMN | DESCRIPTION
-- | --
Code | A unique, alphanumeric code that is used by the system to identify the inventory source. You cannot edit this value after creating a source.
Name | A unique name that identifies the inventory source for Admin users.
Is Enabled | Indicates if the inventory source is active and available to use.
Action | **Edit** Opens the inventory source record in edit mode.