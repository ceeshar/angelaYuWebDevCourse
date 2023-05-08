<h1>Module 2 - Intermediate HTML</h1>

<p> Main Contents
    <ol>
        <li>Tables</li>
        <li>Forms</li>
    </ol>
</p>

<hr>

<h2>
    Tables
</h2>

<p>
    Tables are used to represent information in a two-dimensional table comprised of rows and columns of cells containing data. Tables can also be used for layout.
    The table in HTML is created using the "table" element, and the data is organized into rows and columns using the "tr" (table row), "td" (table data), "th" (table header) elements.
    Just like an ordinary HTML file, HTML Tables can be broken up into three main sections: the header (thead), body(tbody), and footer(tfoot).
    "thead" element contains the header row, which contains the column headers using "th" element. The "tbody" element contains the body of the table, which contains the rows of data using the "tr" element and cells using the "td" element. Finally, the "tfoot" element contains the footer row, which contains a summary of the data using the "td" element. 
    Using these tags helps to group the table content semantically and makes it easier to apply styles and scripts to specific parts of the table. 
</p>

<h2>
    Forms
</h2>

<p>
    An HTML form is used to collect user input. To create an HTML form, you use the "<form>" tag, which specifies the action that the server should take upon submission of the form data. The "action" attribute of the "form" tag specifies the URL of the server-side script that will process the form data.
</p>

<h3>
    Within the "form" tag, you can include different form elements, such as:
    <ul>
        <li>
            "input": the "input" tag defines a text input field where users can enter text or numeric data. You can specify the "type" attribute to define the type of input, such as text, password, email, or number. (input types: text, radio, checkbox, submit, button)
        </li>
        <li>
            "textarea": defines a multi-line text input field where users can enter large amounts of text.
        </li>
        <li>
            "select": defines a dropdown menu where users can select one or more options from a list.
        </li>
        <li>
            "radio", "checkbox" tags defines radio buttons and checkboxes, respectively, which allow users to select one or more options from a list.
        </li>
        <li>
            "button": defines a clickable button that can be used to submit the dorm or perform other actions with the help of JS, which is a client-side scripting language that runs in the user's web browser.
        </li>
        <li>
            "label": defines a label for form elements. It's useful because of the accessibility issues and we can use labels "for" attribute to bind the form's "input" element with itself, so when the label is clicked, input element is also clicked. (label's "for" attribute's value must be same with the "input" element's ID attribute.)
    </ul>
</h3>

<p>
    When the user submits the form, the browser sends the form data to the server which can then process the data and respond with a new web page or other content based on the user's input. The server-side script can access the form data using a programming language like JS, and use it to perform various actions, such as updating a database, sending an email, or displaying a confirmation message to the user.
</p>
