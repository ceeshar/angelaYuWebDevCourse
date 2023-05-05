<h1>Module 3 - Introduction to CSS</h1>

<p>
    <ol>
        <li> Introduction to CSS </li>
        <li> Adding CSS - Inline CSS </li>
        <li> Adding CSS - Internal CSS </li>
        <li> Adding CSS - External CSS </li>
        <li> How to Debug CSS Code </li>
        <li> The Anatomy of CSS Syntax </li>
        <li> CSS Selectors </li>
        <li> Classes vs IDs </li>
    </ol>
</p>

<hr>

<h2>
Introduction to CSS
</h2>

<p>
    Cascading StyleSheets, CSS for short, is a language used exclusively for styling and presentation of HTML or XML documents. It provides a way to separate the presentation of a web page from its content, allowing developers to control the look and feel of the page without changing its underlying structure. Still, it can be used in various ways inside of an HTML document.
</p>

<p>
    CSS can be used to define various visual properties of an HTML element such as font size, color, padding, margin, border, background and much more... It also enables developers to create layouts, specify positioning, and add animations and transitions to create more engaging and interactive user interfaces.
</p>

<h2>
Inline CSS
</h2>

<p>
    Inline CSS is a way of adding CSS styles directly to an HTML element using the "style" attribute. With inline CSS, you can define styles for an individual HTML element, such as a paragraph or a heading, without affecting other elements on the page. The styles are defined within the "style" attribute of the HTML element, using a semicolon-separated list of CSS properties and values.
</p>

<h2>
    Internal CSS
</h2>

<p>
    Internal CSS is also used within the HTML document but instead of declaring the properties within the elements, we are declaring our rulesets using the "style" element in the "head" element of our HTML file. With using internal CSS, we can create styles that applies more than one element. Internal CSS is useful for small projects where you want to keep the styles within the HTML document itself. It is also useful when you want to apply styles to specific elements that cannot be targeted using external CSS files. However, it can become difficult to manage and maintain for larger projects.
</p>

<h2>
    External CSS
</h2>

<p>
    External CSS is a way of adding CSS styles to an HTML document by creating a separate CSS file and linking it to the HTML document using the "link" element. An external CSS file contains a set of CSS rules that apply to elements in the HTML document. By separating the CSS styles into a separate file, you can keep the HTML code clean and easy to read, and make it easier to maintain and update the styles across multiple pages. 
</p>

<p>
    So how do we link an external CSS file to an HTML document? 
    <ol>
        <li>
            Create a new file with a ".css" extension, such as "styles.css"
        </li>
        <li>
            Add your CSS styles to the file.
        </li>
        <li>
            In the HTML document, add a "link" tag to the "head" section of the document.
        </li>
    </ol>
</p>

<h2>
    Debugging Your CSS Code
</h2>

<p>
    Debugging CSS code involves identifying and fixing errors in the CSS styles that affect the layout or appearance of a web page.
</p>

<p>
    Debugging Techniques
    <ol>
        <li>
            Using the browser's developer tools to inspect and preview changes in real-time.
        </li>
        <li>
            Checking the CSS syntax for errors using a CSS syntax validator such as W3C CSS validator.
        </li>
        <li>
            Narrowing the problem down to a specific element or a property. Comment it out or try replacing it with other properties.
        </li>
        <li>
            Testing with different devices and screen sizes. CSS styles must be responsive and fluid, for that we need to use various techniques such as using grid and flex properties with our CSS ruleset, and media-queries. 
        </li>
        <li>
            Review the CSS cascade. Check the CSS cascade to ensure that the desired styles are being applied to the correct elements. The cascade is based on the concept of specificity, which determines which style rule takes precedence over others.
        </li>
</p>

<h2>
    CSS Selectors
</h2>

<p>
    Selectors are patterns used to select and style HTML elements on a webpage. Selectors are used to identify and target specific elements based on their element type, attributes, class, and/or ID. There are: Attribute selectors, class selectors, ID selectors, Type selectors, and the Universal selector.
</p>