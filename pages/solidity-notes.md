## Anatomy of a Function

```js
function functionName(uint x, uint y) public view returns (uint){ 
// function body here
}
```

Every function must begin with the keyword `function`, followed by its name `functionName`. The auguements are passed in the function inside the brackets along with the datatype.

`Public view returns` states the **visibility** of the function. Keyword `public` defines that it can be accessible to the other contracts. 

The function will not to modify the state of the blockchain,since it uses the word `view`.

Finally, `returns` defines that the function will return a value, and also defines the data type of that output.