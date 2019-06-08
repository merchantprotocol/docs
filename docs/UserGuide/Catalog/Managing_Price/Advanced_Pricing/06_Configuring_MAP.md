Configuring MAP
--

Your store’s MAP settings can be applied to all products in your catalog, or configured for specific products. When Minimum Advertised Price is enabled globally, all product prices in the storefront are hidden from view. There are a variety of configuration options that you can use to remain in compliance with the terms of your agreement with the manufacturer, while still offering your customers a better price.

![Actual Price Appears “On Gesture”](https://docs.magento.com/m2/ce/user_guide/Resources/Images/storefront-msrp-on-gesture_thumb_0_0.png)

On the global level, you can enable or disable MAP, apply it to all products, define how the actual price is displayed, and edit the text of the related messages and information tips that appear in the store.

When MAP is enabled, the product-level MAP settings become available. You can apply MAP to an individual product by entering the MSRP, and choosing how you want the actual price to appear in the store. Product-level MAP settings override the global MAP settings.

![Click for Price](https://docs.magento.com/m2/ce/user_guide/Resources/Images/storefront-price-map_thumb_0_0.png)

## To configure MAP:

1.	On the Admin sidebar, tap **Stores**. Then under **Settings**, choose **Configuration**.
2.	If applicable, in the upper-right corner, set **Store View** to the view where the configuration applies.
3.	In the panel on the left under **Sales**, choose **Sales**.
4.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the Minimum Advertised Price section.
5.	If necessary, set **Enable MAP** to “Yes.” Then, do the following:
 
![Minimum Advertised Price](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-sales-sales-minimum-advertised-price_thumb_0_0.png)

### Method 1: Configure MAP for All Products:

1.	To determine when and where you want the actual price to be visible to customers, do the following:

  a.	To change the default value, clear the **Use system value** checkbox.

  b.	Set **Display Actual Price** to one of the following:
  
   * In Cart
   * Before Order Confirmation
   * On Gesture (on click)
   
2.	Enter the text that you want to appear in the **Default Popup Text Message**.
3.	Enter any additional explanation that you want to appear in the **Default “What’s This” Text Message**.
4.	When complete, tap `Save Config` .

### Method 2: Configure MAP for a Single Product

1.	On the Admin sidebar, tap **Products**. Then under **Inventory**, choose **Catalog**.
2.	Open the product in **Edit** mode.
3.	In the panel on the left under **Advanced Settings**, choose **Advanced Pricing**. Then, do the following:
 
  ![Manufacturer’s Suggested Retail Price](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-price-msrp_thumb_0_0.png)

  a.	Enter the **Manufacturer’s Suggested Retail Price**.
  
  In this example, the product price is $54.00, and the MSRP is 59.95.

  b.	Set **Display Actual Price** to one of the following:
  
VALUE | DESCRIPTION
-- | --
Use config | (Default) Applies the MAP configuration setting.
On Gesture | Displays the actual product price in a popup when the customer clicks the “Click for price” or “What’s this?” link.
In Cart | Displays the actual product price in the shopping cart.
Before Order Confirmation | Displays the actual product price at the end of the checkout process, just before the order is confirmed.

> The Manufacturer’s Suggested Retail Price and Display Actual Price fields appear only when Minimum Advertised Price is enabled in the configuration.

6.	When complete, tap `Done`. Then, tap `Save`.