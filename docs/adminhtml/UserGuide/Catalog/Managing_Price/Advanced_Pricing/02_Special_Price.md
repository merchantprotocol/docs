Special Price
--

A special price can be offered for a designated period of time. During the specified time period, the special price appears instead of the regular price, followed by a notation that shows the regular price.

![Special Price on Product Page](https://docs.magento.com/m2/ce/user_guide/Resources/Images/storefront-price-special_thumb_0_0.png)

To assign a special price to multiple products, such as multiple variations of a configurable product, use the Actions control+ as described in Method 2.

## Method 1: Apply Special Price to an Individual Product

1.	Open the product in edit mode.

  a.	Scroll down to the **Price** field, and click **Advanced Pricing**. Then, enter the amount of the **Special Price**.

  b.	Use the **Calendar** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-calendar_21x18.png) ) to choose the **Start Date** and **End Date** for the special price promotion.
  
  The special price goes into effect immediately after midnight at the beginning of the start date (00:01), and continues until just before midnight (23:59) on the day before the end date.

![Special Pricing Settings](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-price-special_thumb_0_0.png)

2.	When complete, tap `Done`. Then, tap `Save`.

  In the storefront, the Special price should appear in both catalog listing, and on the product page.

## Method 2: Apply Special Price to Multiple Products

The following example shows how to assign the same special price to multiple product variations of a configurable product.

1.	On the Admin sidebar, tap **Catalog**. Then, choose **Products**.
2.	Tap `Filters`. Then, do the following:

  a.	Enter the **Name** of the configurable product.

  b.	Set **Type** to “Simple Product.”
 
![Filters](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-price-special-filter_thumb_0_0.png)

  c.	Tap `Apply Filters`.

  The grid lists all simple products that are associated as variations of the configurable product.

![Product Variations](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-price-special-filter-grid_thumb_0_0.png)

3.	If you want to assign the same special price to all of the products, set the control in the header of the first column to “Select All.” Otherwise, mark the checkbox of each product that you want to include.
4.	Set the **Actions** control to “Update attributes.”
 
![Update Attributes](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-price-special-action-update-attributes_thumb_0_0.png)

5.	Scroll down to the **Special Price** field. Then, do the following:

  a.	Mark the **Change** checkbox below the **Special Price** field. Then, enter the special price that you want to offer.

  b.	Mark the **Change** checkbox below the **Special Price From Date** field. Click the **Calendar** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-calendar_21x18.png) ) , and choose the first date of the special price promotion.
  
  The special price goes into effect immediately after midnight at the beginning of the start date (00:01), and continues until just before midnight (23:59) on the day before the end date.

  c.	Mark the **Change** checkbox below the **Special Price To Date** field.  Click the **Calendar** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-calendar_21x18.png) ) , and choose the last date of the special price promotion.
 
![Special Price Fields](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-price-special-action-update-attributes-fields_thumb_0_0.png)

6.	When complete, click `Save`.

  A message indicates how many records were updated with the special price.

  The special price becomes available in the store on the date specified, and appears in catalog listings as well as on the product page. For a configurable product, the regular price also appears on the product page when the options are chosen.

![Special Price for Configurable Product](https://docs.magento.com/m2/ce/user_guide/Resources/Images/storefront-special-price-configurable-product-detail_thumb_0_0.png)

## Troubleshooting

If the special price doesn’t appear correctly in the storefront on both the catalog listing and product pages, do the following:

1.	Clear your browser cache.
2.	On the Admin sidebar, tap **System**. Then, choose **Cache Management**.
3.	Tap `Flush Magento Cache`.