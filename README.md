# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products Page</title>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    /* Custom styles */
    .product-card {
      border: 1px solid #ccc;
      border-radius: 5px;
      padding: 10px;
      margin-bottom: 20px;
    }
    .product-img {
      width: 100%;
      height: auto;
    }
    .product-price {
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="container mt-5">
    <h1 class="text-center mb-4">Our Products</h1>
    <div class="row">
      <div class="col-md-4">
        <div class="product-card">
          <img src="q1.webp" alt="Product 1" class="product-img">
          <h4 class="mt-2">Product 1</h4>
          <p>Description of Product 1</p>
          <p class="product-price">$50</p>
          <button class="btn btn-primary">Add to Cart</button>
        </div>
      </div>
      <div class="col-md-4">
        <div class="product-card">
          <img src="q2.jpeg" alt="Product 2" class="product-img">
          <h4 class="mt-2">Product 2</h4>
          <p>Description of Product 2</p>
          <p class="product-price">$80</p>
          <button class="btn btn-primary">Add to Cart</button>
        </div>
      </div>
      <div class="col-md-4">
        <div class="product-card">
          <img src="q3.jpeg" alt="Product 3" class="product-img">
          <h4 class="mt-2">Product 3</h4>
          <p>Description of Product 3</p>
          <p class="product-price">$100</p>
          <button class="btn btn-primary">Add to Cart</button>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
```


## OUTPUT:

![alt text](<Screenshot 2024-05-11 083233.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
