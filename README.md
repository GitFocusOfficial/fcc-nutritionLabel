# Learn Typography by Building a Nutrition Label

Typography is the art of styling your text to be easily readable and suit its purpose.

In this course, you'll use typography to build a nutrition label webpage. You'll learn how to style text, adjust line height, and position your text using CSS.

## Step 1

We've provided a basic HTML boilerplate for you.

Create an h1 element within your body element and give it the text Nutrition Facts.

## Step 2

Below your h1 element, add a p element with the text 8 servings per container.

## Step 3

Add a second p element with the text Serving size 2/3 cup (55g).

## Step 4

Within your head element, add a link element with the rel attribute set to stylesheet and the href attribute set to https://fonts.googleapis.com/css?family=Open+Sans:400,700,800.

This will import the Open Sans font family, with the font weight values 400, 700, and 800.

Also add a link element to link your styles.css file.

## Step 5

Create a body selector and give it a font-family set to Open Sans with a fallback of sans-serif.

Remember that fonts with spaces in the name must be wrapped in quotes for CSS.

## Step 6

The font is a bit small. Create an html selector and set the font to have a size of 16px.

## Step 7

Wrap your h1 and p elements in a div element. Give that div a class attribute set to label.

## Step 8

Borders can be used to group and prioritize content.

Create a .label selector and give it a border set to 2px solid black.

## Step 9

Good use of white space can bring focus to the important elements of your page, and help guide your user's eyes through your text.

Give your .label selector a width property set to 270px.

## Step 10

Give your .label selector a margin property set to 20px auto, and a padding property set to 0 7px.

## Step 11

If you inspect your .label element with your browser's developer tools, you may notice that it's actually 288 pixels wide instead of 270. This is because, by default, the browser includes the border and padding when determining an element's size.

To solve this, reset the box model by creating a * selector and giving it a box-sizing property of border-box.

## Step 12

Remember that the use of h1, h2, and similar tags determine the semantic structure of your HTML. However, you can adjust the CSS of these elements to control the visual flow and hierarchy.

Create an h1 rule and set the font-weight property to 800. This will make your h1 text bolder.

## Step 13

Give your h1 selector a text-align property of center.

## Step 14

Fine-tune the placement of your h1 by giving it a top and bottom margin of -4px and a left and right margin of 0.

## Step 15

Create a p selector and remove all margins.

## Step 16

Lines can help separate and group important content, especially when space is limited.

Create a div element below your h1 element, and give it a class attribute set to divider.

## Step 17

Create a selector for your new .divider and set the border-bottom property to 1px solid #888989. Also give it a top and bottom margin of 2px. It should not have any left or right margin.

## Step 18

The letter-spacing property can be used to adjust the space between each character of text in an element.

Give your h1 selector a letter-spacing property set to 0.15px to space them out a bit more.

## Step 19

Nutrition labels have a lot of bold text to draw attention to important information. Rather than targeting each element that needs to be bold, it is more efficient to use a class to apply the bold styling to every element.

Give your second p element a class attribute set to bold.

## Step 20

Your new class does not have any styling yet. Create a .bold selector and give it a font-weight property set to 800 to make the text bold.

Go ahead and remove the font-weight property from your h1 selector as well.