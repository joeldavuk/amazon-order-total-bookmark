# amazon-order-total-bookmark

## How to get total spend on amazon UK?

Simple way to add the order totals by page from the order history page (UK only)

Simply create a new bookmark manually in your favourite browser and add the following as the value, 

```
javascript:var total = 0;jQuery('.a-span2 .value' ).each(function( index ) {total += parseInt(jQuery( this ).text().match(/\d+/),10);});alert("Total spend: £"+total);
```

Alternatively paste the aboe in your address bar then bookmark the current page.

Simple goto the bookmark when your on the order history page, or drag it onto your toolbar. Note this only total's the current page. So you would need to go through each page and add up the totals to get an absolute total for the period you need.

