Watermarks
--

If you go to the expense of creating your own original product images, there is not much you can do to prevent unscrupulous competitors from stealing them with the click of a mouse. However, you can make them a less attractive target by placing a watermark on each image to identify them as your property. A watermark file can be either a JPG (JPEG), GIF, or PNG image. Both GIF and PNG file types support transparent layers, which can be used to give the watermark a transparent background.

The watermark used for the “small” image in the following example is a black logo with a transparent background, and saved as a PNG file with the following settings:

Option | Value
-- | --
Size: | 50x50
Opacity: | 5
Position: | Tile

![Tiled Watermark](https://docs.magento.com/m2/ce/user_guide/Resources/Images/storefront-watermark-tiled_thumb_0_0.png)

## To add watermarks to product images:

1.	On the Admin sidebar, tap **Content**. Then under Design, choose **Configuration**.
2.	Find the store view that you want to configure. Then in the **Action** column, click **Edit**.
3.	Under **Other Settings**, expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Product Image Watermarks** section.
4.	Complete the **Base, Thumbnail, Small, and Swatch Image** image settings as follows. The fields in each section are the same.

  a.	Enter the **Image Opacity** as a percentage. For example: 40

  b.	Enter the **Image Size**, in pixels. For example: 200 x 200

  c.	Tap `Upload`, and choose the image file that you want to use.

  d.	Set **Image Position** to determine where the watermark appears.
  
  ![Product Image Watermarks - Base](https://docs.magento.com/m2/ce/user_guide/Resources/Images/config-design-product-image-watermarks-base_thumb_0_0.png)
  
5.	When complete, tap  `Save Config` .
6.	When prompted to refresh the cache, tap the Cache Management link in the system message. Then, refresh the invalid cache.

![Refresh Cache](https://docs.magento.com/m2/ce/user_guide/Resources/Images/msg-cache-management_thumb_0_0.png)

## To restore the default value:

Tap **Use Default Value** ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-use-default_19x18.png) ).

## To delete a watermark:

1.	In the lower-left corner of the image, tap Delete ( ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-trashcan2_14x18.png) ).
![Delete Watermark](https://docs.magento.com/m2/ce/user_guide/Resources/Images/product-image-watermark-delete_thumb_0_0.png)
2.	Tap  `Save Config` .
3.	When prompted to refresh the cache, tap the Cache Management link in the system message. Then, refresh the invalid cache.

  If the watermark image persists in the storefront, return to Cache Management and tap `Flush Magento Cache` .