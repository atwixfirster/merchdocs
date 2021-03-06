---
title: Reports Menu
---

Magento provides a wide selection of reports to keep you informed on your marketing efforts, sales products, and customer activity. The Reports menu provides easy access to current information about your sales, products, customers, and promotions.

<!--{% if "Default.CE Only" contains site.edition %}-->

![]({{ site.baseurl }}{% link images/images/admin-menu-reports.png %}){: .zoom}
*Reports Menu*
<!--{% endif %}-->

<!--{% if "Default.EE-B2B" contains site.edition %}-->

![]({{ site.baseurl }}{% link images/images-ee/admin-menu-reports-ee.png %}){: .zoom}
*Reports Menu*
<!--{% endif %}-->

## To display the Reports menu:

On the Admin sidebar, tap <span class="btn"> Reports </span>.

### Menu Options

## [Marketing]({{ site.baseurl }}{% link reports/marketing-reports.md %})

A selection of marketing reports, including Products in Cart, Search Terms, Abandoned Carts, and Newsletter Problem Reports.

## [Reviews]({{ site.baseurl }}{% link reports/review-reports.md %})

The selection of product review reports includes By Customer and By Product.

## [Sales]({{ site.baseurl }}{% link reports/sales-reports.md %})

The selection of sales reports includes Orders, Tax, Invoiced, Shipping, Refunds, Coupons, and settlement reports for PayPal and Braintree.

## [Customers]({{ site.baseurl }}{% link reports/customer-reports.md %})

{% if "Default.CE Only" contains site.edition %}The selection of customer reports includes Order Total, Order Account, and New. {% endif %}
{% if "Default.EE-B2B" contains site.edition %}The selection of customer reports includes Order Total, Order Account, New, Wish Lists, and Segments.{% endif %}

## [Products]({{ site.baseurl }}{% link reports/product-reports.md %})

The selection of product reports includes Views, Bestsellers, Low Stock, Ordered, and Downloads.

<!--{% if "Default.EE-B2B" contains site.edition %}-->

## [Private Sales]({{ site.baseurl }}{% link reports/statistics.md %})

The selection of reports for private sales and events includes Invitation, Invited Customers, and Conversions.
<!--{% endif %}-->

## [Statistics]({{ site.baseurl }}{% link reports/statistics.md %})

Statistics is a tool that reduces the performance impact of generating reports by calculating and storing statistical data. Rather than recalculate the statistics every time a report is generated, the stored statistics are used until you refresh the statistics.

## [Business Intelligence]({{ site.baseurl }}{% link reports/business-intelligence.md %})

The [Advanced Reporting]({{ site.baseurl }}{% link reports/advanced-reporting.md %})
dashboard gives you valuable insight with a dynamic set of product, order, and customer reports, powered by Magento Business Intelligence. for more sophisticated reporting and analysis, sign up for a free trial of [BI-Essentials]({{ site.baseurl }}{% link reports/bi-essentials.md %}).
