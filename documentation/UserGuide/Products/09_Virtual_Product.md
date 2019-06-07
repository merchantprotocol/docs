Virtual Product
--
Virtual products — or digital goods — represent non-tangible items such as memberships, services, warranties, or subscriptions and digital downloads of books, music, videos, or other products. Virtual products can be sold individually, or included as part of the following product types:

 * Grouped Product
 * Bundle Product

Aside from the absence of the Weight field, the process of creating a virtual product and a simple product is the same. The following instructions take you through the process of creating a virtual product using a product template , required fields, and basic settings. When you finish the basics, you can complete the advanced settings and other settings as needed.

> PayPal has deprecated support for the sale of digital goods through PayPal Express Checkout, and recommends that you use either PayPal Payments Standard or any other PayPal payment gateway to process any order that includes virtual products.

![Virtual Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-virtual-membership_thumb_0_0.png)

## Step 1: Choose the Product Type
1.	On the Admin sidebar, tap **Products**. Then, choose **Catalog**.
2.	In the upper-right corner on the **Add Product** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-save-menu_17x18.png) ) menu, choose **Virtual Product**.
 
![Add Virtual Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/21product-add-virtual_thumb_0_0.png)

## Step 2: Choose the Attribute Set
To choose the attribute set that is used as a template for the product, do one of the following:

* In the **Search** box, enter the name of the attribute set.
* In the list, choose the attribute set that you want to use.
The form is updated to reflect the change.

![Choose Attribute Set](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-choose-attribute-set_thumb_0_0.png)

## Step 3: Complete the Required Settings
1.	Enter the product **Product Name**.
2.	Accept the default **SKU** that is based on the product name, or enter another.
3.	Enter the product **Price**.
4.	Because the product is not yet ready to publish, set the Enable Product switch to the “No” ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-switch-no_32x18.png) ) position.
5.	Tap  `Save`  and continue.
  When the product is saved, the Store View chooser appears in the upper-left corner.
6.	Choose the Store View where the product is to be available.
  ![Choose Store View](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-store-view-choose_thumb_0_0.png)

## Step 4: Complete the Basic Settings

1.	Set **Tax Class** to one of the following:
  * None
  * Taxable Goods
2.	Enter the **Quantity** of the product that is currently in stock. Then, do the following:

  a.	Accept the default Stock Status setting, “In Stock.”
Note that the Weight field is not used, because a virtual product is not shipped.
  b.	Accept the default Visibility setting, “Catalog, Search.”
  
  *Assign Sources and Quantities (Inventory Management)*
  
  For Multi Source merchants using Inventory Management, scroll down to the Sources section and assign sources and quantities:

  1.	To add a source, tap **Assign Sources**. The Assign Sources page displays.
  2.	Browse or search for a source you want to add. Select the checkbox next to the source(s) you want to add for the product.
  ![Assign sources to the product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-product-assign-sources_thumb_0_0.png)
  3.	Tap **Done** to add the sources.
  4.	To change settings and quantities per assigned source, do the following:
  
    a.	Set **Source Item Status** to In Stock.
    b.	Enter an amount update the **Qty** for on-hand stock.
    c.	To set a notification for inventory quantities, do one of the following:

 | 
 -- | --
Custom Notify Quantity | Clear the Notify Quantity Use Default checkbox and enter an amount in Notify Quantity.
Default Notify Quantity | Select the Notify Quantity Use Default checkbox. Magento checks and uses the setting in Advanced Inventory or global Store configuration.
 
![Update Product Quantities per Source](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-product-quantities_thumb_0_0.png)

5.	To assign **Categories** to the product, tap the **Select…** box. Then, do either of the following:

  **Choose an existing category:**

  a.	Start typing in the box to find a match.
  b.	Mark the checkbox of the category that is to be assigned.

  **Create a new category:**

  a.	Tap  `New Category` .
  b.	Enter the **Category Name** and choose the **Parent Category** to determine its position in the menu structure.
  c.	Tap  `Create Category` .
  
There might be additional individual attributes that describe the product. The selection varies attribute set, and you can complete them later.

## Step 5: Complete the Product Information

Complete the information in the following sections as needed:

  * Content
  * Images and Videos
  * Search Engine Optimization
  * Related Products, Up-Sells, and Cross-Sells
  * Customizable Options
  * Products in Websites
  * Design
  * Gift Options

## Step 6: Publish the Product

1.	If you are ready to publish the product in the catalog, set the **Enable Product** switch to the “Yes” ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-switch-yes_32x18.png) ) position.
2.	Do one of the following:

  *Method 1: Save and Preview*
  1.	In the upper-right corner, tap `Save`.
  2.	To view the product in your store, choose **Customer View** on the **Admin** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-dropdown-blk_22x18.png) ) menu. The store opens in a new browser tab.
 
  ![Customer View](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-admin-customer-view_thumb_0_0.png)
  
  *Method 2: Save and Close*
  On the Save ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-dropdown_17x18.png) ) menu, choose **Save & Close**.

  ![Save & Close](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-edit-save-close_thumb_0_0.png)
  
### THINGS TO REMEMBER

> Virtual products are used for non-tangible products such as services, subscriptions, and warranties.

> Virtual products are much like simple products, but without weight.

> Shipping Options do not appear during checkout unless there is a tangible product in the cart.