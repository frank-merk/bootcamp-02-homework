# Bootcamp 02-Homework Assignment: Code Refactoring

##Description

This week's homework assignment was to refactor code for a digital services company called Horiseon. The primary goal of the assignment were to improve the website's **accessibility** while also following the **scout rule** of leaving the code a little cleaner than it was found. To accomplish this task, the following improvements were made:

  * Added accessible 'alt' attributes to all image elements.
  * Replaced div elements with relevant semantic html elements.
  * Restructured styles.css to align with the flow of the html document.
  * Eliminated redundancy in styling whenever possible.
  * Left comments throughout the codebase to describe what the code was doing.
  
##A Note on Styling Strategy

There were many ways to structure this webpage using semantic html and CSS. In order to keep the code as clean as possible, I opted to eliminate classes when applicable and focus instead on styling the semantic html elements like *section*, *aside*, *article*, and so on. Across the homepage I found a lot of replicated styles and redundancies across classes that could be simply contained within the style of a given html element.

My strategy greatly reduced the number of class callouts within the main html file and works clean on a single page. However, the drawback of this strategy is less scalable and flexible if the styles were to be applied to other pages across the website. If I was designing a larger website, I would likely add fewer styles to the semantic html elements and let classes do more of the heavy lifting.


