# Homework Questions 6 (Homework part 2)


1. Responsive web design, also called RWD design, describes a modern web design approach that allows websites and pages to render (or display) on all devices and screen sizes by automatically adapting to the screen, whether it's a desktop, laptop, tablet, or smartphone.

2. Designers size elements in relative units (%) and apply media queries, so their designs can automatically adapt to the browser space to ensure content consistency across devices.

3. When the design and development should respond to the user's behavior and environment based on screen size, platform and orientation. The practice consists of a mix of flexible grids and layouts, images and an intelligent use of CSS media queries.

4. Attract a wider audience. Your audience will access your website from a variety of different devices in all shapes and sizes.Easier to maintain. 
Boost for SEO.

5. Media queries are useful when you want to modify your site or app depending on a device's general type (such as print vs. screen) or specific characteristics and parameters (such as screen resolution or browser viewport width).

6. One is in the site navigation, and the other will be in our CSS Grid columns containing our images on our portfolio page. 


7.


       

9. Using media queries are a popular technique for delivering a tailored style sheet (responsive web design) to desktops, laptops, tablets, and mobile phones. You can also use media queries to specify that certain styles are only for printed documents or for screen readers (mediatype: print, screen, or speech).

10. CSS code is considered mobile first design when we use the min-width CSS property in our media query and the specified width is that of larger screens, i.e. min-width: 800px or min-width: 900px, or even min-width: 1280px, etc. The min-width should be able to fit the content of the page on any width larger than or equal to the min-width provided without omitting any page content.

11. CSS code is considered to be desktop first design when we use the max-width CSS property in our media query and the specified width is that of smaller screens. i.e. max-width: 899px, max-width: 599px, etc. The max-width should be able to fit the content of the page in any width smaller or equal to the max-width provided without omitting any page content.


   of `mobile first design` using `CSS code` from the `portfolio site`. Use the `CSS rule set` for the `section element selector` as the ***example***. You may have to do some ***refactoring*** of the `code`! And make sure to also ***include*** the `HTML markup` it ***targets***.

13. Please ***provide*** an `example` of `desktop first design` using `CSS code` from the `portfolio site`. Use the `CSS rule set` for the `section element selector` as the ***example***. You may have to do some ***refactoring*** of the `code`! And **make sure** to also ***include*** the `HTML markup` it ***targets***.

14. Syntax. A media query is composed of an optional media type and any number of media feature expressions. Multiple queries can be combined in various ways by using logical operators.

media_query_list
 : S* [media_query [ ',' S* media_query ]* ]?
 ;
media_query
 : [ONLY | NOT]? S* media_type S* [ AND S* expression ]*
 | expression [ AND S* expression ]*
 ;
media_type
 : IDENT
 ;
expression
 : '(' S* media_feature S* [ ':' S* expr ]? ')' S*
 ;
media_feature
 : IDENT
 ;
 
 
 
 15. A media query computes to true when the media type (if specified) matches the device on which the document is being displayed and all media feature expressions compute to true.




16. Queries involving unknown media types always evaluate to false.


17. Media types describe the general category of a device. Except for when using the not or only logical operators, media type is optional and the all type is implied.

18. yes we do because it deals with displaying imgaes and the type we would use is screen.

20. Media features describe specific characteristics of the user agent, output device, or environment. Media feature expressions test for their presence or value, and are entirely optional. Each media feature expression must be surrounded by parentheses.



21. Media feature expressions test for their presence or value, and are entirely optional. Each media feature expression must be surrounded by parentheses.




22. 
    

+ `any-hover`: Does ***any*** `available input mechanism` ***allow*** the `user` to ***hover over*** `elements`? (***added*** in `Media Queries Level 4`).

+ `any-pointer`: Is ***any*** `available input mechanism` a `pointing device`, and ***if so***, ***how accurate*** is it? (***added*** in `Media Queries Level 4`).

+ `aspect-ratio`: The `ratio` ***between*** the `width` and the `height` of the `viewport`.

+ `color`: The `number` of `bits` ***per*** `color component` for the `output device`.

+ `color-gamut`: The ***approximate*** `range` of `colors` that are ***supported*** by the `user agent` and `output device` (***added*** in `Media Queries Level 4`).

+ `color-index`: The ***number*** of `colors` the `device` can ***display***.

+ `grid`: ***Whether*** the `device` is a `grid` or `bitmap`.

+ `height`: The `viewport height`.


23. working on our css grids for our images.We need them too flow from screen too phone. I would use grid: Whether the device is a grid or bitmap. and my type would be screen for display purposes but dealing with my photography i might shy too print for printers.
