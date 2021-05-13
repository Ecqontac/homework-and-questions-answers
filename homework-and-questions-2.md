## Homework Questions 2 (Homework part 2)

1. CSS is the acronym of “Cascading Style Sheets”. 

2. "Cascading" means that styles can fall (or cascade) from one style sheet to another, enabling multiple style sheets to be used on one HTML document.
    The html element will search for inline style and apply it, if there is no inline style then it will CASCADE to internal style and apply it, and if there is no internal style then it Will CASCADE to the external style and apply it

3. CSS is the language for describing the presentation of Web pages, including colors, layout, and fonts. It allows one to adapt the presentation to different types of devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language.

4. CSS is independent of HTML and can be used with any XML-based markup language. The separation of HTML from CSS makes it easier to maintain sites, share style sheets across pages, and tailor pages to different environments.

5. A CSS selector is the first part of a CSS Rule. It is a pattern of elements and other terms that tell the browser which HTML elements should be selected to have the CSS property values inside the rule applied to them.

6. The element selector selects HTML elements based on the element name. 
   p {
  text-align: center;
  color: red;
   } 
   Here, all <p> elements on the page will be center-aligned, with a red text color

7.  A CSS rule consists of a CSS selector and a set of CSS properties. The CSS selector determines what HTML elements to target with the CSS rule. The CSS properties specifies what to style of the targeted HTML elements.
     div {
      border    : 1px solid black;
      font-size : 18px;
       }   This example creates a CSS rule that targets all div elements, and the set the CSS properties border and font-size for the targeted elements.

8. A CSS property declaration consists of a property name and a property value. The property name comes first, then a colon, and then the value. Here is the general pattern a CSS property declaration follows:

    property-name : property-value
    
9. A CSS rule is a grouping of one or more CSS properties which are to be applied to one or more target HTML elements.

   A CSS rule consists of a CSS selector and a set of CSS properties. The CSS selector determines what HTML elements to target with the CSS rule. The CSS properties specifies what to style of the targeted HTML elements.


10. DRY stands for Don't Repeat Yourself and the principle is that there should only ever be one copy of any important piece of information. The reason for this principle is that one copy is much easier to maintain than multiple copies; if the information needs to be changed, there is only one place to change it

11. The declaration block contains one or more declarations separated by semicolons. Each declaration includes a CSS property name and a value, separated by a colon. Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

12. A Type Selector sometimes referred to as an Element Type Selector matches elements with the corresponding element node name, such as < p >, < span > , and < div > tags. Type selectors are generally used to make “broad stroke” changes to the style of a site.

13. he class selector is a way to select all of the elements with the specified class name, and apply styles to each of the matching elements. The selector must start with a period ( . ) and then the class name. The browser will look for all tags in the page that have a class attribute containing that class name.

14. The .class selector selects elements with a specific class attribute.

    To select elements with a specific class, write a period (.) character, followed by the name of the class.

15.  The id selector uses the id attribute of an HTML element to select a specific element. The id of an element is unique within a page, so the id selector is used to select one unique element! To select an element with a specific id, write a hash (#) character, followed by the id of the element.

16. The Universal Selector is the * in CSS. Literally the asterisk character. It is essentially a type selector that matches any type. Type meaning an HTML tag like < div > , < body > , < button > , or literally any of the others

17. The CSS grouping selector is used to select multiple elements and style them together. This reduces the code and extra effort to declare common styles for each element. To group selectors, each selector is separated by a space.

article, p, img {
   display: block;
   margin: auto;
   text-align: center;
   border-bottom: double orange;
}
  

18. The CSS attribute selector matches elements based on the presence or value of a given attribute.

19. Simple selectors (select elements based on name, id, class)
Combinator selectors (select elements based on a specific relationship between them)
Pseudo-class selectors (select elements based on a certain state)
Pseudo-elements selectors (select and style a part of an element)
Attribute selectors (select elements based on an attribute or attribute value)


20. The CSS Universal Selector , The CSS element Selector ,The CSS id Selector
