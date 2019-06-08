Stock Message Scenarios
--

You can use a combination of configuration settings to control stock availability messages on product pages and in listings of products on catalog pages.

![Grouped Product with “Out of Stock” Message](https://docs.magento.com/m2/ce/user_guide/Resources/Images/storefront-out-of-stock-message_thumb_0_0.png)

## Product Page Stock Messages

There are several variations of messaging available for the product page, depending on the combination of Manage Stock and Stock Availability settings.

### Example 1: Show Availability Message

**Scenario 1**: This combination of settings causes the availability message to appear on the product page, according to the stock availability of each product.

STOCK OPTIONS | VALUE | MESSAGE
-- | -- | --
Display product availability in stock in the frontend: | Yes | 
**Product Inventory** | | 
Manage Stock | Yes | 
Stock Availability | In Stock.  | “Availability: In Stock”. 
 | Out of Stock | “Availability: Out of Stock”

**Scenario 2**:	When stock is not managed for a product, this combination of settings can be used to display the availability message on the product page.

STOCK OPTIONS | MESSAGE
-- | --
Display product availability in stock in the frontend: | Yes |
**Product Inventory** | | 
Manage Stock | No | “Availability: In Stock”

### Example 2: Hide Availability Message

**Scenario 1**:	This combination of configuration and product settings prevents the availability message from appearing on the product page.

STOCK OPTIONS | VALUE | MESSAGE
-- | -- | --
Display product availability in stock in the frontend: | No |
**Product Inventory** | |
Manage Stock | Yes |
Stock Availability | In Stock | None. 
 | Out of Stock | None

**Scenario 2**:	When stock is not managed for a product, this combination of configuration and product settings prevents the availability message from appearing on the product page.

STOCK OPTIONS | | MESSAGE
-- | -- | --
Display product availability in stock in the frontend: | No |
Product Inventory | |
Manage Stock | No | None

## Catalog Page Stock Messages

The following display options are possible for the category and search results lists, depending on the product availability and configuration settings.

![“Out of Stock” Message on Category Page](https://docs.magento.com/m2/ce/user_guide/Resources/Images/storefront-out-of-stock-catalog-page_thumb_0_0.png)

### Example 1: Show Product with “Out of Stock Message”

This combination of configuration settings includes out of stock products in the category and search results lists, and displays an “out of stock” message.

STOCK OPTIONS | | MESSAGE
-- | -- | --
Display Out of Stock Products | Yes | 
Display product availability in stock in the frontend | Yes | “Out of stock”
Display Out of Stock Products | Yes | 
Display product availability in stock in the frontend | No | None

### Example 2: Show Product without “Out of Stock Message”

This combination of configuration settings includes out of stock products in the category and search results lists, but does not display a message.

STOCK OPTIONS |  | MESSAGE
-- | -- | --
Display Out of Stock Products | Yes | None
Display product availability in stock in the frontend| No | 

### Example 3: Hide Product Until Back in Stock

This configuration setting omits out of stock products entirely from the category and search results lists, until they are back in stock.

STOCK OPTIONS | | MESSAGE
-- | -- | --
Display Out of Stock Products | No | None