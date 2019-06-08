Product Alerts
--

Customers can subscribe to two types of alerts by email: price change alerts and in-stock alerts. For each type of alert, you can determine if customers are able to subscribe, select the email template that is used, and identify the sender of the email.

![Sign Up for Price Alert](https://docs.magento.com/m2/ce/user_guide/Resources/Images/storefront-price-alert-signup_thumb_0_0.png)

## Price Change Alerts

When price change alerts are enabled, a “Sign up for price alert” link appears on every product page. Customers can click the link to subscribe to alerts related to the product. Guests are prompted to open an account with your store. Whenever the price changes, or the product goes on special, everyone who has signed up to be notified receives an email alert.

## In-Stock Alerts

The in-stock alert creates a link called “Sign up to get notified when this product is back in stock” for every product that is out of stock. Customers can click the link to subscribe to the alert. When the product is back in stock, customers receive email notification that the product is available. Products with alerts have a Product Alerts tab in the Product Information panel that lists the customers who have subscribed to an alert.

 ![List of Product and Price Alert Subscriptions](https://docs.magento.com/m2/ce/user_guide/Resources/Images/catalog-product-alerts_thumb_0_0.png)
 
## To set up product alerts:

First, you need to set up and configure price alerts through the Stores > Configuration settings.

1.	On the Admin sidebar, tap **Stores**. Then under Settings, choose **Configuration**.
2.	In the panel on the left under **Catalog**, choose **Catalog**.
3.	Click to expand the **Product Alerts** section. Configure price alerts:

  a.	To offer price change alerts to your customers, set **Allow Alert When Product Price Changes** to “Yes.”

  b.	Set **Price Alert Email Template** to the template that you want to use for the price alert notifications. The default email template is selected for your theme. To create a new email template, see templates below.

  c.	To offer alerts when out-of-stock products become available again, set **Allow Alert When Product Comes Back in Stock** to “Yes.”

  > The “Sign up to get notified when this product is back in stock” message appears only when Inventory Stock Options - Display Out of Stock Products is set to “Yes.” 

  d.	Set **Stock Alert Email Template** to the template that you want to use for product stock alerts.

  e.	Set **Alert Email Sender** to the store contact that you want to appear as the sender of the email alert.
 
  ![Product Alerts](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-product-alerts_thumb_0_0.png)
  
4.	When complete, tap `Save Config`.

## To configure product alerts email templates:

Next, configure, add, or modify the email template for your price alert. You may want to edit your price alert configurations after creating any new templates.

1.	On the Admin sidebar, tap **Marketing**. Then under Communications, choose **Email Templates**.
2.	Tap `Add New Template`.
3.	Under **Load default template**, in the **Template** list, choose the template that you want to customize. This may be the alert template from your theme. Or you can select the Price Alert or Stock Alert templates under Magento_PriceAlert. Tap `Load Template`.
4.	Enter a **Template Name**. You can select this name in the Price Alerts configuration.
5.	Read through the existing content and make changes as needed for the following:

  * Template Subject: Displays in the subject line of an email.
  * Template Content: Displays in the full content of the sent email.

6.	To add generated information from Magento data, use the **Insert Variable** option. A list of available variables displays.
7.	Tap `Save Template`.