Creating Swatches
--

Swatches can be defined as a component of the color attribute, or set up locally for a specific product and uploaded as product images.

In the following examples, the Sylvia Capris are available in specific values of red, green, and blue. Because the swatches were taken from the product image, each is a true representation of the color. The color attribute is used to manage the information for all product colors and swatches.

## Step 1: Create the Swatches

Use either of the following methods to create swatches for your products:

### Method 1: Add a Color Swatch

1.	To capture the true color of a product, open the image in a photo editor and use the eye dropper tool to identify the exact color. Then, take note of the equivalent hexadecimal value.
![Hexadecimal Color Values](https://docs.magento.com/m2/ce/user_guide/Resources/Images/swatch-hex-values_thumb_0_0.png)
2.	On the Admin sidebar, tap **Stores**. Then under Attributes, choose **Product**.
3.	In the grid, open the **color** attribute in edit mode.
4.	Verify that **Catalog Input Type for Store Owner** is set to “Visual Swatch.”
5.	Under **Manage Swatch** (values of your attribute), tap `Add Swatch`. Then, do the following:
 
  ![Manage Swatch Values](https://docs.magento.com/m2/ce/user_guide/Resources/Images/attribute-color-manage-swatch-values_thumb_0_0.png)
  
  a.	In the Swatch column, tap the new swatch to display the menu. Then, select Choose a color.
 
  ![Choose a Color](https://docs.magento.com/m2/ce/user_guide/Resources/Images/attribute-color-swatch-menu_thumb_0_0.png)
  
  b.	In the color picker, place your cursor in the # field, and press the Backspace key to delete the current value. Then, enter the six-character hexadecimal value of the new color..

  ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/attribute-swatch-color-picker-hex-value_thumb_0_0.png)

  c.	To save the swatch, tap the Color Wheel (  ) in the lower-right corner of the color picker.

  d.	In the Admin column, enter a label to describe the color to the store administrator. Then if applicable, enter the translation of the color for each each language supported. In the following example, we include the SKU for reference in the Admin label because the colors are used only for a specific product. You can include a space or underscore in the label, but not a hyphen.

  e.	In the Is Default column, select the swatch that is to be the default option.

  f.	To change the order of the swatches, simply drag each swatch into position.
 
  ![Swatch Labels](https://docs.magento.com/m2/ce/user_guide/Resources/Images/attribute-swatch-labels_thumb_0_0.png)
  
6.	When complete, tap Save Attribute. Then when prompted, refresh the cache.
7.	The last step is to open each product in Edit mode, and update the Color attribute with the correct swatch. To update multiple products at the same time, follow the steps below.

### Method 2: Upload a Swatch Image

1.	To capture an image for a swatch, open the product image in a photo editor, and save a square area of the image that depicts the color, pattern, or texture. Then repeat for each variation of the product. The size and dimensions of the swatch is determined by the theme. As a general rule, saving an image as a square helps to preserve the aspect ratio of a pattern.
 
![Swatch Images](https://docs.magento.com/m2/ce/user_guide/Resources/Images/swatch-samples_thumb_0_0.png)

2.	On the Admin sidebar, tap **Stores**. Then under Attributes, choose **Product**.
3.	In the grid, open the **color** attribute in edit mode.
4.	Verify that **Catalog Input Type for Store Owner** is set to “Visual Swatch.”
5.	Under **Manage Swatch** (values of your attribute), tap `Add Swatch`. Then, do the following:

  a.	In the Swatch column, tap the new swatch to display the menu. Then, choose Upload a file.
 
  ![Upload a File](https://docs.magento.com/m2/ce/user_guide/Resources/Images/attribute-swatch-add-upload-file_thumb_0_0.png)
  
  b.	Navigate to the swatch file that you prepared, and choose the file to upload.

  c.	Repeat these steps for each swatch image.

  d.	Enter the labels for the Admin and Storefront. In this example, we include the SKU in the admin label for reference because these colors are used only for a specific product. You can include a space or underscore in the label, but not a hyphen.
 
  ![Enter Labels](https://docs.magento.com/m2/ce/user_guide/Resources/Images/swatch-upload_thumb_0_0.png)
  
6.	When complete, tap `Save Attribute`. Then when prompted, refresh the cache.
7.	The last step is to open each product in Edit mode, and update the Color attribute with the correct swatch. To update multiple products at the same time, follow the steps below.

## Step 2: Update Your Products

1.	On the Admin sidebar, tap **Products**. Then under Inventory, choose **Catalog**.
2.	Filter the list by Name or SKU to include only the applicable products. The following example filters the list on a partial product name.
 ![Filters](https://docs.magento.com/m2/ce/user_guide/Resources/Images/swatch-apply-filter-product_thumb_0_0.png)
3.	In the grid, mark the checkbox of each product to which the swatch applies. In this example, all blue capris are selected.  Then, set the Actions control to “Update Attributes.”
![Update Attributes](https://docs.magento.com/m2/ce/user_guide/Resources/Images/swatch-apply-update-attributes_thumb_0_0.png)
4.	Scroll down to the Colorattribute, and mark the Change checkbox.
![Change](https://docs.magento.com/m2/ce/user_guide/Resources/Images/swatch-update-attributes-choose-color_thumb_0_0.png)
5.	Choose the swatch that applies to the selected products, and tap `Save`. Then when prompted, refresh the cache.
![Swatch in Storefront](https://docs.magento.com/m2/ce/user_guide/Resources/Images/storefront-swatch-blue-schmear_thumb_0_0.png)