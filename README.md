# Final Project Template [Replace with your project name]

## Overview

This will be where you put all the information for your final project. In this section describe your project, who might use your app, and why would they use it (can be completed at the end).

## Part I - Choose API

Use the below site to choose an API to work with

https://github.com/public-apis/public-apis

Whether you choose one from the list above or find another API, I would recommend it meets the following criteria

- Uses an api-key or is open (No OAuth)
- Does not require a credit card (which means it should be free)
- Has good documentation with examples

Make sure you can actually grab data from your API. Use this code to test your API. You can plug it into your previous project or place it into a console in your browser 
```
const url = `INSERT URL HERE`;
const options = {
   method: "GET",
};

fetch(url, options)
  .then((response) =>
    response.json().then((result) => {
       console.log(result);
    })
   )
   .catch((error) => {
    console.log(error);
  });
```

### Chosen API

[Replace this with your chosen API]

## Part II - Flush out requirements

Now that you've chosen your API, make sure you have a plan to meet the requirements. Answer the following questions in the README

What is going to be your list (e.g. quotes from QuoteGenerator, fiveDayForecasts from Weather app)?

What is going to be your function with a parameter (e.g. loadQuotesByTags with the parameter event in Quote Generator, getFiveDayForecast with the parameter locationKey in Weather App)?. Describe how you are going to use the parameter in your code.

What is going to be your loop (e.g. loop to display quotes in QuoteGenerator, loop to display fiveDayForecast in Weather App)?

## Part III - Design HTML

Use [Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/) to design your HTML. Make sure it is visually appealing. Use dummy images and [Lorem Ipsum](https://loremipsum.io/) if needed to use as placeholders

## Part IV - Code up app

Finish coding up the app. **DO NOT** use generative AI. Look at previous projects for examples on how to meet the requirements. If you use any other resources please cite them below.

Remember to run your project first run the command

`npm install`

then

`node server.js`

### External Resources
