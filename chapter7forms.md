# Forms

## Form controls

### Different kinds of buttons

- Adding text -Text input such as email address or names, Passord input and text area such as messages and comments.
- Making Choices -Radio buttons when someone is trying to  select an option from a list of options, check boxes is when someone is selecting from multiple options and can check multiple options, drop down boxes when a user picks from a drop down menu or list.
- Submitting froms -Submit buttons Image buttons and file upload.
- Uploading files -These buttons allow you to upload a file to a site.

## Form Structure

- < from> The controls for a form live inside the < form> element.  Inside should also have the action and method.  The action attribute will allow you to go to a different page and the method uses "get" or "post" 

- Get -Get allows you to retrive information.
- Post -Post allows you to submit information.

## Text Input

- < input> -This is used to create different kinds of controls.
- Use name to let the user know what attribute is being called for.

- 'type="text"' allows you to use a single line of text to input into the box.
- 'type="text"' allows you to use a single line  of text to input a password.  This will also allow for the text to be blocked out as to protect the password.
- < textarea> -This allows for a user to put in multiple lines of text such as for a review.
- 'type="radio"' This allows a user to make a selection out of a few different selections but only one can be selected.
- 'type="checkbox"' Is similar to that of radio except multiple boxes can be checked.
- < option> - This allows you to create a drop down box. You would use that option with a value in < select> 
- Multiple can be used just like the drop box option but this allows the user to select more than one answer.
- 'type="typefile"' allows  the user to be able to upload a file on the site. 
- 'type="submit"' allows a user to send a form.
- 'type="image"'  This gives a button a certain look.  You have to give it values to make it the way you want it to look.
- 'type="hidden"' create a hidden button that can be seen in the view source option on the site. 
- < label> Each form control should have its own element.  This labels the selectors
- < fielset> This element allows you to group a larger group of controls together.
- < legend> - This gives the fields purpose.
