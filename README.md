# Freshcart

E-commerce storefront built with Angular 18. This is a frontend project: I built the UI and client-side logic on top of an existing, ready-made REST API. I did not write the API.

## Features

- Authentication: login, register, forgot and reset password, profile update
- Products and brands: search by name or category, product details, paginated lists
- Cart and wishlist: add, remove, clear
- Categories and subcategories
- Stripe payment integration

## What I built

- Route guards, HTTP interceptors, pipes and directives
- State sharing with RxJS and BehaviorSubject
- Reactive Forms with validation
- JWT decoding for the signed-in user (jwt-decode)
- UI with Bootstrap, ngx-spinner, ngx-toastr, ngx-pagination and ngx-owl-carousel-o

## Tech stack

Angular 18, TypeScript, RxJS, Bootstrap 5, Font Awesome

## Run locally

```sh
git clone https://github.com/mohamedelhelaly02/fresh-cart.git
cd fresh-cart
npm install
ng serve
```

Open http://localhost:4200
