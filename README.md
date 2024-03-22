"Ecommerce App with Angular | Angular 17 Project | Admin Application" by Learning Partner on YouTube

https://www.youtube.com/watch?v=hejR2GfFXiA&t=652s

Source Code

https://github.com/voidChetan/bigbasket_ecommerce_angular

www.bigbasket.com

Fruitable - Vegetable Website

https://themewagon.github.io/fruitables/

** install Bootstrap 5 

npm i bootstrap@5

angular.json file add to styles
"./node_modules/bootstrap/dist/css/bootstrap.min.css",

** install PrimeNG and PrimeIcons

npm install primeng primeicons

  "node_modules/primeng/resources/themes/lara-light-indigo/theme.css",
  "node_modules/primeng/resources/primeng.min.css",
  "node_modules/primeicons/primeicons.css"

** install NGX Toastr

npm install ngx-toastr --save 

"node_modules/ngx-toastr/toastr.css",

** install quill

npm install ngx-quill

# admin

ng g c pages/admin/cart

ng g c pages/admin/categories

ng g c pages/admin/customer

ng g c pages/admin/layout

ng g c pages/admin/login

ng g c pages/admin/order

ng g c pages/admin/products

# website

ng g c pages/website/category-products

ng g c pages/website/checkout

ng g c pages/website/customer-cart

ng g c pages/website/customer-orders

ng g c pages/website/footer

ng g c pages/website/landing

ng g c pages/website/web-products
 
# services

services/constant/constant.ts

ng g s services/login

ng g s services/product

# shared

ng g c shared/components/card/card

ng g c shared/components/card/offer-card

ng g guard shared/guards/auth

ng g interceptor shared/interceptors/custom

ng g interceptor shared/interceptors/error

ng g pipe shared/pipes/truncate


ng s -o

http://localhost:4200/login


https://codepen.io/

login page code

login.component.html and css


** make a user model **
(class and interface)

getting a Bootstrap navbar from w3schools.com for layout component

used Bootstrap cards from w3schools.com within products component


