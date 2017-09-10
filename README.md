# Recipe Helper

This is a SPA to help users keep track of their own personal recipes and grocery list

## Core Features

### Built with Angular4

This application is build with cutting edge Angular4 with the latest features

### Reactive Forms

There are many robust forms used in this application to allow users to input data. I use Angular reactive forms to 
validate and propagate the form controls. For example, the grocery list is very intuitive and easy to use because the 
user can directly modify the grocery list items. In many apps, you must click an add button or edit button to start
working. In this app, you simply click on the item you wish to edit. The shopping list emulates the checklist in google
keep.

### User Authentication

Each users has his/her own set of recipes and grocery list that they can modify at will and save. This is made possible
 by storing the data using AJAX calls
to a firebase backend server. While I usually create by own backend API services, I decided to use Firebase for this
project as it is an incredibly easy to use a robust service. 

### Responsive

The layout is responsive to screen size. The layout follows the golden ratio design philosophy and includes custom
breakpoints using media queries. The layout is implemented using css flex-box.

### Material Design

The application was designed with material design principles in mind. Everything is minimalistic and follows the paper
spec as much as possible. Some components are modified versions of Angular Material2 components and some of them were
custom coded/designed by me.
