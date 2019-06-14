Configurable Product
--

A configurable product looks like a single product with drop-down lists of options for each variation. Each option is actually a separate simple product with a unique SKU, which makes it possible to track inventory for each product variation. You could achieve a similar effect by using a simple product with custom options, but without the ability to track inventory for each variation.

The following instructions take you through the process of creating a configurable product using a product template, required fields, and basic settings. Each required field is marked with a red asterisk (*). When you finish the basics, you can complete the advanced settings and other settings as needed.

![Configurable Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-configurable_thumb_0_0.png)

## Part 1: Creating a Configurable Product

Although a configurable product uses more SKUs, and may initially take a little longer to set up, it can save you time in the long run. If you plan to grow your business, the configurable product type is a good choice for products with multiple options.

Before you begin, prepare an attribute set that includes an attribute that is set to one of the allowable input types for each product variation. For example, the attribute set might include dropdown attributes for color and size.

The properties of each attribute that is used for a configurable product variation must have the following settings:

### Product Variation Attribute Requirements

PROPERTY | SETTING
-- | --
Scope | Global
Catalog Input Type for Store Owner | The input type of any attribute that is used for a product variation must be one of the following: Dropdown, Visual Swatch, Text Swatch
Values Required | Yes

### Step 1: Choose the Product Type
1.	On the Admin sidebar, tap **Products**. Then, choose **Catalog**.
2.	In the upper-right corner on the **Add Product** ( ![caret](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-save-menu_17x18.png) ) menu, choose **Configurable Product**.
 
![Add Configurable Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/21product-add-configurable_thumb_0_0.png)

### Step 2: Choose the Attribute Set

The attribute set determines the selection of fields that are used in the product. The attribute set that is used in the following example has drop-down attributes for color and size. The name of the attribute set is indicated at the top of the page, and is initially set to “Default”.

1.	To choose the attribute set for the product, click the field at the top of the page and do one of the following:
  * In the **Search** box, enter the name of the attribute set.
  * In the list, choose the attribute set that you want to use.
The form is updated to reflect the change.

2.	If you need to add an additional attribute to the attribute set, tap `Add Attribute`. Then, follow the instruction in Adding an Attribute to a Product.
 
![Choose Template](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-choose-attribute-set_thumb_0_0.png)

### Step 3: Complete the Required Settings
1.	Enter the product **Product Name**.
2.	Accept the default **SKU** that is based on the product name, or enter another.
3.	Enter the product **Price**.
4.	Because the product is not yet ready to publish, set **Enable Product** to the “No” ( ![off](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-switch-no_32x18.png) ) position.
5.	Tap  `Save`  and continue.

> When the product is saved, the Store View chooser appears in the upper-left corner.

6.	Choose the **Store View** where the product is to be available.
 
![Choose Store View](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-store-view-choose.png)

### Step 4: Complete the Basic Settings
1.	Set **Tax Class** to one of the following:
  * None
  * Taxable Goods
2.	The **Quantity** is determined by the product variations, so you can leave it blank for now.
  The Stock Status of a configurable product is determined by each associated configuration. Because the product was saved without entering a quantity, the Stock Status is now set to “Out of Stock.”
  
  a.	Enter the product **Weight**.
  b.	Accept the default **Visibility** setting, “Catalog, Search.”
  
3.	To feature the product in the list of new products, select the **Set Product as New** checkbox.
4.	To assign **Categories** to the product, tap the **Select…** box. Then, do either of the following:

  **Choose an existing category:**

  a.	Start typing in the box to find a match.
  b.	Mark the checkbox of the category that is to be assigned.

  **Create a new category:**

  a.	Tap  `New Category` .
  b.	Enter the **Category Name** and choose the **Parent Category** to determine its position in the menu structure.
  c.	Tap  `Create Category` .

5.	To feature the product in the list of new products, mark the **Set Product as New** checkbox.
6.	Choose the **Country of Manufacture**.
 
![Product Details](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-details-configurable_thumb_0_0.png)

