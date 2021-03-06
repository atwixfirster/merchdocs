---
title: Bundle Product
---

A bundle is a “build your own,” customizable product. Each item in a bundle can be based on one of the following product types:

* [Simple Product]({{ site.baseurl }}{% link catalog/product-create-simple.md %})
* [Virtual Product]({{ site.baseurl }}{% link catalog/product-create-virtual.md %})

    ![]({{ site.baseurl }}{% link images/images/product-bundle.png %}){: .zoom}
    *Bundle Product*

The selection of options appears when the customer taps either the Customize and Add to Cart button. Because the products that are included in the bundle vary, the SKU, Price, and Weight can be set to either a dynamic or fixed value.

{:.bs-callout .bs-callout-info}
Minimum Advertised Price (MAP) is not available for Bundle products with dynamic pricing.

If [Instant Purchase]({{ site.baseurl }}{% link sales/checkout-instant-purchase.md %}) is available, the Instant Purchase button appears below the Add to Cart button for each item in the bundle.

![]({{ site.baseurl }}{% link images/images/product-bundle-customize.png %}){: .zoom}
*Customize Bundle*

The following instructions take you through the process of creating a bundle product using a [product template]({{ site.baseurl }}{% link stores/attribute-sets.md %}), required fields, and basic settings. Each required field is marked with a red asterisk (*). When you finish the basics, you can complete the [advanced settings]({{ site.baseurl }}{% link catalog/settings-advanced.md %}) and [other settings]({{ site.baseurl }}{% link catalog/settings-other.md %}) as needed.

## Step 1: Choose the Product Type

1. On the Admin sidebar, tap **Products**. Then, choose **Catalog**.

1. In the upper-right corner on the **Add Product** ( ![]({{ site.baseurl }}{% link images/images/btn-save-menu.png %}){: .Inline} ) menu, choose **Bundle Product**.

    ![]({{ site.baseurl }}{% link images/images/21product-add-bundle.png %}){: .zoom}
    *Add Bundle Product*

## Step 2: Choose the Attribute Set

To choose the [attribute set]({{ site.baseurl }}{% link stores/attribute-sets.md %}) that is used as a template for the product, do one of the following:

* In the **Search** box, enter the name of the attribute set,
* In the list, choose the attribute set that you want to use.

The form is updated to reflect the change.

![]({{ site.baseurl }}{% link images/images/product-create-choose-attribute-set.png %}){: .zoom}
*Choose Template*

## Step 3: Complete the Required Settings

1. Enter the product **Product Name**.

1. You can either accept the default **SKU** that is based on the product name, or enter a different value. To determine the type of SKU that is assigned to each bundle item, do the following:

    * A **Dynamic SKU** can be assigned automatically to each bundle item by adding a suffix to the default SKU. By default, Dynamic SKU is set to “Yes.”
    * If you prefer to assign a unique SKU for each bundle item, set **Dynamic SKU** to the “No” ( ![]({{ site.baseurl }}{% link images/images/btn-switch-no.png %}){: .Inline}) position.

    ![]({{ site.baseurl }}{% link images/images/product-bundle-dynamic-sku-price.png %}){: .zoom}
    *Dynamic SKU and Price*

1. To determine the price of the bundle, do one of the following:

    * A **Dynamic Price** changes to reflect the options chosen by the customer. By default, Dynamic Price is set to “Yes,” and the Price field is left blank.
    * To charge a fixed price for the bundle, set **Dynamic Price** to the “No.” ( ![]({{ site.baseurl }}{% link images/images/btn-switch-no.png %}){: .Inline}) position. Then, enter the **Price** that you want to charge for the bundle.

1. Because the product is not yet ready to publish, set the **Enable Product** switch to the “No” ( ![]({{ site.baseurl }}{% link images/images/btn-switch-no.png %}){: .Inline} ) position.

1. Tap <span class="btn"> Save </span> and continue.

    When the product is saved, the [Store View]({{ site.baseurl }}{% link catalog/product-scope.md %}) chooser appears in the upper-left corner.

1. Choose the **Store View** where the product is to be available.

    ![]({{ site.baseurl }}{% link images/images/product-create-store-view-choose.png %}){: .zoom}
    *Choose Store View*

## Step 4: Complete the Basic Settings

1. If the bundle has Fixed Pricing, set **Tax Class** to one of the following:

    * None
    * Taxable Goods

    If the bundle has Dynamic Pricing, the tax is determined for each bundle item.

1. Take note of the following:

    * The **Quantity** is not available because the value is determined for each bundle item.
    * The **Stock Status** is set by default to “In Stock.”

