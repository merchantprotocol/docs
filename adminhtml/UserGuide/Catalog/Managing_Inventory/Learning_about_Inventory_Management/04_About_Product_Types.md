About Product Types
--

Inventory Management supports inventory and order management for all product types in Magento: simple, configurable, virtual, downloadable, bundle, and grouped. Options and requirements may differ per product type for sources, stocks, and shipping.

* Single Source merchants create and update product settings and quantities without requiring additional updates. All created and newly imported products automatically assign to the Default Source and Default Stock, immediately available to customers if enabled and In-Stock.
* Multi Source merchants assign sources, quantities per source, and settings during or after product creation. Magento assigns all newly imported products to the Default Source, requiring additional edits to assign sources and quantities.

## Supported Products

PRODUCT TYPE | SINGLE SOURCE | MULTI SOURCE | SOURCE AND STOCK | SHIPPING AND SOURCE SELECTION ALGORITHM
-- | -- | -- | --| --
Simple | Yes | Yes | Default Source. Default Stock. custom source/stock | Supports SSA recommendations and overrides at shipping
Configurable | Yes | Yes | Default Source. Default Stock. custom source/stock | Supports SSA recommendations and overrides at shipping
Virtual | Yes | Yes | Default Source. Default Stock. custom source/stock | Always uses the SSA recommendation. The system runs the algorithm implicitly when it creates invoices, and always uses the suggested results. You cannot adjust these results.
Downloadable | Yes | Yes | Default Source. Default Stock. custom source/stock | Always uses the SSA recommendation. The system runs the algorithm implicitly when it creates invoices, and always uses the suggested results. You cannot adjust these results.
Bundle | Yes | No | Default Source. Default Stock | Supports SSA recommendations and overrides at shipping
Grouped	| Yes |	Yes | Default Source. Default Stock. custom source/stock | Supports SSA recommendations and overrides at shipping