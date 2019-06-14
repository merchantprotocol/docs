Configuring Source Priority Algorithm
--

Custom stocks include an assigned list of sources to sell and ship available product inventory through your storefront. This algorithm uses the order of assigned sources in your stock to make recommendations.

When run, the algorithm:

* Works through the configured order of sources at the stock level starting at the top
* Recommends a quantity to ship and source per product based on the order in the list, available quantity, and quantity ordered
* Continues down the list until the order shipment is filled
* Skips disabled sources if found in the list

To configure, arrange those sources from top-to-bottom in priority for fulfilling orders. The Source Selection Algorithm (SSA) provides an algorithm Priority using this order when determining shipment and inventory deductions. See Prioritizing Sources for a Stock.

> **Important**: When using the Distance Priority algorithm for shipping, if routes and data do not return for the selected Computation mode (driving, bicycling, or walking) for a shipment, the SSA defaults to using the Source Priority.

![Source order after prioritization](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-stock-priorityafter_thumb_0_0.png)