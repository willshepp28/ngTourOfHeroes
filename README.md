# AngularTourOfHeroes

`ng new 'newProject' :` creates a new angualar application

`ng serve --open :` starts the sever and opens browser to localhost:4200

Components are the fundamental building blocs of Angular applications. They display data on the
screen, listen for user input, and take action based on that input.

`{{ example }} :` the double curly braces are Angulars interpolation binding syntax

1. Put application-wide styles in src/styles.css

`ng g c 'name'` : generates a new Components

`@Component`: is a decorator function that specifies the angular metadata for the Component

## Three metadata properites in @Component decorator
 - selector - the components CSS element selector
 - templateUrl - the location of the components template file


 `Pipes`: are a good way to format strings, currency amounts, dates and other display data. Angular ships with several built-in pipes and you can create your own.