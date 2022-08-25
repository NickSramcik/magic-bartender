# Cocktail Recipe API

This "magic bartender" features a web API that allows users to search for cocktails to recieve an image, name, ingredients, and instructions for how to make the cocktail themselves. Great for someone who's interested in learning to make new drinks at home!  

**Link to project:** https://magic-bartender.netlify.app/

<!-- ![alt tag](Image needed!) -->

## How It's Made:

**Tech used:** HTML, CSS, JavaScript

This web application integrates the cocktail web API with some front-end javascript. An event listener sends a request to the API using the contents inside the search form, and changes hidden elements inside the DOM to display data that the API responds back with. 

## Optimizations

This project could be improved by refactoring it into a full-stack application, which would give me more control over how the requests are handled. Running this website as a full-stack app would allow me to more easily add support for form submission, as it currently only works on-click of the submission button. Additionally, I would like to add better support for searches that result with multiple cocktails, such as a rotating carosel that the user can navigate through. 

## Lessons Learned:

This project was an early attempt at web API integration, and along the way I ended up learning how to make some weird cocktails I had never heard of! There were a few interesting hurdles to get across in order to make user inputs play nicely with the web API. The input text needs to be manipulated before it's sent off in each server request to work correctly, because the API expects very specific formatting and casing. 
