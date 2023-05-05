<h1>Module 1 - Introduction to HTML</h1>

<p> 
    In this module, Angela introduces the language of the web, what is HTML? What can it do and what are the basic building blocks of HTML: tags, elements, the HTML boilerplate. 
    Angela follows a teach-apply method in her teachings that's why I've found it suitable to just re-create the site she's done in the course and just push it to git as is. 
    There are no comments in the HTML files but I've tried to explain everything I've learned down below. I hope its helpful. <em>Cheers.</em>
</p>

<hr>

<p> Main Contents 
    <ol> 
        <li>Introduction to HTML</li>
        <li>The Anatomy of an HTML Tag</li>
        <li>HTML Boilerplate</li>
        <li>How to Structure Text in HTML</li>
        <li>HTML Lists</li>
        <li>HTML Image Element</li>
        <li>HTML Anchor Element</li>
    </ol>
</p>

<hr>

<h2>
    Introduction to HTML
</h2>

<p>
    <strong>H</strong>yper<strong>T</strong>ext<strong>M</strong>ark<strong>U</strong>p<strong>L</strong>anguage is a markup language used for creating and
    structuring content on the web. It's the foundation of the World Wide Web and is used to
    create web pages and applications that are displayed in web browsers.
</p>

<h2>
    The Anatomy of an HTML Element
</h2>

<p>
    <strong>HTML</strong> uses elements to define the structure and content of a web page. 
    Elements are created with using tags and those tags can be divided into two categories which are self-closing(empty) tags and paired tags respectively. 
    <ol>
        <li>
            Self-closing Tags:  Self closing tags are used for elements that don't require any content, such as images, line breaks, horizontal lines, etc. Instead of an accompanying closing tag with a (/), they include a forward slash (/) at the end of the opening tag to indicate that the tag is self-closing.
        </li>
        <li>
            Paired Tags: Also known as opening and closing tags, are a type of HTML tag that are used to enclose content between an opening and a closing tag. Paired tags are used for HTML elements that contain content, such as paragraphs, headings, lists and tables.
        </li>
    </ol>

</p>

<h2>
    HTML Boilerplate
</h2>

<p>
    <a href="#"></a>
</p>

<h2>
    How to Structure Text in HTML
</h2>

<p>
    Most common ways to structure textual content in the HTML are:
    <ol>
        <li>
            <strong>Headings:</strong> Headings are used to introduce new sections or sub-sections of content. HTML provides six levels of headings, from h1 (most important heading) to h6 (the least important). Every HTML file can have only 1 h1 heading element meanwhile there could be more than 1 other heading elements.
        </li>
        <li>
            <strong>Paragraphs:</strong> Paragraphs are used to separate blocks of text into individual units. Note that it's generally a good practice to use paragraphs to separate blocks of text, rather than relying on line breaks (br element) to create spacing between lines of text. This helps to ensure that your content is well-organized and easy to read.
        </li>
        <li>
            <strong>Emphasis:</strong> Emphasis element can be used to emphasize a portion of text to indicate its importance. The "em" element is used for emphasis, italic text, while the <strong>"strong"</strong> is used for strong emphasis, bolder text. Usage of semantic tags such as em, and strong is considered a good practice from the SEO stand point. That means if you want your site to rank higher and reach the targeted audience you have to make use of semantic elements.
        </li>
    </ol>

<h2>
    HTML Lists
</h2>

<p>
    Lists are another way of structuring textual content in HTML documents. They are used to group related pieces of information together and present them in a structured way on a webpage.
    There are three types of HTML lists:
        <ol>
            <li> 
                Ordered Lists: An ordered list is used when you want to display items in a numbered format. It is created using the "ol" (ordered list) tag and each item is enclosed within "li" (list item) tags.
            </li>
            <li>
                Unordered Lists: An unordered list is used when you want to display items in bullet format. It is created using the "ul" (unordered list) tag and each item is enclosed within "li" tags.
            </li>
            <li>
                Definition Lists: A definition list is a little bit different than other two lists. It is used whhen you want to display terms and their definitions. 
                It is created using the "dl" (definition list) tag and each term is enclosed within "dt" (data term) tags and each definition is enclosed within "dd" (data definition) tags. 
        </ol>
</p>


<h2> 
    Image Element
</h2>

<p>
    The "<img>" element in HTML is used to embed images into a webpage. It is a self-closing tag and does not require a closing tag. 
    The image element has a required attribute called "src" which specifies the URL or file path of the image file that should be displayed.
    The "alt" attribute is also important for accessibility purposes, as it provides a textual description of the image for visually impaired users.
    The "title" attribute provides a tooltip text when the user hovers over the image.
</p>

<h2>
    Anchor Element
</h2>

<p>
    The anchor element is an HTML tag used to create Hyperlinks to other webpages or to specific parts of the same webpage. It creates a clickable link that takes the used to the destination URL when clicked. The "href" attribute is a must as it specifies the destination URL. "href attribute can also be used to create a link to a specific part of the same webpage by specifying an anchor tag, or "#", followed by the "id" attribute of the element that the link should navigate to.
    There are couple of useful attributes to consider using with the anchor tag.
    <ol>
        <li>
            "target" : specifies where to open the linked document. The "target" attribute can have several values, which specify where the linked document should be opened. Here are the most common values, "_self" the default value. Linked document will open in the same window/tab that the link was clicked on.
            "_blank" the linked document will open in a new window or tab.
            "_parent" the linked document will open in the parent frame of the current frame.
            "_top" the linked document will replace any framesets that may be loaded and will open in the full body of the current window or tab.
        </li> 
        <li>
            "title" : provides additional information about the link when the user hovers over it.
        </li>
        <li>
            "download" : specifies that the target will be downloaded when the user clicks on the link instead of navigating to it.
        </li>
    </ol>
</p>


<p> Inspiration website used in the module: https://www.cs.cornell.edu/home/kleinber/ </p>