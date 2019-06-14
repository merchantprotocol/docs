Creating Shipments with Inventory Management
--

With Inventory Management, send one or more shipments to fulfill as you have inventory. Repeat these instructions to generate additional shipments as needed, using recommended or manually entered quantities and sources. These instructions detail how Multi Source merchants send shipments. Single Source merchants send shipments without these additional steps. See Creating a Shipment.

When creating shipments, use the Source Selection Algorithm for calculated recommendations. Follow and use these recommendations or set the amounts per source, generating custom shipments. You control your outgoing inventory for each order, setting the amounts to deduct, sending one or more shipments, and delivering in stock and backorders as inventory is available. For each line item in the order, enter an amount to deduct from the source quantity.

You may need to send partial shipments to:

* Fulfill backorders as inventory arrives
* Balance inventory deductions across sources

As you enter shipments, your on-hand inventory quantities deduct entered amounts. In effect, reservations convert to actual quantity deductions.

## To create a shipment:

1.	On the Admin sidebar, choose **Sales**. Then, choose **Orders**.
2.	Locate the order and open in **View** mode.
3.	If the order has been paid and invoiced, and is ready to ship, tap Ship.
4.	Complete the Source Selection for sending products per source:

  a.	To view shipping recommendations, tap **Source Selection Algorithm** and select an algorithm.
  
  * **Source Priority** Recommends shipments from sources according to the orders of sources assigned to the stock.
  * **Distance Priority** Recommends shipments from sources closest to the shipping address based on physical distance or shortest time to deliver.

  > **Important**: When using this algorithm for shipping, if routes and data does not return for the selected Computation mode (driving, bicycling, or walking) for a shipment, the SSA defaults to using the Source Priority. We recommend also setting the priority for sources per stock.

  b.	For the **Select a Source to Ship from**, select a source from the drop-down menu to send a shipment.

  c.	For each line item, keep the recommended amount or enter a specific amount in the **Qty to Deduct**.

  d.	Tap `Proceed to Shipment`.

  ![Select a Source and enter a Quantity](https://docs.magento.com/m2/ce/user_guide/Resources/Images/shipment-magento-shipping-sources_thumb_0_0.png)
  
5.	Review the New Shipment page to enter any additional changes. The Inventory section displays the source, products shipping, total ordered quantity, and quantity to ship.

![Inventory details for the Shipment, example Partial Shipment](https://docs.magento.com/m2/ce/user_guide/Resources/Images/inventory/inventory-shipment-details_thumb_0_0.png)

6.	Tap `Submit Shipment` to complete.