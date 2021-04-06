# Boxes

## Box Dimensions

- **Setting specific dimensions for a box is done by using width and height.  To specify the box size you can use pixels, percentages, and em's.**

- Pixels is the most popular way to specify size.  The allows for better and more precise way of cotroling the size of the box.

- Percentage is relative to how big the browser window.  When you pic a percentage it determines how big the browser is and makes the box bigger or smaller depending on the browswer size.

- em's are determined by the text size within that box.

## Limiting Width

- If a user changes the size of their window the box within that window should change with that size.  Using the min-width property will determine how small that box is allowed to go and the opposite happens with max-width.

## Limiting Height

- Just like the above mentioned, you can set a minimum height and a maximum height for the box dependant on how the browswer window is manipulated.  Using the min-height and max-height will let you manipulate the box's height.

## Overflowing Content

- Overflow allows you to take content that is too long for the box and either hide it using hidden, this will cut off the extra information if it is too long for the box, or scroll will add a scroll bar so you can manipulate the text up and down so the user can read all the information.  

## Border, Margin, and Padding

- Border - The border is the spacing bewtween all boxes.
- Margin - The margin sits outside of the border and can be manipulated to make a gap between boxes.
- Padding - This is the space between the information in the box and the border.

## Border Width

- the border-width prperty controls the width of the border.  This can be manipulated using pixels or other values such as thick, medium, or thin.

- You can also control one specific side at a time by adding which side you want to manipulate such as border-top-width.

## Border style

- The border style allows the develor to choose  how it looks like.

- **Values that work with border style are**

- solid

- dotted 

- dashed

- double

- groove

- ridge

- inset

- outset

- hidden or none

## Border color

- Using the border-color element allows you to change the color of the border.  This too can be manipulated by each individual side or all together.  

## Padding and Margin

- Padding is the spacing bewtween what is insdie the box and the inside broder of the box. This too can be manipulated on any side.

- Margin controls the spacing bewtween boxes and can too be manipulated as a whole or specified sides.  

**To center text within the box you want to set the right and left margins to auto**
