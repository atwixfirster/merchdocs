---
title: Checkout
---

Stores > Settings > [Configuration]({{ site.baseurl }}{% link stores/configuration.md %}) > [Sales]({{ site.baseurl }}{% link configuration/sales.md %}) > Checkout

## Checkout Options

<!--{% if "Default.CE Only" contains site.edition %}-->
![]({{ site.baseurl }}{% link images/images/config-sales-checkout-checkout-options.png %}){: .zoom}
[_Checkout Options_]({{ site.baseurl }}{% link sales/checkout-options.md %})
<!--{% endif %}-->
<!--{% if "Default.EE-B2B" contains site.edition %}-->
![]({{ site.baseurl }}{% link images/images-ee/config-sales-checkout-checkout-options.png %}){: .zoom}
[_Checkout Options_]({{ site.baseurl }}{% link sales/checkout-options.md %})
<!--{% endif %}-->

|Field|[Scope]({{ site.baseurl }}{% link configuration/scope.md %})|Description|
|--- |--- |--- |
|[Enable Onepage Checkout]({{ site.baseurl }}{% link sales/checkout-onepage.md %})|Store View|Determines if Onepage checkout is the default checkout format. Options: Yes / No|
|[Allow Guest Checkout]({{ site.baseurl }}{% link sales/checkout-guest.md %})|Store View|Determines if guests can go through checkout without registering for an account with your store. Options: Yes / No|
|[Enable Terms and Conditions]({{ site.baseurl }}{% link sales/terms-and-conditions.md %})|Store View|Determines if customers are required to agree to the Terms and Conditions of the sale before making a purchase. Options: Yes / No|
|Display Billing Address On|Store View|Determines the location of the Billing Address during checkout. Options: Payment Method / Payment Page|
|Maximum Number of Items to Display in Order Summary|Store View|Determines the maximum number of items that can  appear in the Order Summary during checkout. The default is 10.|<!--{% if "Default.EE-B2B" contains site.edition %}-->
|[Enable Address Search]({{ site.baseurl }}{% link sales/checkout-address-search.md %})|Website|Determines if customers can use address search functionality for Shipping, as well as Review & Payments steps. When this is enabled, use Number of Customer Addresses Limit to set the number of saved addresses required to activate this functionality during checkout. Options: Yes / No|
|Number of Customer Addresses Limit|Website|When address search is enabled, determines the number of saved addresses required to activate this functionality during checkout. When the customer's number of saved addresses meets or exceeds this number, only the default address is rendered on the _Shipping_ and _Review & Payments_ steps. The customer can use a search function to change the selected address. The default is 10.|<!--{% endif %}-->

## Shopping Cart

<!--{% if "Default.CE Only" contains site.edition %}-->
![]({{ site.baseurl }}{% link images/images/config-sales-checkout-shopping-cart.png %}){: .zoom}
[_Shopping Cart_]({{ site.baseurl }}{% link sales/cart-configuration.md %})
<!--{% endif %}-->
<!--{% if "Default.EE Only" contains site.edition %}-->
![]({{ site.baseurl }}{% link images/images/config-sales-checkout-shopping-cart.png %}){: .zoom}
[_Shopping Cart_]({{ site.baseurl }}{% link sales/cart-configuration.md %})
<!--{% endif %}-->
<!--{% if "Default.B2B Only" contains site.edition %}-->
![]({{ site.baseurl }}{% link images/images-b2b/config-sales-checkout-shopping-cart.png %}){: .zoom}
[_Shopping Cart_]({{ site.baseurl }}{% link sales/cart-configuration.md %})
<!--{% endif %}-->

