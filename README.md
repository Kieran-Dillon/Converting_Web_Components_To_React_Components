# Converting_Web_Components_To_React_Components

Refactoring is a very important part of development, as new skills are learned we are always thinking of things that can be made more effective, accurate and efficient.

The code I refactored is from the assignment Converting Web Components To React Components. The file is Movie.js which displays a list of movies that I refactored to be simpler and more efficient.

In JavaScript there are common things that can be looked at for refactoring as identified in this article by Fernando Doglio called "Refactoring JavaScript - 5 common problems to look out for and how to fix them":

1) Magic values - plain values used in code that mean nothing, label variables in common understandable language:

The variables used for movies.js were labeled pretty cleanly in the refactored code.

2) Abusing primitive values - create classes and collection of parameters so things can be grouped together:

In movies.js the classes of individual attributes was replaced by data={movie} which contained all the data.attributes to use.

3) Duplicated code - reduce duplication of code by creating functions for reuse:

There was not duplicated code in this simple example, so no refactoring of this type was done.

4) Component independence - reduce complexity by ensuring components are independent where possible:

In this example, there was no refactoring to do for component independence as all the attributes were part of movie card, if there was a combination of book and movie where movie depended on book for an attribute that is where it could be refactored.

5) Callback hell - ensure callbacks are readable back to the calling functions:

There were only a couple of callbacks, so callback hell was not an issue.

Instructions:
Create folder in desired location. Create react app and start npx server in terminal, add files to react app folders. View output in browser.
