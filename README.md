# Angular Product Management Demo App

This is a product management application using Angular.

guide source:

https://www.pluralsight.com/courses/angular-2-getting-started-update


### Part 1

Create a component

Define a linked template in a component product-list

added bootstrap and font-awesome in dependencies

`npm install bootstrap font-awesome`

created product-list.component html and ts

added ProductListComponent in app.module.ts declarations

updated product-list.component.html to display products from ProductListComponent.products

### Part 2

Property binding for images in the product list

Handling events with Event binding for show and hide image button

Handling Input with 2-way binding with the filter by box via ngModel binding

Transforming data with pipes - display price with USD 

### Part 3

defined product interface 

encapsulate product-list.component.css

implement lifecycle hook OnInit

created custom pipe to covert - to spaces

getter-setter for _listFilter

defined performFilter() called onInit and filters product list depending on the input in listFilter