There might be additional attributes that are used to describe the product. The selection varies attribute set, and you can complete them later.

### Step 5: Save and Continue
This is a good time to save your work. In the upper-right corner, tap `Save` . In the next step, you’ll set up the configurations for each variation of the product.

## Part 2: Adding Configurations

The following example shows how to add configurations for three colors and three sizes. In all, nine simple products will be created with unique SKUs to cover every possible combination of variations. By default, the product name and SKU for each variation is based on the parent product name or SKU, plus the attribute value.

The progress bar at the top of the page shows where you are in the process, and guides you through each step.

![Progress Bar](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-configurable-progress-bar-step1_thumb_0_0.png)

### Step 1: Choose the Attributes
1.	Continuing from Part I, scroll down to the **Configurations** section. Then, tap `Create Configurations` .
 
![Configurations](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-configurable-create-configurations_thumb_0_0.png)

2.	Mark the checkbox of each attribute that you want to include as a configuration. For this example, we choose color and size.
3.	The list includes all attributes from the attribute set that can be used in a configurable product.
 
![Select Attributes](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-configurable-step1_thumb_0_0.png)

4.	If you need to add a new attribute, `Create New Attribute` . Complete the attribute properties, and tap `Save Attribute` . Then, mark the checkbox to select the attribute.
5.	In the upper-right corner, tap `Next` .

### Step 2: Enter the Attribute Values
1.	For each attribute, mark the checkbox of the values that apply to the product.
![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-configurable-step2_thumb_0_0.png)
2.	To rearrange the attributes, grab the Change Order ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-sort-order-inline_16x18.png) ) icon and move the section to a new position. The order determines the position of the drop-down lists on the product page.
3.	In the progress bar, `Next`.

### Step 3: Configure the Images, Price, and Quantity
This step determines the images, pricing and quantity of each configuration. The available options are the same for each, and you can choose only one. You can apply the same setting to all SKUs, apply a unique setting to each SKU, or skip the settings for now.

1.	Choose the configuration options that apply.

  **Configure the Images**
  *Method 1: Apply a Single Set of Images to All SKUs*

  1.	Select **Apply single set of images to all SKUs**.
  2.	Browse to each image that you want to include in the product gallery, or drag them to the box.
 
  ![Use Same Images for All SKUs](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-configurations-images-apply-single-set.png)
  
  *Method 2: Apply Unique Images for Each SKU*

  Because we already uploaded an image for the parent product, we’ll use this option to upload an image of each color. This is the image that will appear in the shopping cart when someone buys the shirt in a specific color.

  1.	Select **Apply unique images by attribute to each SKU**.
  2.	Select the **attribute** that the images illustrate. For example: color.
  3.	For each attribute value, either browse to the images that you want to use for that configuration, or drag them to the box.
  If you drag the an image to a value box, it appears in the sections for the other values, as well. If you want to delete an image, tap the trashcan ( ![trash](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-trashcan2_14x18.png) ) icon.

  ![Unique Images per SKU](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-configurable-create-configurations-add-images-unique_thumb_0_0.png)
  
  **Configure the Prices**
  *Method 1: Apply the Same Price to All SKUs*

  1.	If the price is the same for all variations, select **Apply single price to all SKUs**.
  2.	Enter the **Price**.
 
  ![Same Price per SKU](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-configurable-create-configurations-price-all-skus_thumb_0_0.png)

  *Method 2: Apply a Different Price for Each SKU*

  1.	If the price differs for each or for some variations of the product, select **Apply unique prices by attribute to each SKU**.
  2.	Select the **attribute** that is the basis of the price difference.
  3.	Enter the **price** for each attribute value. In this example, the XL size costs more.
 
  ![Unique Price per SKU](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-configurable-create-configurations-price-unique_thumb_0_0.png)

  **Configure the Quantity**
  *Method 1: Apply the Same Quantity to All SKUs*

  1.	If the quantity is the same for all SKUs, select **Apply single quantity to each SKU**.
  2.	Enter the **Quantity**.
 
  ![Same Quantity for All SKUs](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-configurations-quantity-same-all-skus_thumb_0_0.png)
  
  *Apply the Same Quantity to All SKUs (Inventory Management)*

  For Multi Source merchants using Inventory Management, assign sources and add quantities for all generated product variants:

  1.	Select the **Apply single quantity to each SKUs** option.
  2.	To add a source, tap **Assign Sources**. The Assign Sources page displays.
  3.	Browse or search for a source you want to add. Select the checkbox next to the source(s) you want to add for the product.
  4.	Enter an on-hand inventory amount per source.
 
  ![Same Quantity for All SKUs](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-configure-product-quantity_thumb_0_0.png)
  
  *Method 2: Apply Different Quantity by Attribute*

  1.	If the quantity is the different for each SKU, select **Apply unique quantity by attribute to each SKU**.
  2.	Enter the **Quantity** for each.
 
  ![Different Quantities per Attribute](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-configurations-quantity-different_thumb_0_0.png)

