<h1 align="center">
  Javascript Array CheatsheetπΎ
</h1>

![image](Cheatsheet.png)

<h2 align="center">
<a href="Cheatsheet.png" download>Click to download β</a>
</h2>

```
/******************STATIC PROPERTIES*******************/

Array.from('πππ'); //  Creates an Array from a String, output: ["π", "π", "π"] //

Array.isArray(['π', 'π', 'π']); // check for an array, output : true //

Array.of('π', 'π', 'π'); // creates a new Array with provided elements output:["π", "π", "π"] //

/******************INSTANCE PROPERTIES*******************/

['π', 'π'].concat(['π', 'π₯­']); // Joins Two arrays, Output : ["π", "π", "π", "π₯­"]  //

['π', 'π', 'π', 'π₯­'].copyWithin(2, 0); //copy first 2 array elements to last 2, output: ["π", "π", "π","π"] //

['π', 'π', 'π'].filter(emoji => emoji === 'π'); // Returns the array that matches our test output : ["π"] //

['π', 'π', 'π'].fill('π'); // fill all the array elements with "π", Output : ["π","π","π"] //

['π', 'π', 'π'].find(emoji => emoji === 'π'); // element in the array that has a value of "π", output : "π" //

['π', 'π', 'π'].indexOf('π'); // get the index of  π, output: 1 //

['π', 'π', 'π'].findIndex(emoji => emoji === 'π'); // returns the index of the first element  that satisfies the provided testing function. π, output: 1 //

['π', 'π', 'π'].forEach(emoji => console.log(emoji)); //  executes a provided function once for each array element, output :πππ //

['π', 'π', 'π'].map(emoji => emoji + π); // Creates a new array by replacing with the return of a function for each array element, output: [ππ, ππ , ππ]

['π', 'π', 'π'].every(emoji => emoji === 'π'); // Check if every element in the array has a value π, Output : false //

['π', 'π', 'π'].some(emoji => emoji === 'π'); // Check if atleast one element in the array has a value π, Output : true //

['π', 'π', 'π'].includes('π₯­'); // Check if the fruit array contains "π₯­", output : false //

['π', 'π', 'π'].join(' + '); // Joins all elements of an array into a string, output : "π + π + π"//

['π', 'π', 'π'].pop(); // Removes and return the last element of an array, output: "π" //

['π', 'π', 'π'].push('π'); // Adds new elements to the end of an array and returns length, output: 4 //

['π', 'π', 'π'].reverse(); // Reverses the order of the elements in an array, output: ["π", "π", "π"] //

['π', 'π', 'π'].splice(1, 2); // Adds/Removes elements output: (removed array) ["π", "π"]  (new array) ["π"] //

['π', 'π', 'π'].slice(1, 2); // Selects a part of an array, and returns the new array, output: ["π"] //

['π', 'π', 'π'].toString(); // Converts an array to a string, and returns the result, output:"π,π,π" //

['π', 'π', 'π'].shift(); // Removes the first element of an array, and returns that element, output: "π" //

['π', 'π', 'π'].unshift('π'); // Adds new elements to the beginning and returns the new length, output: 4 //

['π', 'π', 'π'].reduce((acc, cur) => acc + cur, 'π'); //Reduce the values of an array to a single value, output: "ππππ"//

```


## Important π¨

There is no way this is perfect or include all the methods. I'll try to fix/add more methods.For Now I have added only that methods that I knew about. Thanks for sparing your time and  dropping by. Drop a star if this helped you β¨ and share with someone who could use this. Have a great day π¦ .
