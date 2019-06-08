Customizable Options
--

Adding customizable options to a product is an easy way to offer customers a selection of options with a variety of text, selection, and date input types. Customizable options are a good solution if your inventory needs are simple. However, because they are based on variations of a single SKU, they cannot be used to manage stock. If you have multiple products with the same options, you can set up one product, and import the options to the other products.

## To create customizable options:

1.	Open the product in edit mode.
2.	Scroll down and expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the Customizable Options section. Then, tap Add Option.
![Customizable Options](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-customizable-options_thumb_0_0.png)
3.	In the upper-left corner, tap  `New Option` . Then, do the following:

  a.	In the **Option Title** field, enter a name for the option.
  b.	Set the **Option Type** for data entry.
  c.	If the option is not required to purchase the product, clear the **Required** checkbox.
  
  ![New Option](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-customizable-options-new-option_thumb_0_0.png)

4.	Tap `Add New Row` . Then, complete the following:
![Add Value](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-customizable-options-add-values_thumb_0_0.png)
a.	In the **Title** field, enter a name for this option.
b.	In the **Price** field, enter any markup or markdown from the base product price that applies to this option.
c.	Set **Price Type** to one of the following:

-- | --
Fixed | The price of the variation differs from the price of the base product by a fixed monetary amount, such as $1.
Percentage | The price of the variation differs from the price of the base product by a percentage, such as 10%.

  d.	Enter a SKU for the option. The option SKU is a suffix that is added to the product SKU.
  e.	To change the order of the options, tap the Change Order icon , and drag the option to a new position in the list.

  ![Change Order of Options](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-customizable-options-move_thumb_0_0.png)
  
  f.	Repeat this step for each option to be added.

5.	When complete, tap  `Save` .

### To import customizable options:

1.	In the Customizable Options section, tap `Import Options`.

![Customizable Options](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-customizable-options_thumb_0_0.png)

2.	All products with customizable options appear in the grid.
3.	In the list, mark the checkbox of the product with the options that you want to import.
4.	Tap  `Import` .
5.	When complete, you can continue to add more custom options, or tap `Save and Close`.


### Input Controls

INPUT TYPE | DESCRIPTION
 -- | --
TEXT | | 
 | Field | A single line input field for text.
 | Area | A multiple-line input box for paragraphs of text. You can use the WYSIWYG Editor to format the text with HTML tags, or type HTML directly into the text area.
FILE | |
 | File | A file to be uploaded by the customer.
SELECT | |
 | Drop-down | A drop-down list of options. Only one item can be selected at a time.
 | Radio Buttons | A set of options that allows only one to be selected at a time.
 | Checkbox | A checkbox is a variation of a yes/no option. If the product has more than one checkbox, multiple selections can be made at the same time.
 | Multiple Select | A drop-down list of options that accepts multiple selections. To select multiple options, hold down the Ctrl (PC) or Command (Mac) key.
DATE | | 
Date | Date | An input field for a date value. The date can be typed directly into the field, selected from a listm or calendar. The method of input used and format of the date is determined by the Date & Time Custom Options configuration.
 | Date & Time | An input field for date and time values.
 | Time | An input field for a time value.