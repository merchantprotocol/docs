Root Categories
--

The products in the main menu are determined by the root category that is assigned to the store. The root category is basically a container for the main menu in the category tree. You can create a root category with an entirely new set of products, or copy products from an existing root category. The root category can be assigned to the current store, or to any other store in the same website.

![Scope of Main Menu](https://docs.magento.com/m2/ce/user_guide/Resources/Images/scope-catalog_thumb_0_0.png)

From the Admin, the category structure is like an upside-down tree, with the root on top. The root has a name, but no URL key, and does not appear in the top navigation of the store. All other categories in the menu are nested below the root. Because the root category is the highest level of the catalog, your store can have only one root category active at a time. You can, however, create additional root categories for alternate catalog structures, different stores, and views.

The following example shows how to create a new root category and assign it to a different store.

## Step 1: Create a New Root Category

1.	On the Admin sidebar, tap **Products**. Then under **Inventory**, choose **Categories**.
2.	In the panel on the left, tap `Add Root Category`.
![New Root Category](https://docs.magento.com/m2/ce/user_guide/Resources/Images/category-root_thumb_0_0.png)
3.	Assign a **Category Name**.

  The name you choose will initially be assigned to all store views.

4.	If you want to add products to the catalog from the current catalog, do the following:

  a.	Expand ![](https://docs.magento.com/m2/ce/user_guide/Resources/Images/btn-expand.png) the **Products in Category** section.
  b.	Use the search filters to find the products you want. Then, mark the checkbox of each product that you want to copy into the new catalog.

5.	When complete, tap `Save`.

## Step 2: Build Out the Main Menu

1.	In the panel on the left, select the new root category that you created in the previous step.
2.	Tap `Add Subcategory`. Then, follow the instructions to create the category structure for the main menu.

## Step 3: Assign the Root Category to the Store

1.	On the Admin sidebar, tap **Stores**. Then under **Settings**, choose **All Stores**.
2.	In the **Stores** column of the grid, click the store that you want to assign the new catalog.
3.	Set **Root Category** to the new root category that you created.
4.	Make sure that the store has a **Default Store View** assigned. The store must have at least one store view.
5.	When complete, tap `Save Store`.
6.	To verify that the store has a new catalog, do the following:

  a.	On the Admin sidebar, tap **Products**. Then, choose **Catalog**.
Any products that were copied to the new catalog appear in the grid.
  b.	Visit the storefront to verify that the new catalog and main menu are working correctly.