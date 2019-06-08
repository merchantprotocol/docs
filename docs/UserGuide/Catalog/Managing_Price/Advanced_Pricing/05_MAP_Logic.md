MAP Logic
--

For products with prices that depend on a selected options, (such as custom options, or simple products with their own SKUs and stock management), the following logic is applied, according to the product type and price setting. The actual price is used by order management and customer management tools, and reports.

## Using MAP with Product Types
PRODUCT TYPE | DESCRIPTION
-- | --
Simple, Virtual | The actual price does not automatically appear on catalog list and product pages, but is included only according to the Display Actual Price setting. Custom option prices appear normally.
Grouped | The prices of associated simple products do not automatically appear on catalog list and product pages, but are included only according to the Display Actual Price setting.
Configurable | The actual price does not automatically appear on catalog list and product pages, but is included only according to the Display Actual Price setting. Option prices appear normally.
Bundle (with fixed price) | The actual price does not automatically appear on catalog pages, but is included only according to the Display Actual Price setting. The prices of bundle items appear normally.*MAP is not available for bundle products with dynamic pricing.*
Downloadable | The actual price does not automatically appear on catalog list and product pages, but is included only according to the Display Actual Price setting. The price associated with each download link appears normally.

## Using MAP with Price Settings

PRICE SETTING| DESCRIPTION
-- | --
Main Price | When MAP is applied to the main price, the prices of options, bundle items, and associated products (which add or subtract from the main price) appear normally.
Associated Product Price | If a product does not have a main price, and its price is derived from the associated product prices (such as in a grouped product), the MAP settings of the associated products are applied.
MSRP | If a product in the cart has the Manufacturer’s Suggested Retail Price (MSRP) specified, the price is not crossed-out.
Tier Price | If tier pricing is set, the tier pricing message is not displayed in the catalog. On the product page a notification is displayed that indicates that the price can be lower when ordering more than a certain quantity, but the discount is displayed in percentages only. For associated products of a grouped product, the discounts are not displayed on the product page. The tier price appears according to the Display Actual Price setting.
Special Price | If the Special price is specified, the special price is displayed according to the Display Actual Price setting.