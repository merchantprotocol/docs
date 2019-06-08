Prioritizing Sources for a Stock
--
After adding sources to the stock, arrange those sources from top-to-bottom in priority for fulfilling orders. The Source Selection Algorithm (SSA) provides an algorithm Priority using this order when determining shipment and inventory deductions.

The source priority on stocks does not influence assigned sources when editing product inventories.

In this example, the UK Stock has sources assigned out of order for a store and two warehouses in London and a warehouse in Berlin.

![Source order before prioritization](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-stock-prioritybefore_thumb_0_0.png)

The merchant prefers to have shipments prioritized from the larger Berlin warehouse, then the London warehouse, the London overflow location, and finally the storefront in London. To reorder, the entries are dragged and dropped in order.

Use ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-sort-3_10x18.png) to drag and drop the sources into a priority from top (first) to bottom (last). This order is important when shipping orders. SSA recommends shipments based on the order of sources

![Source order after prioritization](https://docs.magento.com/m2/ce/user_guide/Resources/Images/stores-inventory-stock-priorityafter_thumb_0_0.png)