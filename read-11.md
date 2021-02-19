Video Series on Styling HTML5 Forms
https://www.youtube.com/playlist?list=PL4cUxeGkcC9g5_p_BVUGWykHfqx6bb7qK
- The first thing I noticed was using square brackets in CSS to select/target an attribute of a particular element. The use of pseudoclass are for targeting elements that are in a certain state. It is interesting to see the use of sprites which are images to style inputs. You can hide the default selectors using opacity 0 and set the background of the radio button to an image.png. 
- Text input styling - Set a span tag with a classname to get a validation mark when correct input is entered. I need to find some stock .png images to use as custom styles to inputs, radio buttons, etc.
- Select elements which are dropdowns. use the appearance: none to remove deafult styling. This has to be done for each browser and webkit.
  - -webkit-appearance: none;
  - -moz-appearance: none;
  - -o-appearance: none;
  - -ms-appearance: none;
- add box shadow to make the element, like a button, appear as though it is 3D, hovering above the page:
  - box-shadow: 1px 3px 5px rgba(0,0,0,0.5);
