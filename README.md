# Template of an Angular application with the configured "function-plot" library

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.0.

<hr>

IMPORTANT: for proper working of 
"function-plot" there was added in "head" 
of [index.html](src/index.html) the following script:

```js
if (global === undefined) {
    var global = window;
}
```

Without this script there is "Uncaught ReferenceError: global is not defined"

<hr>

## Building a Dynamic plot

As it was made by the "function-plot" creator in his site 
[Integral - Mauricio Poppe](https://www.mauriciopoppe.com/notes/mathematics/calculus/integral/#area-as-the-limit-of-the-sum)
#sum-area plot is rebuilt each time the slider changes its value.

Here is the source of #sum-area: [integral.js#L83](https://github.com/mauriciopoppe/blog/blob/master/site/static/js/calculus/integral.js#L83)
