<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
.row {
  display: flex;
  width: 80%;
  margin: 0 auto;
}
.column {
  flex: 50%;
  border: 1px solid red;
}
[class^='product']{
    padding:50px;
}
.product-2,.product-3{
    height:50%;
}
.product-2{
    border-bottom: 1px solid red;
}
.product-1{
    text-align: center;
}
.img-container{
    margin: 0 auto;
    background: #ccc;
}
.img-container img{
    width: 100%;
}
.product-1 .img-container{
    width: 400px;
    height: 400px;
}
.product-2 .img-container, .product-3 .img-container{
    width: 200px;
    height: 200px;
}
.col-6{
    width: 50%;
    float: left;
}
</style>
</head>
<body>
<div class="row">
  <div class="column">
        <div class="product-1">
            <div class="img-container">
                <img src="" class="img-fluid">
            </div>
            <h2>Product Name XYZ awiudoiauwdouw</h2>
            <p>Price Information</p>
            <button>Book Now</button>
            <button>Buy Now</button>
        </div>
  </div>
  <div class="column">
  <div class="product-2">
    <div class="img-container col-6">
        <img src="" class="img-fluid">
    </div>
    <div class="product-info col-6">
        <h2>Product Name</h2>
        <p>Price Information</p>
        <button>Book Now</button>
        <button>Buy Now</button>
    </div>
    </div>
  <div class="product-3">
    <div class="img-container col-6">
        <img src="" class="img-fluid">
    </div>
    <div class="product-info col-6">
        <h2>Product Name</h2>
        <p>Price Information</p>
        <button>Book Now</button>
        <button>Buy Now</button>
    </div>
    </div>
  </div>
</div>

</body>
</html>
