Default Field Values
--

To save time when creating products, the default value of several product fields references values from another field. You can either accept the default value, or enter another. The following fields have automatically generated default values:

FIELD | DESCRIPTION
-- | --
SKU | Based on product Name.
Meta Title | Based on product Name.
Meta Keywords | Based on product Name.
Meta Description | Based on product Name and Description.

The placeholders that represent the value of another field are enclosed in double-curly braces. Any attribute code that is included in the product attribute set can be used as a placeholder.

 
![Product Fields Auto-Generation](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-product-fields-auto-generation_thumb_0_0.png)

### To edit the placeholder value:

1.	On the Admin sidebar, tap Stores. Then under Settings, choose Configuration.

2.	In the panel on the left under Catalog, choose Catalog.

3.	Expand the Product Fields Auto-Generation section. Then, make any changes needed to the placeholder values.

For example, if there’s a specific keyword that you want to include for every product, or a phrase that you want to include in every meta description, you can type the value directly into the appropriate field.

If you want to keep the existing placeholder values, be careful to preserve the double curly braces that enclose each markup tag.

4.	When complete, tap  Save Config .

### Common Placeholders

{{color}}

{{country_of_manufacture}}

{{description}}

{{gender}}

{{material}}

{{name}}

{{short_description}}

{{size}}

{{sku}}