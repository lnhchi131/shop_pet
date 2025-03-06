## About Shop Pet


Shop Pet is a pet store management website

Link demo: httpshttps//www.youtube.com/watch?v=xaKk8URDWW4

## Features

### User Functions
- Register and login
- Search, view products, and details
- Add to cart and checkout
- View order history and status
- Payment via COD and VNPAY

### Admin Functions
- Admin login
- Dashboard overview
- Manage orders, products, and categories
- CRUD operations (*add, edit, delete, search*)
- Revenue statistics

## Installation & Setup

Clone Repository:

    git clone https://github.com/lnhchi131/shop_pet.git
    cd shop_pet
    cd shopthucung_laravellaravel

Install Dependencies:

    composer install

Configure Environment:

    cp .env.example .env
    php artisan key:generate

Database Setup
Edit the .env file with database credentials and run:

    php artisan migrate --seed

Run the Server

    php artisan serve

Visit: 

    http://localhost:8000


## Functional Diagram
![Sơ đồ chức năng](img/Sơ%20Đồ%20Chức%20Năng.png)

## Flowchart 
![Quy trình đăng nhập đăng ký](img/Quy%20trình%20đặp%20nhập%20đăng%20ký.png)


![](img/Quy%20trình%20duyệt%20sản%20phẩm.png)


![](img/Quy%20trình%20xem%20sản%20phẩm%20chi%20tiết%20.png)


![](img/Quy%20trình%20đặt%20hàng%20và%20thanh%20%20toán.png)


![](img/Quy%20trình%20theo%20dỗi%20Đơn%20hàng.png)

### Website screenshot

| Login  |  Home
|:-:|:-:|
| ![login](img/login.png) | ![home](img/home.png) |

| Product  |  Cart
|:-:|:-:|
| ![product](img/product.png) | ![cart](img/cart.png) |

| Orderss List  |  Filter
|:-:|:-:|
| ![order](img/order.png) | ![filter](img/filter.png) |

| Admin  |  Products  Management
|:-:|:-:|
| ![adminadmin](img/admin.png) | ![prodcuts_managementmanagement](img/product_management.jpg) |

| Categories  |  Order Management
|:-:|:-:|
| ![Categories ](img/categories.jpg) | ![Order Management](img/order_management.jpg) |