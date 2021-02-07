# From the Duckett HTML book:

## Chapter 5: “Images” (pp.94-125)
- The ``<img>`` element is used to add an image to the page
    - images should math the color palette of the site
    - search for free stock images website
- Storing Images
    - images should be stored in their own directory and if there are several categories of images they should go in sub-directories
- height and width of images can be set as an attribute in the image element width="" height=""
- all img elements must have src="" to indicate the source of the image. And and alt="" to describe the image for accessability purposes
- best practice is to format the image to the proper size prior to saving it in the directory
    - measure images in pixels
- use .png format for transparency
- photos should be .jpg and logos should be .gif or .png

## Chapter 11: “Color” (pp.246-263)
- Four ways to specify color:
    1) RGB
    2) hex codes
    3) color name
    4) RGBA (the A is used for opacity)
- color property sets font color
- saturation refers to the amount of grey in a color
- brightness refers to the amount of black in a color
- opacity is a number between 0 - 1, .5 would be 50% opacity 
- HSL is a weird way to pick colors and I probably won't use it
## Chapter 12: “Text” (pp.264-299)
- Several properties are available to change font, size, weight, style, spacing
- link specific Google fonts in the head of HTML to use different fonts available on Google fonts API
- pseudo classes allow to change the appearance of elements when a user interacts with them
    - the syntax begins with a colon, as an example
        1) :hover
        2) :active
        3) :focus