<p align="center">
  <a href="https://angularspree.firebaseapp.com/" target='_blank'>
    <img alt="AngualreSpree Logo" title="AngularSpree Logo" src="http://res.cloudinary.com/mally/image/upload/v1490186051/Angular_spree_hqgwtq.png" width="200">
  </a>
</p>

<p align="center">
  AngularSpree Plug and play frontend application for SPREE E-Commerce API built with ❤️ using Angular2, Redux, Observables & ImmutableJs.
</p>

<p align="center">
  <a href="https://angularspree.firebaseapp.com/" target='_blank'>Check demo</a> | <a href="https://aviabird.github.io/angularspree/" target="_blank">Docs </a>
</p>

<p align="center">
  <a href="/CONTRIBUTING.md" target='_blank'><img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"></a>
  <a href="https://www.pivotaltracker.com/n/projects/1985365" target='_blank'><img alt="Pivotal Project page" src="http://res.cloudinary.com/zeus999/image/upload/c_limit,h_1041,w_1487/v1486457388/Yatrum%20Logo/pt-badge_ss3dyt.svg"></a>
</p>

<p align="center">
  <a href="https://teracommerce.in" target="_blank"><img alt="TeraCommerce Bundle" src="https://res.cloudinary.com/ashish173/image/upload/v1506115865/Full_E-COMMERCE_BUNDL_3_km1yzz.jpg"></a>
</p>


### :rocket: **Progressive Web App:** [Lighthouse](https://github.com/GoogleChrome/lighthouse) score of __95/100__.

## What is AngularSpree?

