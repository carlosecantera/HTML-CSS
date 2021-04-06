# HTML5 Layout

## Traditional and New HTML Layout

- In older versions of HTMl the layout was different than the new. Everything in the body would be within a < div > element and would have an ID associated with it.  These div elements would indicate the purpose of each attribute.
- In the new HTML format the < div > element is still used but not as frequently.  New elements such as < heading > and < article > are used.  This allows the developer to skip to different portions of their code to work on what they want to work on at that moment and go back as needed.  The layout is easier to follow.

## Elements

**header** - The header contains the site name and is wehre the main navigation of the page is found.
**footer** - The footer is where the author of the site would put any copyright or trademark information.
**nav** - The nav element allows you to have links that will direct you to different parts of the site.  An example would be the home about or contact us.
**article** -This element allows you to have a specific piece of information blocked off fromt he rest of the page as its own stand alone portion.  You can nest multiple article within each other.
**aside** - This element can live in two different places.  It can live inside an article or outside of an article.  If it lives in an article the aside needs to be relavent to the article it is nested in.  If it's outside of the article it would have to be relavent to the whole page and not just a small portion.
**section** - The section element allows you to group related content together. an example given in the book would be a section with recipes holding multiple recipe links.  Each section would have their own heading.
**hgroup** - An hgroup allows you to group multiple headings together so they are treated as one individual heading. This element seems to be less popular and is not used regularly.
**figure** - This is used to insert a figure that is important to the section you are working on. Examples would be an image or video that is relevant to the section you are working on.  
**figurecaption** - This element allows you to put a caption attached to the figure you inserted.  So if you insert a picture of a dog the caption may let the user know what kind of dog it is or what it is doing.
**< a >** - This element allows you to grab a piece of code and turn that entire block into a link.

**In older browsers HTML5 may be an issue as it does not understand the new elements, therefore it treats them like inline elements.**