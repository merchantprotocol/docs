Tier Price
--

Tier pricing lets you offer a quantity discount from a product listing or product page in the storefront. The discount can be applied to a specific store view or customer group.

If you have many products to update, it is most efficient to import the tier price changes, rather than enter them individually. To learn more, see: Importing Tier Prices.

![Tier Price on Product Page](https://docs.magento.com/m2/ce/user_guide/Resources/Images/storefront-tier-pricing-water-bottle_thumb_0_0.png)

The product page calculates the quantity discount and displays a message such as:

```
Buy 6 for $5.95 each and save 15%
```

The prices in the storefront take precedence from the highest to the lowest quantity. Therefore, if you have a tier for the quantity 5 and one for the quantity 10, and a customer adds 5, 6, 7, 8 or 9 items to the shopping cart, the customer receives the discounted price that you specified for the quantity 5 tier. As soon as the customer adds the 10th item, the discounted price specified for the quantity 10 tier supersedes the tier for a quantity of 5, and discounted price for 10 applies.

## To set up a tier price:

1.	Open the product in edit mode.
2.	Below the **Price** field, click **Advanced Pricing**.
3.	In the **Tier Price** section, tap  `Add`. If you’re creating a tier of several prices, tap **Add** for each additional level, so you can work all tiers at the same time. Each tier in the group has the same website and customer group, but a different quantity and price.
4.	For each tier, do the following:

  a.	If your store has multiple websites, choose the **Website** where the tier pricing applies.

  b.	If necessary, choose the **Customer Group** that is to receive the discount.

  c.	In the **Qty** field, enter the quantity that must be ordered to receive the discount.

  d.	Use one of the following methods to enter the tier prices:

  **Method 1: Enter Price as Fixed Amount**
  
  1.	Set **Price** to “Fixed”.

  2.	In the next field, enter the adjusted price for one unit at that tier.
 
  ![Tier Price as a Fixed Amount](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-price-tier-fixed_thumb_0_0.png)
  
  **Method 2: Enter Price as Percentage**
  
  1.	Set **Price** to “Discount”.

  2.	In the next field, enter the discounted price as a percentage off the base price of the product. For example, for a 15 percent discount, enter the number 15. (The price is saved with two decimal positions, such as “15.00”.)
 
  ![Tier Price as a Percentage](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-price-tier-discount_thumb_0_0.png)
  
5.	To add another set of tier pricing for a different website or customer group, repeat the process.
6.	When complete, tap `Done`. Then, tap `Save`.