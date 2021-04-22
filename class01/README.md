# Reading Notes

# Class 01 - Review, Research, and Discussion

## Describe Array.map()

Array.map is a JavaScript method that will traverse an array and return a new array with different values depending on how you interact with each value in the array. An example of this in use would be taking an array of todo items, appending <li></li> tags around each value and then converting the array to a string in order to display the list of todo items in page. 

## Describe Array.reduce()

Array.reduce is a Javascript method that will traverse an array and interact with each value in the array in order to return a new type of data. Using reduce, you can turn an array into a string, number, object etc. An example of this would be taking a list of numbers and performing the reduce method to identify the max value in an array.

## How to use superagent?

**superagent with Promises**
```
 superagent.get("https://swapi.dev.api/people/1/").then(data => {
     console.log(data);
 });
```

**Superagent with Async/Await**

```
    function getCityName = async (cityName) => {
        let cityData = await superagent.get(`https://geocode.xyz/${cityName}?json=1`);

        console.log(cityData);
    }

    getCityName();

```

## Explain Promises

In Javascript, there are times where you need to make a request to an api or a database to retrieve data for your application. When making these requests, it takes time until we actually receive the data. Because of this Javascript performs these requests asynchronously which basically means taking this function call out of the normal call stack and putting it to the side so other functions can also run in the application. However we still need a way to retrieve that data when the request is finished. This is where Promises come in. Promises will wait for that request to complete and then execute the code interacting with the data received.

## Are all callback functions considered to be Asynchronous? Why or Why Not?

All callback functions are not considered Asynchronous. If you have a parent function with a callback as an argument, and in both scenarios just console.logging a simple line of code, the callback will always return before the parent function. This is because the parent cannot finish executing until the callback has finished. However, if you put the callback into an asynchronous state, for example using setTimeout, then the parent function will return first.

Resource - [https://medium.com/@pravngaur/callbacks-synchronous-asynchronous-62bac2b8fe85](https://medium.com/@pravngaur/callbacks-synchronous-asynchronous-62bac2b8fe85)