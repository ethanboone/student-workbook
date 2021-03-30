# Day 1
https://ethanboone.github.io/AfternoonChallengeWeek3Day1/
## Daily Journal
Read Advancing with JS > ES6 modules and answer the following questions
1. What problem does using exports solve?
Exports solves the issue with load time with using multiple script tags. Prior to ES2015, developers had to either use external libraries for modules or include multiple script sources in the html document.
2. How does export differ from export default?
Default exports are better for exporting single modules into your code, and the module can be given an alias when importing to other javascript files. Standard exports are more often used for exporting more than one object or piece of data, and can also be given an alias but you must use the "as" keyword in your import.
3. What is a benefit of using the Module System?
Some benefits to using modules in javascript are that they increase application performance, can split your program into multiple files for better organization, as well as making debugging your code easier.