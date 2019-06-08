Advanced Pricing
--

The Advanced Pricing settings define the conditions required for special pricing that is available for a specific customer group. Advanced Pricing can be applied to simple, virtual, downloadable, and bundle products. To apply discounted pricing to other product types, use a catalog price rule. To learn more, see: Price Scope.

Advanced pricing data is synchronized with product pages. For example, if you update a tier price quantity, the system updates the value on the product page.

![Advanced Pricing](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-pricing-advanced-link_thumb_0_0.png)

## To display the Advanced Pricing options:

1.	Open the product in edit mode.
2.	Under the **Price** field, click **Advanced Pricing**.
3.	Follow the instructions for the type of advanced pricing that is needed.

  * Group Price
  * Special Price
  * Tier Price
  * Minimum Advertised Price
 
![Advanced Pricing](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-pricing-advanced_thumb_0_0.png)

## Field Descriptions

FIELD | DESCRIPTION
-- | --
Special Price | Offers a discounted price during a specified time period. When a special price is available, the retail price is crossed out and the special price appears below in large, bold text. **From** Sets the first date the Special Price is available. You can either enter the date or select it from the calendar. **To** Sets the last date the Special Price is available. You can either enter the date or select it from the calendar.
Cost | The actual cost of the item.
Manufacturer's Suggested Retail Price | The manufacturer's suggested retail price (MSRP) for the product.

## Customer Group Price

Sets up promotional and tier prices for specific customer groups for the current website. Options include:

FIELD | DESCRIPTION
-- | --
Website | Identifies the website where the group price rule applies. This option appears only if the installation has multiple websites.
Customer Group | (Required) Identifies the customer group that qualifies to receive the discount price. When a value in a group or catalog field is changed, the corresponding custom price row that matched the previous setting is deleted from the shared catalog Options: **ALL GROUPS** Applies the rule to all customer groups. **NOT LOGGED IN** Applies the rule guests and customers who are not logged in to their accounts.
Quantity | Specifies the quantity that is required to receive a tier price.
Price | (Required) Specifies a fixed or discount product price for members of the customer group, within the specific website. Options: Fixed / Discount **Fixed** (Default) The discount price is entered as a fixed decimal value. For example, enter “9.99” as the discount price. **Discount** The discount price is entered as a percentage (%) of the base product price. For example, enter “10” for a 10% discount.
![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-trashcan2.png) | Deletes the current rule.
`Add` | Inserts an additional row for a new rule

## Display Actual Price

Determines where the actual price of the product is visible to the customer. Options:

FIELD | DESCRIPTION
-- | --
Use Config | Uses the current configuration setting for the price display.
On Gesture | Displays the actual product price in a popup, in response to the "Click for price" or What's this?" link.
In Cart | Displays the actual product price in the shopping cart.
Before Order Confirmation | Displays the actual product price at the end of the checkout process, just before the order is submitted.