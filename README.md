# Wiki
## Heading
Use of Semantics in HTML

Semantics have been a part of html in some form or another. It helps you understand what's happening where on the page.

The benefit of writing semantic HTML stems from the goal of a web page—to communicate. And by adding semantic tags to your documents, you are providing additional information about your document, which aids in communication and goes beyond just how they look on a page.
These tags help in proper structuring and understanding of the layout.

Earlier when <div> was used for pretty much everything, we still implemented semantics by giving it a "semantic" class name or an id name.

### Examples
Various Semantic Tags

* <code> - Code reference
* <h1> - First level headline

* Footer: The <footer> element specifies a footer for a document or section.

<footer>
  <p>Posted by: Hege Refsnes</p>
  <p>Contact information: <a href="mailto:someone@example.com">
    someone@example.com</a>.</p>
  </footer>

* Nav tag: The <nav> element is intended for large blocks of navigation links. However, not all links in a document should be inside a <nav> element!

<nav>
<a href="/html/">HTML</a> |
<a href="/css/">CSS</a> |
<a href="/js/">JavaScript</a> |
<a href="/jquery/">jQuery</a>
</nav>

* Aside Tag: The <aside> element defines some content aside from the content it is placed in (like a sidebar).

<p>My family and I visited The Epcot center this summer.</p>
<aside>
  <h4>Epcot Center</h4>
  <p>The Epcot Center is a theme park in Disney World, Florida.</p>
</aside>

#### Not Recommended

Some of the most commonly misused semantic tags include:

* <Blockquote>: Should not use it to indent text. Use CSS margins instead.
* <P>: Avoid <p>&nbsp;</p> to add extra space between page elements.
* <h1> to <h6>: The header tags can be used to make fonts bigger and bolder, but if the text is not a headline, it should not be inside a headline tag. Use the font-weight and font-size CSS properties instead.

### Further Reference
* http://webdesign.about.com/od/htmltags/a/why-semantic-html.htm : Various other semantic tags
* http://html5doctor.com/lets-talk-about-semantics/ : Discusses about the usage of semantics
* http://diveintohtml5.info/semantics.html : Explains semantics in details