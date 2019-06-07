Bundle Product
--

A bundle is a “build your own,” customizable product. Each item in a bundle can be based on one of the following product types:

 * Simple Product
 * Virtual Product
 
![Bundle Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle_thumb_0_0.png)

The selection of options appears when the customer taps either the Customize and Add to Cart button. Because the products that are included in the bundle vary, the SKU, Price, and Weight can be set to either a dynamic or fixed value.

> Minimum Advertised Price (MAP) is not available for Bundle products with dynamic pricing.

If Instant Purchase is available, the Instant Purchase button appears below the Add to Cart button for each item in the bundle.

![Customize Bundle](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-customize_thumb_0_0.png)

The following instructions take you through the process of creating a bundle product using a product template, required fields, and basic settings. Each required field is marked with a red asterisk (*). When you finish the basics, you can complete the advanced settings and other settings as needed.

## Step 1: Choose the Product Type

1.	On the Admin sidebar, tap **Products**. Then, choose **Catalog**.
2.	In the upper-right corner on the **Add Product** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-save-menu_17x18.png) ) menu, choose **Bundle Product**.
 
![Add Bundle Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/21product-add-bundle_thumb_0_0.png)

## Step 2: Choose the Attribute Set

To choose the attribute set that is used as a template for the product, do one of the following:

 * In the Search box, enter the name of the attribute set,
 * In the list, choose the attribute set that you want to use.

The form is updated to reflect the change.

![Choose Template](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-choose-attribute-set_thumb_0_0.png)

## Step 3: Complete the Required Settings

1.	Enter the product **Product Name**.
2.	You can either accept the default **SKU** that is based on the product name, or enter a different value. To determine the type of SKU that is assigned to each bundle item, do the following:

  * A **Dynamic SKU** can be assigned automatically to each bundle item by adding a suffix to the default SKU. By default, Dynamic SKU is set to “Yes.”
  * If you prefer to assign a unique SKU for each bundle item, set **Dynamic SKU** to the “No” ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-switch-no_32x18.png) ) position.
  ![Dynamic SKU and Price](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-dynamic-sku-price_thumb_0_0.png)
  
3.	To determine the price of the bundle, do one of the following:

  * A **Dynamic Price** changes to reflect the options chosen by the customer. By default, Dynamic Price is set to “Yes,” and the Price field is left blank.
  * To charge a fixed price for the bundle, set **Dynamic Price** to the “No.” ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-switch-no_32x18.png) ) position. Then, enter the **Price** that you want to charge for the bundle.
  
4.	Because the product is not yet ready to publish, set the **Enable Product** switch to the “No” ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-switch-no_32x18.png) ) position.
5.	Tap `Save` and continue.

  When the product is saved, the Store View chooser appears in the upper-left corner.

6.	Choose the **Store View** where the product is to be available.
 
  ![Choose Store View](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-store-view-choose_thumb_0_0.png)
  
## Step 4: Complete the Basic Settings

1.	If the bundle has Fixed Pricing, set **Tax Class** to one of the following:

  * None
  * Taxable Goods

If the bundle has Dynamic Pricing, the tax is determined for each bundle item.

2.	Take note of the following:

  * The **Quantity** is not available because the value is determined for each bundle item.
  * The **Stock Status** is set by default to “In Stock.”

3.	To determine the weight of the bundle, do one of the following:

  * A **Dynamic Weight** changes to reflect the options chosen by the customer. By default, Dynamic Weight is set to “Yes,” and the Weight field is left blank.
  * To assign a fixed weight to the bundle, set **Dynamic Weight** to the “No.” ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-switch-no_32x18.png) ) position. Then, enter the Weight of the bundle.
 
  ![Dynamic Weight](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-dynamic-weight_thumb_0_0.png)
  
4.	To feature the product in the list of new products, mark the **Set Product as New** checkbox.
5.	Accept the default **Visibility** setting, “Catalog, Search.”
6.	To assign **Categories** to the product, tap the **Select…** box. Then, do either of the following:

  *Choose an existing category:*

  a.	Start typing in the box to find a match.
  b.	Mark the checkbox of each category that is to be assigned.

  *Create a new category:*

  a.	Tap  `New Category` .
  b.	Enter the **Category Name** and choose the **Parent Category** to determine its position in the menu structure.
  c.	Tap  `Create Category` .

7.	Choose the **Country of Manufacture**.
 
  ![Bundle Details](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-details_thumb_0_0.png)

  There might be additional attributes that describe the product. The selection varies attribute set, and you can complete them later.

## Step 5: Add the Bundle Items

