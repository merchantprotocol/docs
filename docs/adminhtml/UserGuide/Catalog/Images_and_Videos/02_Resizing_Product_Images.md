Resizing Product Images
--

When uploading product images, you may add larger images with varying sizes to provide detailed, high quality zooms on the Product Details page. To ensure all images have a similar size and look, we provide an image upload resizing option to ensure all images match a specific pixel size. This option automatically resizes all product images using the configuration settings, which can help with performance of zoom, faster loading of images, and keep a uniform look to your product images.

Setting a maximum pixel width and height resizes the image to the physical dimensions by pixel. Magento resizes the image according to the higher amount of either width or height while keeping the proportions. Reducing the quality amount for JPG images reduces the file size.

For example, a 3000 x 2100 pixel JPG at 100% could be a 5mb+ image. Resizing this image would reduce the width to 1920 pixels, keeping proportions, and quality to 80% to provide much smaller file size with high quality.

## To enable image resizing:

1.	On the Admin sidebar, tap **Stores**. Then under Settings, choose **Configuration**.
2.	Tap **Advanced**. Then choose **System**.
3.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the Images Upload Configuration section, and configure. TO change default settings, you may need to clear the Use system value checkbox.

  a.	To enable, make sure **Enable Frontend Resize** is set to "Yes".

  b.	Enter a **Quality** setting from 1 to 100%. Recommend 80-90% for a reduced file size and high quality.

  c.	Set the **Maximum Width** in pixels for the image. When the image is resized, it does not exceed this width and retains proportions.

  d.	Set the **Maximum Height** in pixels for the image. When the image is resized, it does not exceed this height and retains proportions.
 
![Image Upload Configuration](https://docs.magento.com/m2/ce/user_guide/Resources/Images/system-image-upload-configuration_thumb_0_0.png)

4.	When complete, tap  `Save Config` .

### Field Descriptions

FIELD | SCOPE | DESCRIPTION
-- | -- | --
Quality | Global | Determines the JPG quality for the resized image. Lower quality reduces the file size. We recommend 80-90% to help reduce file size with high quality. Default: 80
Enable Frontend Resize | Global	| Enable to allow Magento to resize large, oversized images you may upload for the Product Details Page. Magento resizing the image files using JavaScript prior to uploading the file. When the image is resized, it keeps the exact proportions, meeting and not exceeding the largest size for Maximum Width or Maximum Height. Default: Yes
Maximum Width | Global | Determines the maximum pixel width for the image. When the image is resized, it does not exceed this width. Default: 1920
Maximum Height | Global | Determines the maximum pixel height for the image. When the image is resized, it does not exceed this height. Default: 1200