AngularSpree is an open source Angular(2.x+) front-end application for [Spree Commerce](https://github.com/spree/spree). 
**It's free and always will be**. 

**Bootstrap 4 Compatible**

Go ahead use it the way you want to or let us know at `hello@aviabird.com` if you need any help with this project.

<p align="center">
  <a href="https://angular-spree.herokuapp.com/" target='_blank'>
    <img alt="Slack invite Logo" title="Slack invite Logo" src="http://res.cloudinary.com/yatrum/image/upload/v1490434825/slack_vmaait.png" width="300">
  </a>
</p>


## Why did we build it?

We have been working with Spree for very long time, making products for a lot of clients. There was one pattern we noticed in what the clients always asked for. They were comfortable using spree for the backend [API](http://guides.spreecommerce.org/api/) but not for the front-end. These requests have been very consistent with so many awesome [front-end framework](https://github.com/showcases/front-end-javascript-frameworks) around.

When Angular team realeased the beta version in March last year we knew that angular was going to be a big player soon.
We decided to give it a try. Hence, AngularSpree was born as a front-end framework for the most awesome backend api for E-Commerce out there.

🔥🔥🔥🔥🔥🔥🔥🔥🔥

If you are looking to build a project similar to this one with all the ready-made setup, then I highly encourage you to look at this [starter seed project](https://github.com/aviabird/angular-seed) by [Aviabird Team](https://aviabird.com).

**[AngularSeed](https://github.com/aviabird/angular-seed) is a Plug and play Seed project built with ❤️ using Angular 5, Redux/ngrx-store 4, Observables & ImmutableJs. We are commited to keeping this project upto date with all the latest versions of all the libs and components.**

🔥🔥🔥🔥🔥🔥🔥🔥🔥

## What's included?

Currently, this is a fairly basic vesion of the application. We are calling it a pre-alpha release.

### What's working and ready to be deployed?
* Add/Remove products to cart.
* Select/Clear filters based on category.
* Support for product variants.
* Cart checkout feature.
* Cash on delivery option.
* Authentication (Login/Signup)

### What's coming very soon?
* __Angular Universal__ support for better SEO and [much more](https://github.com/angular/angular/issues/13822).
* __Payment__ options credit/debit cards.
* __Multilanguage__ Support i18n.
* More sorting features(new/popular, Discount, Price[low,high]).
* Support for further types of products(size, pattern, collar, etc).
* Support for further options in types eg. size(32, 34, 36) etc. etc.
* Ability to add more than one addresses.
* and many more....

There is a long way to go... keep an eye on this [project](https://github.com/aviabird/angularspree/) here on github.

## Angular 2 Fundamentals course

Based on this application and **[other applications](https://github.com/aviabird/yatrum)** we have built in past we are working on a full blown Angular 2 fundamentals course on udemy. Throughout this course you'll learn how to build yatrum from ground up.

### Course curriculum

* Architecture, setup, source files
* TypeScript basics
* Getting started with latest angular
* Template fundamentals
* Rendering flows
* Component Architecture and Modules
* Services, Http and Observables
* Template Forms, Inputs and Validation
* Reactive Forms and more magic
* Routing

__[Subscribe to this course here](https://upscri.be/a00eaf/)__

## What in the Tech News?

We've built AngularSpree keeping scaling in mind leveraging the best technologies out there.

As of now, the application has 7 major modules, `products`, `core`, `home`, `user`, `checkout`, `auth`, `shared`.

We are working on documentation and we can share that once we are looking at a more stable release.

* Exclusively using @ngrx libraries(store, effects, actions), showcasing common patterns and best practices.
* Fully Observable approach using RxJS 5.0.1(latest beta).
* Uses @ngrx/store to manage the state of the app and to cache requests made to the Backend API, 
* @angular/router to manage navigation between routes, 
* @ngrx/effects to isolate side effects.
* @ngrx/actions to define the actions on the frontend.
* Following Container/Presentation component approach.
* Lazy loading of modules(for modules which are not immediately required for first painting the DOM).
* ImmutableJs to create and safeguard objects againts mutability.
* Project is divided into modules which are more or less independant of each other except core module.

__Current version of Angular is latest release [4.0.0](https://github.com/angular/angular/releases/tag/4.0.0).__

__Current version of Angular-cli is [1.0.0](https://github.com/angular/angular-cli/releases/tag/v1.0.0).__

We try to make sure that we keep the repository upto date with the angular release every weekend.

## Screenshots

### Home Page

On this page user can filter products as per category. Change layout of the products(cozy, comfortable) etc.

<p align="center">
  <a href="https://angularspree.firebaseapp.com/" target="_blank">
    <img alt="AngualreSpree Logo" title="AngularSpree Logo" width="80%" src="http://res.cloudinary.com/yatrum/image/upload/c_limit,h_1041,w_1487/v1490188458/screen_home.png">
  </a>
</p>

### Cart Page

Cart page displays all the line items or items in the cart which the user has added while browsing the website.

<p align="center">
  <a href="https://angularspree.firebaseapp.com/" target="_blank">
    <img alt="AngualreSpree Logo" title="AngularSpree Logo" width="80%" src="http://res.cloudinary.com/yatrum/image/upload/c_limit,h_1041,w_1487/v1490188642/screen_cart.png">
  </a>
</p>

### Product detail page

Display's the detailed product information of a particular product.

<p align="center">
  <a href="https://angularspree.firebaseapp.com/" target="_blank">
    <img alt="AngualreSpree Logo" title="AngularSpree Logo" width="80%" src="http://res.cloudinary.com/yatrum/image/upload/c_limit,h_1041,w_1487/v1490188748/screen_product_page.png">
  </a>
</p>



### Package Manager [Yarn](https://yarnpkg.com/en/)

We are using Yarn as a package manager in this project though you can also use `npm` if you like to.

## Backend for this project?


**Start the API for this project to work successfully.

We have a very thin and custom [repo](https://github.com/aviabird/angularspree-api/) which is the backend for this project. 
Clone it and run the server. We have updated the readme on how to setup the backend API project.

## Contributing to AngularSpree

Where to start

There are many different ways to contribute to AngularSpree's development, just find the one that best fits with your skills. Examples of contributions we would love to receive include:

* Code patches
* Documentation improvements
* Translations(yet to come)
* Bug reports
* Patch reviews
* UI enhancements

Big features are also welcome but if you want to see your contributions included in AngularSpree's codebase we strongly recommend you start by initiating a chat on our __[slack channel](https://angular-spree.herokuapp.com/)__.

## Development server & Mock Api
Run `npm start-mock` for a dev server with 'mock' api. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files and will fetch data from mock api;

## Development server
Run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Development server with Service Worker
Run `npm run build--prod` to build in production with service worker pre-cache and then `npm run static-serve` to serve.

## Build with Service Worker

Run `npm run build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `npm run build--prod` for a production build.


## Who are we?

We are [Aviabird Technologies](https://aviabird.com).

__We love to create awesome Web & Mobile products.__

__We are very proud of our work.__

We love technologies like Golang, Elixir, Scala, Ruby, Javascript, Typescript, Swift, Java.

We love some frameworks too:-
* Ruby On Rails
* Phoenix/Elixir framework.
* Spring framework.
* AngularJs (1.x+ & 2.x+)
* ReactJs
* BackboneJs

### We are available for hire

__If you want to hire us for a project, please contact us on `hello@aviabird.com`.__
