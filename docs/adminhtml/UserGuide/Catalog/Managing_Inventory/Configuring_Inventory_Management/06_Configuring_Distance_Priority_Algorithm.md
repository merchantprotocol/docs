Configuring Distance Priority Algorithm
--

The Distance Priority algorithm compares the location of the shipping destination address with source locations to determine the closest source to fulfill shipments. The distance may be determined by physical distance or time spent traveling from one location to another, using database data or driving, walking, or bicycling directions. Use this Source Selection Algorithm to recommend the closest source to shipping destination addresses.

> We recommend entering the full street address and GPS coordinates for your sources if using the Distance Priority algorithm.

You have two options for calculating the distance and time to find the closest source for shipment fulfillment:

* **Google MAP**: Uses Google Maps Platform services to calculate the distance and time between the shipping destination address and source locations. This option uses the source's Latitude and Longitude (GPS coordinates) and may use the street address depending on the computation mode. This option uses the source's Latitude and Longitude. You must provide a Google API key with Geocoding API and Distance Matrix API enabled, and may incur charges through Google.
* **Offline Calculation**: Calculates the distance using downloaded and imported geocode data using zip/post codes and GPS coordinates to determine the closest source to the shipping destination address. To configure this option, you may require developer assistance to initially download and import geocodes using a command line.

## To configure Google Maps:

You do not need a Google account to get started. The process includes Google account and project creation if needed. This option requires a billing account and payment method added to your Google account to complete configurations and use the algorithm.

### Step 1: Create the Google API Key

The key is from the [Google Maps Platform](https://cloud.google.com/maps-platform/) and should have [Geocoding API](https://developers.google.com/maps/documentation/geocoding/start) and [Distance Matrix API](https://developers.google.com/maps/documentation/distance-matrix/start) enabled. For details, see [Configuring Distance Priority Algorithm](https://docs.magento.com/m2/ce/user_guide/catalog/inventory-configure-distance-priority.html#).

1.	Visit [Google Maps Platform](https://cloud.google.com/maps-platform/) and click **Get Started**.
2.	To enable the platform, select Maps, Routes, and Places and click **Continue**.
 ![Google Maps Platform for your Key](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-inventory-google-key1_thumb_0_0.png)
3.	Sign in with a Google account or create a new account.
4.	Set up a project:

  a.	Select a project or enter a new project name.

  b.	Select **Yes** to accept the terms.
 
  c.	Click **Next**.

5.	Enter a billing account, or create one. You can skip and add a billing account later. The account is required to use this service.
6.	Click **Console** to open and configure your Google Cloud Platform options.

  a.	Open your project.

  b.	Expand the menu and click **APIs & Services** > Library.
  
  ![Google API Services](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-inventory-google-key2.png)
  
  c.	Search for [Geocoding API](https://developers.google.com/maps/documentation/geocoding/start) and [Distance Matrix API](https://developers.google.com/maps/documentation/distance-matrix/start). Select and enable each service.

7.	Expand the menu and click **APIs & Services** > **Credentials**. Copy the Google API Key.
 
![Google API Key Copy](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-inventory-google-key3_thumb_0_0.png)

### Step 2: Configure the Google MAP Provider

1.	On the Admin sidebar, tap **Stores**. Then under Settings, choose **Configuration**.
2.	In the panel on the left under Catalog, choose **Inventory**.
3.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Distance Provider for Distance Based SSA** section, and set **Provider** to "Google MAP".
 
![Distance Providers for Distance Based SSA](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-inventory-distance-provider_thumb_0_0.png)

4.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Google Distance Provider** section, and configure the settings:

  a.	Enter the *Google API Key**, copied from your Google Account.

  b.	For **Computation mode**, select a configuration.

  > **Important**: When using this algorithm for shipping, if routes and data does not return for the selected Computation mode (driving, bicycling, or walking) for a shipment, the SSA defaults to using the Source Priority. We recommend also setting the priority for sources per stock.

  **Driving** | Default setting, requests standard driving directions using the road network
  
  **Walking** | Requests walking directions using pedestrian paths and sidewalks (where available)
  
  **Bicycling** | Requests bicycling directions using bicycle paths and preferred streets (where available). The Distance Matrix Service is currently only available in the US and some Canadian cities.

  c.	For **Value**, select a value type:

  **Distance** | Default setting, returns the distance between points in metrics (kilometers and meters) or imperial (miles and feet)
  
  **Time to Destination** | Returns the time required to travel from the source locations to the shipping address in hours and minutes

  ![Google Distance Provider](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-inventory-distance-provider-settings_thumb_0_0.png)

5.	When complete, tap  `Save Config` .

## To configure Offline Calculation:

Offline calculations use country codes to determine the distance between the shipping destination and source addresses. This option may require developer assistance to configure. You will issue a an Inventory Management CLI command to download and import data from [geonames.org](https://www.geonames.org/).

### Step 1: Download and Import Geocodes
Complete command line configuration to download and import geocodes countries to ship to and have source locations in. This step may require developer assistance. See DevDocs Import geocodes for Inventory Management.

Complete these commands anytime you need to add more geocodes.

### Step 2: Configure Offline Calculation

1.	On the Admin sidebar, tap **Stores**. Then under Settings, choose **Configuration**.
2.	In the panel on the left under **Catalog**, choose **Inventory**.
3.	Expand 1[](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Distance Provider for Distance Based SSA** section, clear the **Use system value** checkbox and set **Provider** to "Offline Calculation".
 ![Distance Providers for Distance Based SSA](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-inventory-distance-offline_thumb_0_0.png)
4.	When complete, tap  `Save Config` .