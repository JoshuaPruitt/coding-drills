
<br/>

## Problem

1. You've recently updated your Macbook to the latest release of macOS and suddenly can no longer push or pull to your github repositories. 

#### What I searched: 
    can no longer push or pull repository after mac update

#### Answer(s) I got:
* Use "brew install openssh" to install git using homebrew as the Monterey update seems to ruin git.
* Another fix may be to install an older version of sourcetree

## Problem 

2. You've suddenly forgetten the syntax for using switch cases

#### What I searched: 
    Switch Cases JavaScript

#### Answer(s) I got:
````
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
````
This is the syntax for a switch case in JavaScript. 
## Problem 

3. You're feeling a bit creative and want to give your navigation some cool hover effects

#### What I searched: 
    Navigation hover effects

#### Answer(s) I got:
    https://codepen.io/maheshambure21/pen/QwXaRw
    https://dev.to/kiranrajvjd/10-simple-navigation-bar-hover-animations-1980

These two sites both contain code for mutiple navigation hover effects. Some of the examples are Circle Fill, Underline Stroke, and Underline Fill.

## Problem
4. You've been working with APIs but got this error code when trying to make an AJAX call
    ```
    XMLHttpRequest cannot load http://myApiUrl.io/apiKey=Ajd234mifs04?query=cats No 'Access-Control-Allow-Origin' header is present on the requested resource. Origin 'null' is therefore not allowed access.
    ```

#### What I Searched:
    No 'Access-Control-Allow-Origin' header is present on the requested resource. Origin 'null' is therefore not allowed access

#### Answer(s) I Got:
    1.Use a reverse proxy server or WSGI server(such as Nginx or Apache) to proxy requests to your resource and handle the OPTIONS method in the proxy.
    2.Add support for handling the OPTIONS method in the resource's code.

## Problem
5. You've been using jQuery to create on click listener for some buttons `$('.btn').on('click', function(){//does something})`, however another function is creating new buttons and your on.click listener is not working on the newer buttons

#### What I Searched:
    jquery not working on new buttons

#### Answer(s) I got:
A solutution may be to change 
````
$('.btn').on('click', function(){//does something})
````
to 
````
$(body).on('click', '.btn', function(e){
    
}
````

## Problem
6. You've made an AJAX call to an API endpoint that is supposed to return data that you can append to your HTML, but for some reason no data is being appended.

#### What I searched:

#### Answer(s) I got:

## Problem
7. You want to double check the syntax for the `.forEach` method, but don't trust W3Schools and only want results for Mozilla

#### What I searched:

    Mozilla Web Docs .forEach

#### Answer(s) I got:
````
forEach(callback)
forEach(callback, thisArg)
````
This is the syntax for the `.forEach` Node

## Problem
8. You used the `.sort` method on an array of numbers `[1, 6, 5, 11, 34, 2]`, but for some reason it's sorting it incorrectly and gives you `[1, 11, 2, 34, 5, 6]` instead

#### What I searched:
    '.sort" not sorting numbers correctly

#### Answer(s) I got:
    http://www.javascriptkit.com/javatutors/arraysort.shtml
````
var myarray=[1, 6, 5, 11, 34, 2]
myarray.sort(function(a,b){ //Array now becomes [1, 2, 5, 6, 11, 34]
    return a - b
})
````
By changing it to have additional information it should now sort an array into numerical order
## Problem
9. You made some sick animations using CSS and they look great on Chrome, but you viewed them on a friend's computer who uses Firefox and they're not working

#### What I Searched:

    animations that work on chrome dont work on firefox

#### Answer(s) I got:

The 'setTimeout' function can be used to put the animation into the callStack which will let the animation go through when all other animations have finished. 

## Problem
10. You have an array of names `[Sasha, Jimmy, Amber, Robert]` and have created a function that uses a for loop to console log each name in the array after a set amount of time using `setTimeout`, but for some reason it is console logging undefined.

#### What I searched:
    settimeout console log undefined

#### Answer(s) I got:

`setTimeout(() => {` instead of `setTimeout(function() => {:`

you can try adding an arrow function after setTimeout to keep the scope of the array.