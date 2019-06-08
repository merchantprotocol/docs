Creating Product Attributes
--

Attributes can be created while working on a product, or from the Product Attributes page. The following example shows how to create attributes from the Stores menu.

![New Attribute Properties](https://docs.magento.com/m2/ce/user_guide/Resources/Images/attribute-properties_thumb_0_0.png)

## Step 1: Describe the Basic Properties

1.	On the Admin sidebar, tap **Stores**. Then under Attributes, choose **Product**.
2.	Tap  `Add New Attribute` .
![Attribute Properties](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-add-attribute-properties-flavor_thumb_0_0.png)
3.	Under Attribute Properties, enter a **Default Label** to identify the attribute.
4.	Set **Catalog Input Type for Store Owner** to the type in input control to be used for data entry.
5.	For Dropdown and Multiple Select input types, do the following:

  a.	Under **Manage Options**, tap  `Add Option` .
  b.	Enter the first value that you want to appear in the list. You can enter one value for the Admin, and a translation of the value for each store view. If you have only one store view, you can enter only the Admin value and it will be used for the storefront as well.
  c.	Tap  `Add Option`  and repeat the previous step for each option that you want to include in the list.
  d.	Select **Is Default** to use the option as the default value.

6.	If you want to require the customer to choose an option before the product can be purchased, set **Values Required** to “Yes.”
![Manage Options](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-add-values-flavors_thumb_0_0.png)

## Step 2: Describe the Advanced Properties (if needed)

1.	Enter a unique **Attribute Code** in lowercase characters, and without spaces.
![Advanced Attribute Properties](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-advanced-attribute-properties_thumb_0_0.png)
2.	Set **Scope** to indicate where in your store hierarchy the attribute can be used.
3.	If you want to prevent duplicate values from being entered, set **Unique Value** to “Yes.”
4.	To run a validity test of any data entered into a text field, set **Input Validation for Store Owner** to the type of data that the field should contain. This field is not available for input types with values that are selected. The test can validate any of the following:

  * Decimal Number
  * Integer Number
  * Email
  * URL
  * Letters
  * Letters (a-z, A-Z) or Numbers (0-9)
 
  ![Input Validation](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-input-validation_thumb_0_0.png)
  
5.	To add this attribute to the product grid, set the following options to "Yes."

-- | --
Add to Column Options | Includes the attribute as a column in the Products grid.
Use in Filter Options | Adds a filter control to the column header in the Products grid.

## Step 3: Enter the Field Label

1.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Manage titles** section.
2.	Enter a **Title** to be used as a label for the field. If your store is available in different languages, you can enter a translated title for each view.
 ![Manage Titles](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-add-manage-titles_thumb_0_0.png)
 
## Step 4: Describe the Storefront Properties

1.	In the panel on the left, choose **Storefront Properties**.
2.	If the attribute is to be available for search, set **Use in Search** to “Yes.”
3.	To include the attribute in Product Compare, set **Comparable on Storefront** to “Yes.”
4.	For dropdown, multiple select and price fields, do the following:

  a.	To use the attribute as a filter in layered navigation, set **Use in Layered Navigation** to “Yes.”
  b.	to use the attribute in layered navigation on search results pages, set **Use in Search Results Layered Navigation** to “Yes,”
  c.	In the **Position** field, enter a number to indicate the relative position of the attribute in the layered navigation block.

5.	To use the attribute in price rules, set **Use for Promo Rule Conditions** to “Yes,”
6.	To allow the text to be formatted with HTML, set **Allow HTML Tags** on Frontend to “Yes.” This setting makes the WYSIWYG editor available for the field.

  To include the attribute in catalog page listings, set **Visible on Catalog Pages** on Storefront to “Yes.”

7.	Complete the following settings if supported by your theme:

  a.	To include the attribute on the product detail page, set Visible on **Catalog Pages** on Storefront to “Yes.”
  b.	To include the attribute in product listings, set Used in **Product Listing** to “Yes.”
  c.	To use attribute as a sort parameter for product listings, set **Used for Sorting in Product Listing** to “Yes.”

8.	When complete, tap  `Save Attribute` .
 
![Storefront Properties](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-add-storefront-properties_thumb_0_0.png)

## Attributes for Configurable Products

Any attribute that is used as a drop-down list of options for a configurable product must have the following properties:

PROPERTY | VALUE
-- | --
Catalog Input Type for Store Owner | Dropdown
Scope | Global