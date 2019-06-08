Importing and Exporting Inventory
--

For catalogs with a large amount of products, use the Import and Export features of Magento with expanded Inventory Management options to update sources and quantities by SKU. With these options, you can add new sources and update inventory quantities for all or a specific source. For example, you can export products for a source in Germany without affecting product information for sources in France, England, or the US.

* Magento automatically assigns the Default Source to your products when upgrading Magento or importing new products. If you import products with a custom source assigned, the Default Source will still be added with a quantity of 0. To update sources and quantities, use these import instructions.
* Single Source merchants use import to update only product quantities. All existing and added products are assigned to the Default Source.
* Multi Source merchants use import to add multiple sources and quantities per row per SKU.

To import updates, first export a CSV file for a specific or all sources. Edit the CSV file and add a row per SKU for each source and quantity. You need the source's code when adding a new source and adding quantities of stock. You cannot add or update stocks using import-export features.

## CSV file content

The export-import file includes the following information according to source:

 * **source_code**: The code for sources in Magento. You will see a row for each source and SKU.
 * **sku**: The SKU for the product in Magento. The SKU must match a product in your store to properly update Inventory Management data.
 * **status**: 0 for Out of Stock. 1 for In Stock. This value must be 1 to purchase stock from this source.
 * **quantity**: The total amount of inventory available for this SKU and source.
 
Use this option to quickly update multiple products and assigned sources to update and correct any inaccuracies in inventory records rather than one at a time through the application interface. For a base file, export first and update as needed.

![Example CSV file for Import - Export Inventory Data](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-import-export-data_thumb_0_0.png)

## To export product data for all sources:

1.	On the Admin sidebar, tap **System**. Under **Data Transfer**, choose **Export**.
2.	From the **Entity Type** drop-down menu, select **Stock Sources**. The export only extracts data for products with a SKU.
3.	Tap `Continue`. The file generates and downloads to open and edit.

After updating inventory amounts and product data, import the file back into Magento.

![Export Stock Sources for product data and sources](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-export-stock-sources_thumb_0_0.png)

## To export product data for a specific source:

1.	On the Admin sidebar, tap **System**. Under **Data Transfer**, choose **Export**.
2.	From the Entity Type drop-down menu, select **Stock Sources**. The export only extracts data for products with a SKU.
3.	To filter the exported products for a specific source, scroll to the Entity Attributes. For source_code, enter the code for the source in the filter field.
4.	Tap Continue. The file generates and downloads to open and edit.
After updating inventory amounts and product data, import the file back into Magento.

![Export Stock Sources for product data and sources](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-export-stock-sources_thumb_0_0.png)

## To import product data:

1.	On the Admin sidebar, tap **System**. Under Data Transfer, choose **Import**.
2.	From the Entity Type drop-down menu, select Stock Sources. The export only extracts data for products with a SKU.
3.	Select configurations for the Import Behavior.
4.	Select the .csv file to import.
5.	Tap **Check Data** and complete the import.
![Import product data and sources](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-import-sources_thumb_0_0.png)