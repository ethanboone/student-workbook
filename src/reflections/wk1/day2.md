# Day 2

## Daily Journal
Read Building Blocks Of Web Development > CSS and answer the following questions
1. What is a Pseudo-Class and what are some of the most common ones you think you will use?
A pseudo class is a unique style added to an html element when the specified condition is applicable. A commonly used pseudo class is element:hover. This adds properties to the element when the user hovers over it. Often times, the hover pseudo class changes the color of the background and text on the element.
2. What is Specificity and how might you use it to your benefit?
Specifity is the number assigned to a CSS rule that determines what style will be applied to the element. Specifity is useful when you need to add styling to an element with the exception of a few specific nested elements. A developer would then use the CSS .class syntax to affect the nested elements as adding style to a class has a specificity of 10 and a standard CSS rule would be 1.
3. What problems do you think you could run into if you over-utilized the `!important` feature?
Overusing !important would make it increasingly more tedious to modify styling. You would have to individually change each !important property as it overrides the specificity of the initial rules in the CSS code, similar to the way inline-style overrides the CSS rule. However, the style utilizing !important would remain if inline-style affected the same element.
