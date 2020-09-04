# Angular Crash Course

## Tutorial By Traversy Media :octocat: - https://www.youtube.com/watch?v=Fdf5aTYRW0E

## What Is Angular?
 - Angular is a full featured  __JavaScript framework__ created & maintained by Google and is used for building front-end applications or the front-end part of a full stack application
 - Angular is very popular in large enterprise

## A Note On Versions
 - **AngularJS** was released in 2010. It is not recommended and should be updated to **Angular**
 - Angular refers to version 2+. Right now we are on version 7, but 2-7 is the same framework with a few changes, mostly the underhood.

## Why Use Angular?
 - Organized front-end structure (Components, Modules, Services)
 - Extremely powerful & full featured
 - All-in-one solution (Routing, HTTP, RxJS, etc)
 - Build powerful SPA apps 
 - MVC - Model, View, Controller design pattern
 - TypeScript
 - Fantastic CLI

## The Angular Way
 - Uses TypeScript for static types (variables, functions, params)
 - Component based (Like other frameworks)
 - Uses "services" to share data/functionality between components 
 - Concept of "modules" (root module, forms module, http module, etc)
 - Uses RxJS "observables" for async operations
 - Steep learning curve relative to other frameworks

## Angular CLI 
 - Power tool for generating apps, modules, components, services, etc.
 ```javascript
 $ng new myapp
 $ng serve
 $ng build

 //
 
 ng generate component todos
 ng generate service todo
 ng generate module app-routing

 ```

## Note On State Management
 - You can use state managers like ngrx and Redux with Angular for larger apps
 - I find less necessary due to the overall structure of the framework and services which are used to share data and functionality.