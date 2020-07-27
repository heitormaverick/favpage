# FavPage
## Favorite page to save space in the favbar

### How to customize your FavPage:

First things first: download this repository

Then, choose a Tab Name and change it

Now, Choose an image to be the Favicon (preferably square or circle), and use the website favicon-generator.org (https://www.favicon-generator.org/) to convert it.

Don't change anything, just upload the image and click "create".

Now download, extract the zip and move the three files "favicon-00x00.png" to your website folder.

Your Favicon is ready.

Now, if you want, change the Page Title.

Now, to create buttons, replace the default button link with your choice, and the name as well.

Your buttons have already been created, to change appearance, open the "style.css", look for the #button0 and change the color options of the background, border and color (font color).

If you want to create more buttons, copy the line of code
```html
<a href="Button 1 Link Here"><button id = "button1">Button 1 Name Here</button></a>
```  
and change the link, the number of id to 6,7,8 ... and the name.

Now in CSS, copy  
```css
#button1 {
    background-color: black;
    border: 3px solid white;
color: white;
}
```  
under #button5 and change the "1" to the number of the button you want to change.