|Field|[Scope]({{ site.baseurl }}{% link configuration/scope.md %})|Description|
|--- |--- |--- |
|[Quote Lifetime (days)]({{ site.baseurl }}{% link sales/cart-quote-lifetime.md %})|Website|Determines the lifetime of a quoted price, in days.|
|[After Adding a Product Redirect to Shopping Cart]({{ site.baseurl }}{% link sales/cart-redirect.md %})|Store View|Determines if the shopping cart page appears immediately after a product is added to the cart. Options: Yes / No|
|Number of Items to Display Pager|Store View|Determines the number of items in the shopping cart before the pager is triggered. Default value: 20|
|[Show Cross-sell Items in the Shopping Cart]({{ site.baseurl }}{% link catalog/settings-advanced-cross-sells.md %})|Store View|Indicates if cross-sell items will display in the shopping cart, providing additional sale options to customers. Options: Yes (Default) / No|
|[Grouped Product Image]({{ site.baseurl }}{% link sales/cart-thumbnails.md %})|Store View|Determines the  thumbnail image that appears for  a [grouped product]({{ site.baseurl }}{% link catalog/product-create-grouped.md %}) in the shopping cart. Options: Product Thumbnail Itself / Parent Product Thumbnail|
|[Configurable Product Image]({{ site.baseurl }}{% link sales/cart-thumbnails.md %})|Store View|Determines the  thumbnail image that appears for a configurable product in the shopping cart. Options: Product Thumbnail Itself / Parent Product Thumbnail| <!--{% if "Default.B2B Only" contains site.edition %}-->
|Preview Quote Lifetime (minutes)|Store View|Determines the maximum age of the quote in minutes when previewed from the shopping cart.|<!--{% endif %}-->

## My Cart Link

![]({{ site.baseurl }}{% link images/images/config-sales-checkout-my-cart-link.png %}){: .zoom}
[*My Cart Link*]({{ site.baseurl }}{% link sales/cart-link.md %})

|Field|[Scope]({{ site.baseurl }}{% link configuration/scope.md %})|Description|
|--- |--- |--- |
|Display Cart Summary|Website|Determines the value that appears in parenthesis after the My Cart link. Options: Display number of items in cart / Display item quantities|

## Shopping Cart Sidebar

![]({{ site.baseurl }}{% link images/images/config-sales-checkout-shopping-cart-sidebar.png %}){: .zoom}
[*Shopping Cart Sidebar*]({{ site.baseurl }}{% link sales/cart-sidebar.md %})

|Field|[Scope]({{ site.baseurl }}{% link configuration/scope.md %})|Description|
|--- |--- |--- |
|Display Shopping Cart Sidebar|Store View|Determines if a sidebar appears in the shopping cart. The display of the sidebar depends upon the theme. Options: Yes / No|
|Number of Items to Display Scrollbar|Store View|Determines the number of items that can appear in the sidebar before the scrollbar is triggered.|
|Maximum Number of Items to Display|Store View|Determines the maximum number of items that can appear in the shopping cart sidebar.|

## Payment Failed Emails

![]({{ site.baseurl }}{% link images/images/config-sales-checkout-payment-failed-emails.png %}){: .zoom}
[*Payment Failed Emails*]({{ site.baseurl }}{% link sales/checkout-payment-failed-emails.md %})

|Field|[Scope]({{ site.baseurl }}{% link configuration/scope.md %})|Description|
|--- |--- |--- |
|Payment Failed Email Receiver|Store View|Identifies the store contact who receives Payment Failed emails. Default receiver: General Contact|
|Payment Failed Email Sender|Store View|Identifies the store contact that appears as the message sender of Payment Failed emails. Default sender: General Contact|
|Payment Failed Template|Store View|Identifies the template that is used for Payment Failed emails.  Default template: Payment Failed|
|Send Payment Failed Copy To|Store View|Provides the email address of anyone to receive a copy of a Payment Failed email. Separate multiple addresses with a comma.|
|Send Payment Failed Copy Method|Store View|Indicates the email method used to send the copy. Options: <br />**Bcc** - Sends a blind courtesy copy by including the recipient in the header of the same email that is sent to the customer. The BCC recipient is not visible to the customer. <br />**Separate Email** - Sends the copy as a separate email.|