2.	When complete, tap `Next` in the upper-right corner.

### Step 4: Generate the Product Configurations

1.	Wait a moment for the list of products to appear.
2.	Do one of the following:
  * If you are satisfied with the configurations, tap **Next**.
  * To make corrections, tap **Back**.
 
  ![Summary](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-configurable-summary_thumb_0_0.png)
  
  The current product variations appear at the bottom of the Configuration section.
 
  ![Current Configurations](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-configurable-summary_thumb_0_0.png)
  
### Step 5: Add a Product Image

1.	Scroll down to the **Images and Videos** section. Then, expand  the section.
2.	Click the **Camera** tile, and browse to the main image that you want to use for the configurable product.
  To learn more, see: Images and Videos.

### Step 6: Complete the Product Information

Scroll down and complete the information in the following sections as needed:

  * Content
  * Related Products, Up-Sells, and Cross-Sells
  * Search Engine Optimization
  * Customizable Options
  * Products in Websites
  * Design
  * Gift Options
  
### Step 7: Publish the Product

1.	If you are ready to publish the product in the catalog, set Enable Product to the “Yes” ( ![on](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-switch-yes_32x18.png) ) position.
2.	Do one of the following:

  **Method 1: Save and Preview**
  (This is the Drop-down text)

  1.	In the upper-right corner, tap `Save`.
  2.	To view the product in your store, choose **Customer View** on the **Admin** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-dropdown-blk_22x18.png) ) menu. The store opens in a new browser tab.
 
  ![Customer View](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-admin-customer-view_thumb_0_0.png)
  
  **Method 2: Save and Close**
  On the **Save** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-dropdown_17x18.png) ) menu, choose **Save & Close**.

  ![Save & Close](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-edit-save-close_thumb_0_0.png)
  
### Step 8: Configure the Cart Thumbnails (Optional)

If you have a different image for each variation you can set the configuration to use the correct image for the shopping cart thumbnail.

1.	On the Admin sidebar, tap **Stores**. Then under Settings, choose **Configuration**.
2.	In the panel on the left under Sales, choose **Checkout**. Then, expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Shopping Cart** section.
3.	Set **Configurable Product Image** to “Product Thumbnail Itself.”
4.	When complete, tap  `Save Config` .
 
  ![Shopping Cart - Configurable Product Image](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-sales-checkout-shopping-cart-configurable-product_thumb_0_0.png)
  
## THINGS TO REMEMBER

> A configurable product allows the shopper to choose options from drop-down, multiple select, visual swatch and text swatch input types. Each option is actually a separate, simple product.

> The attributes that are used for product variations must have a global scope and the customer must be required to choose a value. The product variation attributes must be included in the attribute set that is used as a template for the configurable product.

> The attribute set that is used as a template for a configurable product must include the attribute(s) that contain the values that are needed for each product variation.

> The thumbnail image in the shopping cart can be set to display the image from the configurable product record, or from the product variation.