Downloadable Product
--

A downloadable product can be anything that you can deliver as a file, such as an eBook, music, video, software application, or update. You can offer an album for sale, and sell each song individually. You can also use a downloadable product to deliver an electronic version of your product catalog.

Because the actual download doesn’t become available until after the purchase, you can provide samples, such as an excerpt from a book, a clip from an audio file, or a trailer from a video that the customer can try before purchasing the product. The files that you make available for download can be either uploaded to your server, or from a different server.

![Downloadable Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/storefront-product-downloadable_thumb_0_0.png)

Downloadable products can be configured to require that the customer log in to an account to receive the link, or can be sent by email and shared with others. The status of the order before the download becomes available, default values, and other delivery options are set in the configuration. To learn more, see: Configuring Download Options.

The following instructions take you through the process of creating a downloadable product using a product template, required fields, and basic settings. Each required field is marked with a red asterisk (*). When you finish the basics, you can complete the advanced settings and other settings as needed.

> Downloadable file names can include letters and numbers. Either a dash or underscore character can be used to represent a space between words. Any invalid characters in the file name are replaced with an underscore.

## Step 1: Choose the Product Type

1.	On the Admin sidebar, tap **Products**. Then, choose **Catalog**.
2.	In the upper-right corner on the **Add Product** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-save-menu_17x18.png) ) menu, choose **Downloadable Product**.
 
![Add Downloadable Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/21product-add-downloadable_thumb_0_0.png)

## Step 2: Choose the Attribute Set

The sample data includes an attribute set called “Downloadable” that has special fields for downloadable products. You can use an existing template, or create another before the product is saved.

To choose the attribute set that is used as a template for the product, do one of the following:

* In the **Search** box, enter the name of the attribute set.
* In the list, choose the “Downloadable” attribute set.

The form is updated to reflect the change.

![Choose Attribute Set](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-choose-attribute-set-downloadable_thumb_0_0.png)

## Step 3: Complete the Required Settings

1.	Enter the product **Product Name**.
2.	Accept the default **SKU** that is based on the product name, or enter another.
3.	Enter the product **Price**.
4.	Because the product is not yet ready to publish, set the **Enable Product** switch to the “No” ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-switch-no_32x18.png) ) position.
5.	Tap  `Save`  and continue.

  When the product is saved, the Store View chooser appears in the upper-left corner.

6.	Choose the Store View where the product is to be available.
 
![Choose Store View](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-create-store-view-choose_thumb_0_0.png)

## Step 4: Complete the Basic Settings

1.	Set **Tax Class** to one of the following:

* None
* Taxable Goods

2.	Enter the **Quantity** of the product that is currently in stock. For Multi Source merchants with Inventory Management, see the expanded instructions.

  Take note of the following:

  * By default, Stock Status is set to “Out of Stock.”
  * The Weight field is not used, because downloadable products are not shipped.
  
  *Assign Sources and Quantities (Inventory Management)**

  For Multi Source merchants using Inventory Management, scroll down to the Sources section and assign sources and quantities:

  1.	To add a source, tap **Assign Sources**. The Assign Sources page displays.
  2.	Browse or search for a source you want to add. Select the checkbox next to the source(s) you want to add for the product.
  ![Assign sources to the product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-product-assign-sources_thumb_0_0.png)
  3.	Tap **Done** to add the sources.
  4.	To change settings and quantities per assigned source, do the following:
  
    a.	Set **Source Item Status** to In Stock.
    b.	Enter an amount update the **Qty** for on-hand stock.
    c.	To set a notification for inventory quantities, do one of the following:

-- | --
Custom Notify Quantity | Clear the Notify Quantity Use Default checkbox and enter an amount in Notify Quantity.
Default Notify Quantity | Select the Notify Quantity Use Default checkbox. Magento checks and uses the setting in Advanced Inventory or global Store configuration.

    ![Update Product Quantities per Source](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-product-quantities_thumb_0_0.png)

