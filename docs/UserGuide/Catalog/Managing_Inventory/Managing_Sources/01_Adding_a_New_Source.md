Adding a New Source
--

Manage inventory and order fulfillment from multiple locations with custom sources. Create a source for each location such as warehouses, brick-and-mortar stores, distribution centers, and drop shippers. Assign sources and update quantities per product

If editing the Default Source, you can edit all configurations except name and code. We recommend single source merchants add information matching their location.

## To add a new inventory source:

1.	On the Admin sidebar, tap **Stores**. Then under **Inventory**, choose **Sources**.
2.	Tap `Add New Source`.
![Manage Sources](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-sources_thumb_0_0.png)
3.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **General** section, and do the following:

  a.	Enter a unique **Name** to identify the inventory source.

  b.	Enter a unique **Code**. The code supports upper and lower case letters, numbers, dashes, and underscores. The code is a unique ID used when assigning to stock and exporting-importing data.

  c.	If this inventory source is ready to use, set **Is Enabled** to “Yes.”

  d.	Enter a brief **Description** for this location for quick reference or additional details.

  e.	In the **Latitude** and **Longitude** fields, enter the Global Positioning System (GPS) coordinates of the facility location.

  To find the GPS coordinates with [Google Maps](https://www.google.com/maps), enter the address in the Search box. Right-click the marker on the map and choose What’s here? The GPS coordinates appear in the details box below the street address.

  ![General](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-source-general_thumb_0_0.png)
  
4.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Contact Info** section, and do the following:

  a.	For the **Contact Name**, enter the full name of the primary contact at the location.

  b.	Enter an **Email** address for contacting the location.

  c.	For the **Phone**, enter the area code and phone number.

  d.	In the **Fax** field, enter the area code and phone number of the fax, if available.

  ![Contact Info](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-source-contact-info_thumb_0_0.png)
  
5.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Address Data** section, and do the following:

  a.	Choose the **Country**.

  b.	For the **State/Province**, enter the standard abbreviation for the state or province.

  c.	Enter the **City**.

  d.	Enter the physical **Street** address.

  e.	For the **Postcode**, enter the ZIP or postal code.
 
  ![Address Data](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-source-address-data_thumb_0_0.png)
  
6.	To save your work, do one of the following:

  * To save your work and continue editing, tap Save & Continue.
  * To save your work and return to the Manage Sources page, tap the down arrow  (  ) and choose Save & Close.
  * To save your work on the current source record and enter a new source, choose Save & New.

### Button Bar

COLUMN | DESCRIPTION
-- | --
Back | Returns to the Manage Sources page.
Reset| Restores all fields in the form to their values at the time of the last save.
Save & Continue | Saves all changes, and keeps the form open for further editing. Click the down arrow for these additional options:
 | **Save & Close** Saves changes to the current record, closes the form, and returns to the Manage Sources page.
 | **Save & New** Saves changes and closes the current record, and opens a new blank form.

### Field Descriptions

FIELD | DESCRIPTION
-- | -- 
**GENERAL** | 
Name | (Required) A unique name that identifies the inventory source for Admin users.
Code | (Required) A unique, alphanumeric code that is used by the system to identify the inventory source. Enter the code in upper or lowercase characters and/or numbers, without spaces. If necessary, a hyphen or underscore can be used instead of a space. The code cannot be edited after creating the source. It is a unique ID used when you assign sources to stocks and export and/or import product data.
Is Enabled | Determines if the inventory source is available to be used. Options: Yes / No
Description | A brief description of the inventory source location. Include details helpful to your Admin users.
Latitude | Specifies the latitude coordinate of the inventory source for GPS. Enter the value as a number, preceded by a plus or minus sign as needed. The degree symbol and letters are not permitted. For example: Latitude 32.7555
Longitude | Specifies the longitude coordinate of the inventory source for GPS. Enter the value as a number, preceded by a plus or minus sign as needed. The degree symbol and letters are not permitted. For example: Longitude -97.3308
**CONTACT INFO** |
Contact Name | The name of the primary contact at the inventory source location.
Email | The email of the primary contact.
Phone | The area code and telephone number of the primary contact, using the format that you prefer. For example: (123) 456-7890 or 123-456-7890
Fax | The area code and fax number of the primary contact.
**ADDRESS DATA** | 
Country | (Required) The country where the inventory source is located.
State/Province | The state or province where the inventory source is located.
City | The city where the inventory source is located.
Street | The street address of the inventory source.
Postcode | (Required) The ZIP or postal code of the inventory source.