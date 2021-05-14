# Homework Questions 5 (Homework part 2)

1. In CSS, the term "box model" is used when talking about design and layout. The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.

2. you just set the width and height of the content area. To calculate the full size of an element, you must also add padding, borders and margins.

3. It is important to note that when we set the width and height properties of an element with CSS, we just set the width and height of the content area. To        calculate the full size of an element, we must also add padding, borders and margins.

4. width + padding + border = actual width of an element<article>
   height + padding + border = actual height of an element

5. 592px

```css
div {
    background-color: lightgrey;
    width: 545px;
    border: 12px solid green;
    padding: 35px;
    margin: 25px;
}
```


6.  592px

```css
div {
    background-color: lightgrey;
    height: 545px;
    border: 12px solid green;
    padding: 35px;
    margin: 25px;
}
```



7. The box-sizing property allows us to include the padding and border in an element's total width and height.

8.
+ `static`
+ `absolute`
+ `fixed`
+ `relative`
+ `sticky`
+ `initial`
+ `inherit`

9.
+ `initial`
+ `inherit`

10. width + padding + border = actual width of an element<article>
    height + padding + border = actual height of an element
    
    and the answer is no 

11. By adding the property declaration box-sizing: border-box; to the universal selector rule set, all elements on the page are targeted, and padding and border are     included in all their widths and heights.

12. ***Consider*** the ***following*** `CSS`:

```css
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
```

adding the property declaration box-sizing: border-box; to the universal selector rule set, all elements on the page are targeted, and padding and border are included in all their widths and heights.

Many browsers already use box-sizing: border-box; for many form elements (but not all - which is why inputs and text areas look different at width: 100%;).

Applying box-sizing: border-box is safe and smart.

Padding: Clears an area around the content. The padding is transparent.

Margin: Clears an area outside the border. The margin is transparent.

13. Normal Flow, or Flow Layout, is the way that Block and Inline elements are displayed on a page before any changes are made to their layout. The flow is    essentially a set of things that are all working together and know about each other in your layout. Once something is taken out of flow it works independently.

14. When taking an item out of flow with positioning, you will need to manage the possibility of content overlapping. Out of flow essentially means that the other elements on your page no longer know that element exists so will not respond to it.

15. position property is used to specify how the element will be displayed on the page. The top, right, bottom, and left CSS position properties determine the final location of the element. Note these properties only work if the position property is already established.

16. 
   ## static: The default value. Elements render in order, as they appear in the document flow. Static postioned elements are NOT affected by the top, bottom, left, and right properties. An element with position: static; is not positioned in any special way. It is always positioned according to the normal flow of the page.

  ## absolute: The element is positioned relative to its nearest positioned (not static) ancestor element (instead of positioned relative to the viewport, like fixed).If an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

  ## fixed: The element is positioned relative to the viewport (browser window). This means that it always stays in the same place, even if the page is scrolled. The top, right, bottom, and left properties are used to position the element. A fixed element does not leave a gap in the page where it would normally have been located.
  
  ## relative: The element is positioned relative to its normal position, so left: 25px adds 25px to the element's LEFT position.Setting the top, right, bottom and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.

17. ***When*** `applying` a `position property declaration` on an `element`, ***which*** `properties` can ***also*** be ***applied***? There are ***six***. Please ***describe*** them and ***what*** they ***do*** along with the `position property`. Please also include ***how*** they `work` ***depending*** on the `position` ***value***. Please ***refer*** to the `slide decks` ***specifically related*** to ***these*** `properties`. Please ***also provide*** an `example` of ***each*** `property` ***with*** a `property declaration`.

18. The z-index property specifies the stack order of an element.

An element with greater stack order is always in front of an element with a lower stack order.

19. Absolutely positioned elements overlap each other. All sorts of reasons. Without any z-index value, elements stack in the order that they appear in the DOM (the lowest one down at the same hierarchy level appears on top)

20. A fluid layout is a type of webpage design in which layout of the page resizes as the window size is changed. This is accomplished by defining areas of the page using percentages instead of fixed pixel widths. By using percentages, the content can expand or shrink to fit the window of the user's computer
