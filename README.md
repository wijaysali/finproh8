## Requirements

FinProH8 is a simple App to show Movies List From 3rd Parties Data. Please note this requirements as well as your final project appraisal.

1. Using create-react-app
2. Get Movies from http://www.omdbapi.com/ 
   Get API_KEY from http://www.omdbapi.com/apikey.aspx using fetch or axios allowed.
3. Simplied your react state into functional component using react-hooks applied (UseState, useEffect, useReducer).
4. Functional Component Based, details : 

i.App.js — It will be the parent component for the other 3. It will also contain the function that handles the API request and it will have  a function that calls the API during the component’s initial render.

ii. Header.js — A simple component that renders the app header and accepts a title prop

iii. Movie.js — It renders each movie. The movie object is simply passed into it as props.

iv. Search.js — Contains a form with the input element and the search button, contains functions that handle the input element and resets the field, and also contains a function that calls the search function which is passed as props to it.


##Q&A 

Q : Does the Final Project only like the demo ? 
A : Yes, it does. If you want try anything seems like details it would be good

Q : Does the Interface must applied like the demo ? 
A : No, The interface on demo just like your reference UI, if you want to custom to another UI is allowing as long you must get attention from requirement section. 

Q : Does 3rd Parties Sync only OMDB ? 
A : Yes, but if you want try others 3rd parties is allowing as long you must applied it as requirement above.

It must be simple, so you must be careful with your syntax or code. Be Sure your app is suitable with the requirement above, because we do check your code/syntax with the rubrik (requirement applied). So MAKE IT PERFECT ! 

## Installation Instructions
1. Run ```git clone```
2. Run ```cd react-movie-app```
3. Run ```yarn install```
4. Run ```yarn start```