1. To determine the weight of the bundle, do one of the following:

    * A **Dynamic Weight** changes to reflect the options chosen by the customer. By default, Dynamic Weight is set to “Yes,” and the Weight field is left blank.
    * To assign a fixed weight to the bundle, set **Dynamic Weight** to the “No.” ( ![]({{ site.baseurl }}{% link images/images/btn-switch-no.png %}){: .Inline}) position. Then, enter the **Weight** of the bundle.

    ![]({{ site.baseurl }}{% link images/images/product-bundle-dynamic-weight.png %}){: .zoom}
    *Dynamic Weight*

1. To feature the product in the list of[ new products]({{ site.baseurl }}{% link cms/widget-new-products-list.md %}), mark the **Set Product as New** checkbox.

1. Accept the default **Visibility** setting, “Catalog, Search.”

1. To assign **Categories** to the product, tap the **Select…** box. Then, do either of the following:

    **Choose an existing category:**

    * Start typing in the box to find a match.

    * Mark the checkbox of each category that is to be assigned.

    **Create a new category:**

    * Tap <span class="btn"> New Category </span>.

    * Enter the **Category Name** and choose the **Parent Category** to determine its position in the menu structure.

    * Tap <span class="btn"> Create Category </span>.

1. Choose the **Country of Manufacture**.

    ![]({{ site.baseurl }}{% link images/images/product-bundle-details.png %}){: .zoom}
    *Bundle Details*

    There might be additional attributes that describe the product. The selection varies attribute set, and you can complete them later.

## Step 5: Add the Bundle Items

1. Scroll down to the Bundle Items section. Then, set **Ship Bundle Items** to one of the following:

    * Separately
    * Together

    ![]({{ site.baseurl }}{% link images/images/product-bundle-items.png %}){: .zoom}
    *Bundle Items*

1. Tap <span class="btn"> Add Option </span>, Then, do the following:

    ![]({{ site.baseurl }}{% link images/images/product-bundle-new-option.png %}){: .zoom}
    *Add Bundle Options*

    * Enter an **Option Title** to be used field label.

    * Set **Input Type** to one of the following:

        * Drop-down
        * Radio buttons
        * Checkbox
        * Multiple Select

    * To make the field a required entry, mark the **Required** checkbox.

    * Tap <span class="btn"> Add Products to Option </span>. Then, mark the checkbox of each product that you want to include in this option. If there are many products, use the [list filters]({{ site.baseurl }}{% link stores/admin-grid-controls.md %}) and [pagination controls]({{ site.baseurl }}{% link catalog/navigation-pagination.md %}) to find the products you need.

    * Tap <span class="btn"> Add Selected Products </span>.

    ![]({{ site.baseurl }}{% link images/images/product-bundle-add-products-to-option.png %}){: .zoom}
    *Add Selected Products*

    * After the items appear in the Options section choose one to be the **Default** selection.

    * In the **Default Quantity** column, enter the quantity of each item that is to be added to the bundle when a customer chooses the item.

    * To allow customers to change the quantity of a bundle item, select the **User Defined** option.

    {:.bs-callout .bs-callout-info}
    The quantity can be a preset or user-defined value. However, do not assign the User Defined property to checkbox or multiple-select input types.

    By default, the Default Quantity that is included in a bundle item cannot be changed by the customer. However, the customer can enter the quantity of the item that is to be included in the bundle.

    For example, if the Default Quantity of the Sprite Status Ball is set to 2, and the customer orders 4 of that bundle option, the total number of total balls purchased is 8.

    ![]({{ site.baseurl }}{% link images/images/product-bundle-item-detail.png %}){: .zoom}
    *Item Detail*

1. Repeat these steps for each item you want to add to the bundle.

1. To remove any item from the bundle, tap the **Delete** ( ![]({{ site.baseurl }}{% link images/images/btn-delete.png %}){: .Inline} ) icon.

1. When complete, tap <span class="btn"> Save </span>.

## Step 6: Complete the Product Information

Scroll down and complete the information in the following sections as needed:

* [Content]({{ site.baseurl }}{% link catalog/product-content.md %})
* [Images and Videos]({{ site.baseurl }}{% link catalog/product-images-and-video.md %})
* [Search Engine Optimization]({{ site.baseurl }}{% link catalog/product-search-engine-optimization.md %})
* [Related Products, Up-Sells, and Cross-Sells]({{ site.baseurl }}{% link catalog/related-products-up-sells-cross-sells.md %})
* [Customizable Options]({{ site.baseurl }}{% link catalog/settings-advanced-custom-options.md %})
* [Products in Websites]({{ site.baseurl }}{% link catalog/settings-basic-websites.md %})
* [Design]({{ site.baseurl }}{% link catalog/settings-advanced-design.md %})
* [Gift Options]({{ site.baseurl }}{% link catalog/product-gift-options.md %})