5.	Accept the default **Visibility** setting, “Catalog, Search.”
6.	To feature the product in the list of new products, mark the **Set Product as New** checkbox.
7.	To assign **Categories** to the product, tap the **Select…** box. Then, do either of the following:

  *Choose an existing category:*

  a.	Start typing in the box to find a match.
  b.	Mark the checkbox of each category that is to be assigned.

  *Create a new category:*

  a.	Tap  `New Category` .
  b.	Enter the **Category Name** and choose the **Parent Category** to determine its position in the menu structure.
  c.	Tap  `Create Category` .

8.	Set **Format** to one of the following:

  * Download
  * DVD

  If necessary, you can edit the attribute to add more values.

  ![Product Details](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-details-downloadable_thumb_0_0.png)
  
  There might be additional attributes that describe the product. The selection varies attribute set, and you can complete them later.

## Step 5: Complete the Downloadable Information

1.	Scroll down to **Downloadable Information**, and expand  the section. Then, mark the **Is this downloadable product?** checkbox.

The Downloadable Information section has two parts. The first part describes each download link, and the second part describes each sample file. The default value for many of these options can be set in the configuration.

![Downloadable Information](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-downloadable-information_thumb_0_0.png)


  *Part 1: Complete the Links*

  1.	In the Links section, enter the **Title** that you want to use as a heading for the download links.
  2.	If applicable, mark the **Links can be purchased separately** checkbox.
  3.	Tap `Add Link`. Then, do the following:

    a.	Enter the Title and Price of the download.
    b.	For both File and Sample files, choose one of the following methods of distribution for the downloads:

-- | --
Upload File | To upload the the distribution file to the server, choose “Upload File.” Then, browse to the file, and select it for upload.
URL | To access the distribution file from a URL, choose “URL”  Then, enter the full URL to the download file.

    c.	Set Shareable to one of the following:

-- | --
No | Requires customers to log in to their accounts to access the download link.
Yes | Sends the link by email, which customers can share with others.
Use Config | Uses the method that is specified in the Dowloadable Product Options configuration.

    d.	Do one of the following:

      * To limit downloads per customer, enter the number of **Max. Downloads**.
      * To allow unlimited downloads, mark the **Unlimited** checkbox.

      ![Link Detail](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-downloadable-link-detail_thumb_0_0.png)
      
  4.	To add another link, tap Add Link. Then, repeat these steps.
  
  *Part 2: Complete the Samples*
  
  1.	In the Samples section, enter the **Title** that you want to use as a heading for the samples.
  2.	To complete the information for each sample, tap  `Add Link` .
 
  ![Samples](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-downloadable-samples_thumb_0_0.png)
  
  3.	Complete the link detail as follows:

    a.	Enter the Title of the individual sample.
    b.	Choose one of the following distribution methods:

-- | --
Upload File | To upload the the sample distribution file to the server, choose “Upload File.” Then, browse to the file, and select it for upload.
URL | To access the sample distribution file from a URL, choose “URL”  Then, enter the full URL to the download file.

    c.	To add another sample, tap  Add Link , and repeat these steps.
    d.	To change the order of the samples, grab the Change Order (  ) icon, and drag the sample to a new position.

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
  
  1.	In the upper-right corner, tap Save.
  2.	To view the product in your store, choose **Customer View** on the **Admin** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-dropdown-blk_22x18.png) ) menu. The store opens in a new browser tab.
 
  ![Customer View](https://docs.magento.com/m2/ce/user_guide/Resources/Images/admin-customer-view_thumb_0_0.png)
  
  *Method 2: Save and Close*
  
  On the Save ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-dropdown_17x18.png) ) menu, choose Save & Close.

  ![Save & Close](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-edit-save-close_thumb_0_0.png)
  
## THINGS TO REMEMBER

> Downloadable products can be uploaded to the server, or linked to from another server on the Internet.

> You can determine the number of times a customer can download a product.

> Customers who purchase a downloadable product can be required to log in before going through checkout.

> The delivery of a downloadable product can be made when the order is in either a “Pending” or “Invoiced” state.