1.	Scroll down to the Bundle Items section. Then, set Ship Bundle Items to one of the following:

  * Separately
  * Together
 
  ![Bundle Items](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-items_thumb_0_0.png)
  
2.	Tap  `Add Option` , Then, do the following:
 
  ![Add Bundle Options](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-new-option_thumb_0_0.png)
  
  a.	Enter an **Option Title** to be used field label.
  b.	Set **Input Type** to one of the following:
  
    * Drop-down
    * Radio buttons
    * Checkbox
    * Multiple Select

  c.	To make the field a required entry, mark the **Required** checkbox.
  d.	Tap  `Add Products to Option` . Then, mark the checkbox of each product that you want to include in this option. If there are many products, use the list filters and pagination controls to find the products you need.
  e.	Tap  `Add Selected Products` .
 
  ![Add Selected Products](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-add-products-to-option_thumb_0_0.png)
  
  f.	After the items appear in the Options section choose one to be the Default selection.
  g.	In the Default Quantity column, enter the quantity of each item that is to be added to the bundle when a customer chooses the item.
  h.	To allow customers to change the quantity of a bundle item, select the User Defined option.

  > The quantity can be a preset or user-defined value. However, do not assign the User Defined property to checkbox or multiple-select input types.

  By default, the Default Quantity that is included in a bundle item cannot be changed by the customer. However, the customer can enter the quantity of the item that is to be included in the bundle.

  For example, if the Default Quantity of the Sprite Status Ball is set to 2, and the customer orders 4 of that bundle option, the total number of total balls purchased is 8.

  ![Item Detail](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-item-detail_thumb_0_0.png)
  
3.	Repeat these steps for each item you want to add to the bundle.
4.	To remove any item from the bundle, tap the **Delete** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-delete_22x18.png) ) icon.
5.	When complete, tap  `Save` .

## Step 6: Complete the Product Information

Scroll down and complete the information in the following sections as needed:

 * Content
 * Images and Videos
 * Search Engine Optimization
 * Related Products, Up-Sells, and Cross-Sells
 * Customizable Options
 * Products in Websites
 * Design
 * Gift Options
 
## Step 7: Publish the Product

1.	If you are ready to publish the product in the catalog, set the **Enable Product** switch to the “Yes” ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-switch-yes_32x18.png) ) position.
2.	Do one of the following:

  *Method 1: Save and Preview*
  
  1.	In the upper-right corner, tap `Save`.
  2.	To view the product in your store, choose **Customer View** on the **Admin** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-dropdown-blk_22x18.png) ) menu. The store opens in a new browser tab.
 
  ![Customer View](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-admin-customer-view_thumb_0_0.png)
  
  *Method 2: Save and Close*

  On the **Save** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-dropdown_17x18.png) ) menu, choose **Save & Close**.

  ![Save & Close](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-edit-save-close_thumb_0_0.png)

### Input Controls

CONTROL | DESCRIPTION
-- | --
Drop-down | Displays a drop-down list of options with the product name and price. Only one item can be selected. ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-input-type-drop-down_thumb_0_0.png)
Radio Buttons | Displays a radio button for each option, followed by the product name and price. Only one item can be selected. ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-input-type-radio-buttons_thumb_0_0.png)
Checkbox | Displays a checkbox for each option, followed by the product name and price. Multiple items can be selected. ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-input-type-checkbox_thumb_0_0.png)
Multiple Select | Displays a list of options with the product name and price. To select multiple items, hold down the Ctrl (or Option) key, and click each item. ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-bundle-input-type-multiple-select_thumb_0_0.png)

### Field Descriptions
FIELD | DESCRIPTION
-- | --
SKU | Determines if each item is assigned a variable, dynamic SKU, or if a fixed SKU is used for the bundle. Options include: Fixed / Dynamic.
Weight | Specifies the weight is calculated based on the items selected, or is a fixed weight for the entire bundle. Options include: Fixed / Dynamic.
Price View | Determines if the product price is shown as a range, from the least expensive to the most expensive (Price Range), or with the least expensive shown (As Low As). Options include: Price Range / As Low As.
Ship Bundle Items | Specifies if individual items can be shipped separately.

### THINGS TO REMEMBER

> Customers can “build their own” bundle product.

> Bundle items can be simple or virtual products without custom options.

> The Price View can be set to a price range or to “As Low As.”

> SKU and Weight can be either “Fixed” or “Dynamic.”

> The quantity can be a preset or user-defined value. However, do not assign the User Defined property to checkbox or multiple-select input types.

> Bundle items can be shipped together or separately.