## Step 7: Publish the Product

1. If you are ready to publish the product in the catalog, set the **Enable Product** switch to the “Yes” ( ![]({{ site.baseurl }}{% link images/images/btn-switch-yes.png %}){: .Inline} ) position.

1. Do one of the following:

    **Method 1: Save and Preview**

    1. In the upper-right corner, tap <span class="btn">Save</span>.

    1. To view the product in your store, choose **Customer View** on the **Admin** ( ![]({{ site.baseurl }}{% link images/images/btn-dropdown-blk.png %}){: .Inline} ) menu. The store opens in a new browser tab.

    ![]({{ site.baseurl }}{% link images/images/product-admin-customer-view.png %}){: .zoom}
    Customer View

    **Method 2: Save and Close**

    On the **Save** (![]({{ site.baseurl }}{% link images/images/btn-dropdown.png %}){: .Inline} ) menu, choose
    **Save &amp; Close**.

    ![]({{ site.baseurl }}{% link images/images/product-edit-save-close.png %}){: .zoom}
    *Save &amp; Close*

<table><h3 class="TableHeading">Input Controls</h3>
<col WIDTH="200">
<col WIDTH="auto">
<thead><tr><th>Control</th><th>Description</th></tr></thead><tbody><tr><td>Drop-down</td><td>Displays a drop-down list of options with the product name and price. Only one item can be selected.<img src="{{ site.baseurl }}{% link images/images/product-bundle-input-type-drop-down.png %}" class="zoom" /></td></tr><tr><td>Radio Buttons</td><td>Displays a radio button for each option, followed by the product name and price.  Only one item can be selected.<img src="{{ site.baseurl }}{% link images/images/product-bundle-input-type-radio-buttons.png %}" class="zoom" /></td></tr><tr><td>Checkbox</td><td>Displays a checkbox for each option, followed by the product name and price.  Multiple items can be selected. <img src="{{ site.baseurl }}{% link images/images/product-bundle-input-type-checkbox.png %}" class="zoom" /></td></tr><tr><td>Multiple Select</td><td>Displays a list of options with the product name and price. To select multiple items, hold down the Ctrl (or Option) key, and click each item. <p><img src="{{ site.baseurl }}{% link images/images/product-bundle-input-type-multiple-select.png %}" class="zoom" /></p></td></tr></tbody></table>

<table><h3 class="TableHeading">Field Descriptions</h3>
<col WIDTH="200">
<col WIDTH="auto">
<thead><tr><th>Field</th><th>Description</th></tr></thead><tbody><tr><td>SKU</td><td>Determines if each item is assigned a variable, dynamic SKU, or if a fixed SKU is used for the bundle. Options include: Fixed / Dynamic.</td></tr><tr><td>Weight</td><td>Specifies the weight is calculated based on the items selected, or is a fixed weight for the entire bundle. Options include: Fixed / Dynamic.</td></tr><tr><td>Price View</td><td>Determines if the product price is shown as a range, from the least expensive  to the most expensive (Price Range), or with the least expensive shown (As Low As). Options include: Price Range / As Low As.</td></tr><tr><td>Ship Bundle Items</td><td>Specifies if individual items can be shipped separately.</td></tr></tbody></table>

## Things to Remember

| ![]({{ site.baseurl }}{% link images/images/assets/checkbox.png %}){: .checkbox} | Customers can “build their own” bundle product. |
| ![]({{ site.baseurl }}{% link images/images/assets/checkbox.png %}){: .checkbox} | Bundle items can be simple or virtual products without custom options. |
| ![]({{ site.baseurl }}{% link images/images/assets/checkbox.png %}){: .checkbox} | The Price View can be set to a price range or to “As Low As.” |
| ![]({{ site.baseurl }}{% link images/images/assets/checkbox.png %}){: .checkbox} | SKU and Weight can be either “Fixed” or “Dynamic.” |
| ![]({{ site.baseurl }}{% link images/images/assets/checkbox.png %}){: .checkbox} | The quantity can be a preset or user-defined value. However, do not assign the User Defined property to checkbox or multiple-select input types. |
| ![]({{ site.baseurl }}{% link images/images/assets/checkbox.png %}){: .checkbox} | Bundle items can be shipped together or separately. |
{:style="table-layout:auto"}