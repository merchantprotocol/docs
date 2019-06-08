Adding an Attribute to a Product
--

Although attributes are managed primarily from the Stores menu, you can also add new attributes “on the fly” while working on a product. You can choose from the list of existing attributes, or create a new attribute. The new attribute is added to the attribute set upon which the product is based.

![Add Attribute](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-add_thumb_0_0.png)

## Step 1: Add a New Attribute

1.	Open the product in edit mode. Then in the upper-right corner, tap `Add Attribute`.
 
![New Attribute](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-add-select_thumb_0_0.png)

2.	To add an existing attribute to the product, use the filter controls to find the attribute in the grid. Then, do the following:

  a.	Mark the checkbox in the first column of each attribute to be added.
  b.	Tap `Add Selected`.

3.	To define a new attribute, tap `Create New Attribute`, and complete the following steps.

## Step 2: Describe the Basic Properties

1.	Under **Attribute Properties**, enter a **Default Label** to identify the attribute.

![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-add-new_thumb_0_0.png)

2.	Set **Catalog Input Type for Store Owner** to the type in input control to be used for data entry.

  If the attribute is used for a configurable product, choose “Dropdown.”  Then, set **Required** to “Yes.”

3.	For Dropdown and Multiple Select input types, do the following:

  a.	Under **Values**, tap  `Add Value` .
  b.	Enter the first value that you want to appear in the list. You can enter one value for the Admin, and a translation of the value for each store view. If you have only one store view, you can enter only the Admin value and it will be used for the storefront as well.
  c.	Tap  `Add Value`  and repeat the previous step for each option that you want to include in the list.
  d.	Select **Is Default** to use the option as the default value.
  ![Values](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-add-values-flavors_thumb_0_0.png)

4.	If you want to require the customer to choose an option before the product can be purchased, set **Required** to “Yes.”

## Step 3: Describe the Advanced Properties (if needed)

1.	Enter a unique **Attribute Code** in lowercase characters, and without spaces.
 
![Advanced Attribute Properties](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-advanced-attribute-properties_thumb_0_0.png)

2.	Set **Scope** to indicate where in your store hierarchy the attribute can be used.

  If the attribute is used for a configurable product, choose “Global.”

3.	If this attribute applies only to this product, set Unique Value to “Yes.”
4.	To run a validity test of any data entered into a text field, set **Input Validation for Store Owner** to the type of data that the field should contain. This field is not available for input types with values that are selected. Input validation can be used for any of the following:

 * Decimal Number
 * Integer Number
 * Email
 * URL
 * Letters
 * Letters (a-z, A-Z) or Numbers (0-9)
 
![Input Validation](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-input-validation_thumb_0_0.png)

5.	If you want to be able to include the attribute as a column in the Products grid, set **Add to Column Options** to “Yes.”
6.	If you want to be able to filter the Products grid by this column, set **Use in Filter Options** to “Yes.”

## Step 4: Enter the Field Label

1.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the Manage titles section.
2.	Enter a **Title** to be used as a label for the field. If your store is available in different languages, you can enter a translated title for each view.
 
![Manage Titles](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-add-manage-titles_thumb_0_0.png)

## Step 5: Describe the Storefront Properties

1.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Storefront Properties** section. Then, do the following:
![Storefront Properties](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-attribute-add-storefront-properties_thumb_0_0.png)

  a.	To make the attribute available for search, set **Use in Search** to “Yes.”
  b.	To include the attribute in **Product Compare**, set Comparable on Storefront to “Yes.”
  c.	To include dropdown, multiple select, or price attributes in layered navigation, set **Use in Search Results Layered Navigation** to one of the following:

-- | --
Filterable (with results) | Layered navigation includes only those filters for which matching products can be found. Any attribute value that already applies to all products shown in the list does not appear as an available filter. Attribute values with a count of zero (0) product matches are also omitted from the list of available filters. The filtered list of products includes only those that match the filter. The products list is updated only if the selected filter(s) change what is currently shown.
Filterable (no results) | Layered navigation includes filters for all available attribute values and their product counts, including those with zero (0) product matches. If the attribute value is a swatch, the value appears as a filter, but is crossed out.

  d.	To use in layered navigation on search results pages, set **Use in Search Results Navigation** to “Yes.”
  e.	In the **Position** field, enter a number to indicate the relative position of the attribute in the layered navigation block.
  f.	To use the attribute in price rules, set **Use for Promo Rule Conditions** to “Yes.”
  g.	To allow the text to be formatted with HTML, set **Allow HTML Tags on Storefront** to “Yes.”

  This setting makes the WYSIWYG editor available when editing the field.

  h.	To include the attribute on the product page, set **Visible on Catalog Pages on Storefront** to “Yes.”

2.	Complete the following settings as supported by your theme:

  a.	To include the attribute in product listings, set **Used in Product Listing** to “Yes.”
  b.	To use attribute as a sort parameter for product listings, set **Used for Sorting in Product Listing** to “Yes.”
  
3.	When complete, tap  `Save Attribute` .