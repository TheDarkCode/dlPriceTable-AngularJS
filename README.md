# dlPriceTable-AngularJS
Barebones example to generate price tables with AngularJS.

Dependencies: xeditable.

Some functionality is only set up for you to add yourself. Simple ways to change the look of the price table using attributes such as title, price, route, buttoncolor, buttontext, color, features, theme, and custom classes on ```<dl-price-table> </dl-price-table>```.


# Sample Usage
```html
<div class="panel panel-default">
    <div class="panel-heading">
        Sample Price Tables
    </div>
    <div class="panel panel-body">
            <dl-price-table title="Sample Product"
                            price="$199"
                            route="#"
                            buttoncolor="warning"
                            buttontext="Buy Now!"
                            color="red"
                            features="['Feature 1', 'Feature 2', 'Feature 3']"></dl-price-table>
            <dl-price-table title="Sample Product"
                            price="$199"
                            route="#"
                            buttoncolor="warning"
                            buttontext="Buy Now!"
                            color="green"
                            features="['Feature 1', 'Feature 2', 'Feature 3']"></dl-price-table>
            <dl-price-table title="Sample Product"
                            price="$199"
                            route="#"
                            buttoncolor="warning"
                            buttontext="Buy Now!"
                            color="blue"
                            features="['Feature 1', 'Feature 2', 'Feature 3']"></dl-price-table>
            <dl-price-table title="Sample Product"
                            price="$199"
                            route="#"
                            buttoncolor="warning"
                            buttontext="Buy Now!"
                            color="grey"
                            features="['Feature 1', 'Feature 2', 'Feature 3']"></dl-price-table>

    </div>
</div>
```
