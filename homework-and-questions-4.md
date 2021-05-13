# Homework Questions 4 (Homework part 2)

1. The HTML5 specification introduced several semantic sectioning elements to help organize the structure of documents.They are intended to enhance the limited semantics of earlier versions of HTML, which included only the < div > tag as a generic mechanism for grouping related content.

2. Semantic sectioning elements are specifically designed to communicate structural meaning to browsers and other technologies interpreting the document on behalf of users, such as screen readers and voice assistants. Semantic sectioning elements clarify the larger-scale structures within a document.

3. Examples of non-semantic elements: < div > and < span > - Tells nothing about its content.

   Examples of semantic elements: < form >, < table >, and < article > - Clearly defines its content.
   Semantic sectioning elements clarify the larger-scale structures within a document. They are intended to enhance the limited semantics of earlier versions of HTML, which included only the < div > tag as a generic mechanism for grouping related content.
   
4. In HTML there are some semantic elements that can be used to define different parts of a web page
  < article >
  < aside >
  < details >
  < figcaption >
  < figure >
  < footer >
  < header >
  < main > 
  < mark >
  < nav >
  < section >
  < summary >
  < time >
5. < article >
  < aside >
  < details >
  < figcaption >
  < figure >
  < footer >
  < header >
  < main > 
  < mark >
  < nav >
  < section >
  < summary >
  < time >

6. The HTML < nav > element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes.

7. The < article > element specifies independent, self-contained content.

   An article should make sense on its own, and it should be possible to distribute it independently from the rest of the web site.

   Examples of where an element can be used:<article>
   Forum post <article>  
   Blog post<article>   
   Newspaper article <article>

8. Defines a section of a document to indicate a related grouping of semantic meaning. It makes sense to use the section element to provide extra context for the parent element.

9. The outline for an HTML document shows the structure of the content on the page. This is useful for user agents, who can use the outline to create, for example, a table of contents for the document. This can then be used by screen readers to help people better navigate the page.

10. The HTML Aside Section Element  < aside >  defines a section that, though related to the main element, doesn't belong to the main flow, like an explanation box or an advertisement. It has its own outline, but doesn't belong to the main one.

11. The header can also be used inside other semantic elements such as < article > or < section > . A section header might contain the section's heading, author name, etc. < article > , < section > , < aside > , and < nav > can have their own < header > .

12. The < body > tag defines the document's body. The <body> element contains all the contents of an HTML document, such as headings, paragraphs, images, hyperlinks, tables, lists, etc. Note: There can only be one <body> element in an HTML document.

13. A header typically contains a group of introductory or navigational aids. A header element is intended to usually contain the section's heading (an h1 – h6 element), but this is not required. The header element can also be used to wrap a section's table of contents, a search form, or any relevant logos

14. The < header > element can also be used to wrap a section’s table of contents, a search form, or any relevant logos.There can be several < header > elements in one document.
    A < header > tag cannot be placed within a < footer >, < address > or another < heade r> element.

15. Headers for all required pages must be consistently formatted; they should be the same size, font, and style, and located in the same position on each page. They must start at the very top of the page, on the first line, within the 1-inch margin.

16. A footer typically contains information about its section such as who wrote it, links to related documents, copyright data, and the like. When the footer element contains entire sections, they represent appendices, indexes, long colophons, verbose license agreements, and other such content.

17. ***Which*** `sectioning elements` ***might have*** their ***own*** `footer`?

18. The HTML < nav > element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes.

19. <nav>
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="/about/">About</a></li>
<li><a href="/blog/">Blog</a></li>
</ul>
</nav>

20. If not present and if no CSS list-style-type property applies to the element, the user agent selects a bullet type depending on the nesting level of the list.

21. The < ul > element is for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. Typically, unordered-list items are displayed with a bullet, which can be of several forms, like a dot, a circle, or a square

22. The Element is used to represent an item in a list. It must be contained in a parent element: an ordered list ( < ol > ), an unordered list ( < ul > ), or a menu ( < menu > ). In menus and unordered lists, list items are usually displayed using bullet points.

23. The element must be nested inside either a < ol > or < ul > element

24. The element  anchor , with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address. Content within each < a > should indicate the link's destination.

25. The most common types of content that HTML elements contain are text, images, and video.

26. The < a > tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to

27.<!DOCTYPE HTML>
<html>
<head>
<meta charset="UTF-8">
<title>Embedded Style Sheet</title>
<style>
  h1  {
    color: #009;
    font-size: 1em;
    margin-bottom: .3em;
    text-align: center;
    text-decoration: underline;
  }
  
  table {
    margin: .3em;
    width: 290px;
  }
  
  th {
    padding: .2em;
  }
  
  td {
    background-color: #ffc;
    border: 1px solid #900;
    padding-left: .5em;
    padding-right: .5em;
  }
  
  #trHeader {
    color: #900;
    text-decoration: underline;
  }
  
  .centerCell {
    text-align: center;
  }
</style>
</head>
<body>

<div>
<h1>All-time Home Run Record</h1>
<table>
  <tr id="trHeader">
    <th>Player</th>
    <th>Home Runs</th>
    <th>Team</th>
  </tr>
  <tr>
    <td>Barry Bonds</td>
    <td class="centerCell">762</td>
    <td>Giants</td>
  </tr>
  <tr>
    <td>Hank Aaron</td>
    <td class="centerCell">755</td>
    <td>Braves</td>
  </tr>
  <tr>
    <td>Babe Ruth</td>
    <td class="centerCell">714</td>
    <td>Yankees</td>
  </tr>
  <tr>
    <td>Willie Mays</td>
    <td class="centerCell">660</td>
    <td>Giants</td>
  </tr>
</table>
</div>
</body>
</html>

Create a new file and save it as StyleSheet.css in the same directory. (You can give the file any name as long as it has the .css extension).

Move all the CSS rules from the HTML file to the StyleSheet.css file. Don't copy the style tags

h1 {
  text-align: center;
  font-size: 1em;
  color: #009;
  margin-bottom: .3em;
  text-decoration: underline;
}

table {
  margin: .3em;
  width: 290px;
}

th {
  padding: .2em;
}

td {
  padding-left: .5em;
  padding-right: .5em;
  border: 1px solid #900;
  background-color: #ffc;
}

#trHeader {
  text-decoration: underline;
  color: #900;
}

.centerCell {
  text-align: center;
}

Remove the style block from the HTML file.
In the HTML file, add a link tag after the closing title tag that points to StyleSheet.css.

<link href="StyleSheet.css" rel="stylesheet">

<link> attributes include:

href	points to the location of the external style sheet
rel	  must be set to "stylesheet" for linking style sheets
type	must be set to "text/css" for linking to cascading style sheets

Open the HTML file in a browser...
