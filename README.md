# module2-project-angel

## Which 3rd party API I'm using
www.google.com/orangechair/resaurants/

## Problem statement (which problem I am trying to solve)
An apps that finds restaurant. The problem is that some users want only restaurants with orange chairs.

## Target users (who are the people who's problem I'm trying to solve)
The target users are people who really REALLY love orange chairs.

## Wireframe
* In your wireframe/drawings we want to see you actually write out which components are stateful and which aren't

2 Stateful components
5 functional components (presentational components / no stateful logic)

App.js (stateful) -> users signup form (stateful) -> confirmation box/lightboxes/modal (functional/presentational)

Lets say once they confirm their info I take them to another page. And show them <Restaurants /> 

Restaurants is stateful because it has to make an API call and then render the info from API call

restaurants (stateful) -> restaurant (presentational)