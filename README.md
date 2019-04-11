<!doctype html>
<html>
    <head>
        <style>
            *{
                box-sizing: border-box;
            }
            .col-6{
                width: 50%;
            }
            .new-arrival{
                display: flex;
                border: 1px solid #ccc;
            }
            .product{
                padding:40px;
                display: flex;
                flex-wrap: wrap;
                place-content: center;
                width: 100%;
            }
            .product-container-2 .product {
                height: 50%;
            }
            .new-arrival .product-container-1{
                border-right: 1px solid #ccc;
                display: flex;
            }
            .new-arrival .product-container-2 .product:first-child{
                border-bottom: 1px solid #ccc;
            }
        </style>
    </head>
    <body>
        <div class="new-arrival">
                <div class="product-container-1 col-6">
                    <div class="product">text text kauywdu awldhua ydiuwaid uwaiduiwa ud
                    </div>
                </div>
                <div class="product-container-2 col-6">
                    <div class="product">text</div>
                    <div class="product">text</div>
                </div>
        </div>
    </body>
</html>
