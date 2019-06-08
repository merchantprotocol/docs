Adding Product Video
--

To add product video, you must first obtain an API Key from your Google account, and enter it in the configuration of your store. Then, you can link to the video from the product.

## Step 1: Get Your YouTube API Key
1.	Log in to your Google account, and visit the [Google Developers Console](https://console.developers.google.com/). Then, do the following:

  a.	Under Use Google APIs, click **Enable and manage APIs**.

  b.	In the panel on the left choose **Credentials**. Expand the Add Credentials menu, and choose **API key**.

  c.	When prompted to create a new key, choose **Server key**. Enter a name for the key, and tap `Create`.

2.	Wait a few moments while the key is generated. Then, copy the key to the clipboard.

  In the next step, you will paste the key into your store’s configuration.

## Step 2: Configure Magento

1.	On the Admin sidebar, tap **Stores**. Then under Settings, choose **Configuration**.
2.	In the panel on the left under **Catalog**, choose **Catalog**.
3.	Expand  the **Product Video** section. Then, paste your **YouTube API key**.
![Product Video](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-catalog-catalog-product-video_thumb_0_0.png)
4.	When complete, click `Save Config`.
5.	When prompted, refresh the cache.

### Step 3: Link to the Video

1.	Open a product in edit mode.  Then in the Images and Video section, tap `Add Video`.

  If you haven’t yet entered your YouTube API key, tap `OK` to continue. You won’t be able to link to a YouTube video, but you can go through the process.

  ![Add Video](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-video-add_thumb_0_0.png)

2.	Enter the **URL** of the YouTube or Vimeo video.
3.	Enter the **Title** and **Description** of the video.
4.	To upload a **Preview Image**, browse to the image and select the file.
5.	If you prefer to use the video meta data, tap `Get Video Information`.
6.	To determine how the video is used in the store, mark the checkbox of each Role that applies:

  * Base Image
  * Small Image
  * Swatch Image
  * Thumbnail
  * Hide from Product Page
  
7.	When complete, tap `Save`.
 
![New Video](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-video-new-with-data_thumb_0_0.png)

### Field Descriptions

FIELD | DESCRIPTION
-- | --
URL | The URL of the associated video.
Title | The video title.
Description | The video description.
Preview Image | An uploaded image that is used as a preview of the video in your store.
`Get Video Information` | Retrieves the video meta data that is stored on the host server. You can use the original data, or update it as needed.
Role | Determines how the preview image is used in your store. Options:
 | Base Image
 | Small Image
 | Thumbnail
 | Swatch Image
 | Hide from Product Page