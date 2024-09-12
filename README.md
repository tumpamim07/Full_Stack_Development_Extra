 <div align="center">
<h1>Full Stack Development Extra</h1>
</div>

<details>
<summary>Assignment 01(Portfolio Using HTML)</summary>

- Ques: Build a website just with HTML. No CSS.
    ---
    
    ### **Portfolio Page (task.html)**
    
    ### **HTML Document Structure**
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Portfolio</title>
    </head>
    <body>
    
    ```
    
    - `<!DOCTYPE html>`: Declares the document as HTML5.
    - `<html lang="en">`: Starts the HTML document with English as the language.
    - `<head>`: Contains meta-information about the document.
    - `<meta charset="UTF-8">`: Specifies the character encoding.
    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures the page is responsive on different devices.
    - `<title>`: Sets the title of the page.
    
    ### **Body Content**
    
    ```html
        <section>
            <h1>Welcome to My Portfolio</h1>
            <img src="cat.jpg" alt="" height="100px">
            <p>Hello, I am Tumpa Moni Mim. I am currently in my final year of a BSc in the CSE department. Being passionate about websites and applications, I have completed many courses to improve my programming skills</p>
        </section>
    
    ```
    
    - `<body>`: Contains the visible content of the page.
    - `<section>`: Groups related content together.
    - `<h1>`: Main heading of the section.
    - `<img src="cat.jpg" alt="" height="100px">`: Embeds an image with a height of 100 pixels.
    - `<p>`: Paragraph of text introducing yourself.
    
    ### **Education Experience and Skills**
    
    ```html
        <section>
            <h1>Education Experience</h1>
            <ul>
                <li><b>Diploma in CSE</b></li>
                <li><b>BSc in CSE (ongoing)</b></li>
            </ul>
    
            <h1>Skills</h1>
            <ol>
                <li>HTML</li>
                <li>CSS</li>
                <li>Python</li>
                <li>Django</li>
                <li>C</li>
                <li>C++</li>
            </ol>
        </section>
    
    ```
    
    - `<h1>`: Headings for education and skills sections.
    - `<ul>`: Unordered list for education experience.
    - `<li>`: List item in the unordered list.
    - `<b>`: Bold text for highlighting the educational qualifications.
    - `<ol>`: Ordered list for skills.
    
    ### **Projects and Contact Link**
    
    ```html
        <section>
            <h1>My Projects</h1>
            <ul>
                <li><a href="<https://github.com/tumpamim07/Portfolio-Project>">Portfolio Project</a></li>
                <li><a href="<https://github.com/tumpamim07/Recipe_Project>">Recipe Project</a></li>
            </ul>
        </section>
        <p>If you want to contact me, click below</p>
        <a href="contact.html">Contact</a>
    </body>
    </html>
    
    ```
    
    - `<h1>`: Heading for the projects section.
    - `<ul>`: Unordered list for project links.
    - `<a href="<https://github.com/tumpamim07/Portfolio-Project>">`: Link to an external project.
    - `<a href="contact.html">`: Link to the contact page.
    
    ---
    
    ### **Contact Page (contact.html)**
    
    ### **Contact Information**
    
    ```html
    <h1>Contact Information</h1>
    <dl>
        <dt><b>Email:</b></dt>
        <dd>tumpamoni455@gmail.com</dd>
        <dt><b>Phone:</b></dt>
        <dd>01700000000</dd>
        <dt><b>Github</b></dt>
        <dd><a href="<https://github.com/tumpamim07>">Github</a></dd>
    </dl>
    
    ```
    
    - `<h1>`: Main heading for the contact information.
    - `<dl>`: Definition list for contact details.
    - `<dt>`: Definition term (e.g., "Email:", "Phone:").
    - `<dd>`: Definition description (e.g., email address, phone number).
    - `<b>`: Bold text for definition terms.
    - `<a href="<https://github.com/tumpamim07>">`: Link to an external GitHub profile.
    
    ---
    
    ### Summary
    
    This setup covers a basic portfolio and contact page using HTML, showcasing how to use various HTML tags to structure and present content effectively.

</details>
<details>
<summary>Assignment 02(HTML Tags)</summary>
    
- HTML Tags
    
    This HTML code demonstrates the use of various HTML elements, such as tables, forms, multimedia content (video), iframes, and accessible forms:
    
    ### 1. `<head>` Tag
    
    - The head section contains metadata, links to stylesheets, scripts, and the title of the document, but nothing visible to users.
    
    ```html
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="author" content="Tumpa">
        <title>HTML Tags</title>
    </head>
    
    ```
    
    - **`<meta charset="UTF-8">`**: Defines the character encoding (UTF-8) used by the page.
    - **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Ensures the website is responsive and fits the screen size on different devices.
    - **`<meta name="author" content="Tumpa">`**: Specifies the author of the page.
    - **`<title>`**: Sets the title of the webpage, which appears in the browser tab.
    
    ### 2. `<body>` Tag
    
    - The body contains the visible content of the HTML document, such as text, images, tables, forms, etc.
    
    ```html
    <body>
    
    ```
    
    ### 3. `<header>` Tag
    
    - Defines a header section that typically contains introductory content or navigational links. In your example, it contains a heading and a paragraph.
    
    ```html
    <header>
        <h1>Welcome Everyone</h1>
        <p>This page showcases the usage of various HTML elements</p>
    </header>
    
    ```
    
    - **`<h1>`**: Represents the main heading (Heading 1).
    - **`<p>`**: Defines a paragraph of text.
    
    ### 4. `<section>` Tag
    
    - A section element is used to define a thematic grouping of content. It often contains headings and related content.
    
    ```html
    <section>
        <h1>Tables</h1>
        <table border="1">
            <caption>Education Experience</caption>
            <thead>
                <tr>
                    <th>Degree</th>
                    <th>Institution</th>
                    <th>Year</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>BSc in CSE</td>
                    <td>ABC University</td>
                    <td>2024</td>
                </tr>
                <tr>
                    <td>HSC</td>
                    <td>XYZ</td>
                    <td>2019</td>
                </tr>
            </tbody>
        </table>
    </section>
    
    ```
    
    ### 5. `<table>` Tag
    
    - Defines a table for organizing data in rows and columns.
    
    ```html
    <table border="1">
    
    ```
    
    - **`border="1"`**: Adds a border around the table cells.
    
    ### 6. `<caption>` Tag
    
    - Provides a caption for the table.
    
    ```html
    <caption>Education Experience</caption>
    
    ```
    
    ### 7. `<thead>`, `<tbody>`, `<tr>`, `<th>`, and `<td>` Tags
    
    - **`<thead>`**: Defines the header section of the table.
    - **`<tbody>`**: Contains the main body of the table data.
    - **`<tr>`**: Represents a row within a table.
    - **`<th>`**: Defines a header cell (usually bold and centered).
    - **`<td>`**: Defines a standard table cell containing data.
    
    ```html
    <thead>
        <tr>
            <th>Degree</th>
            <th>Institution</th>
            <th>Year</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>BSc in CSE</td>
            <td>ABC University</td>
            <td>2024</td>
        </tr>
        <tr>
            <td>HSC</td>
            <td>XYZ</td>
            <td>2019</td>
        </tr>
    </tbody>
    
    ```
    
    ### 8. `<form>` Tag
    
    - Defines a form that allows users to input data and submit it to a server. In your example, it includes inputs for name, email, date of birth, gender, and a message.
    
    ```html
    <form action="">
        <label for="name">Name:</label>
        <input type="text" name="name" id="name"><br><br>
    </form>
    
    ```
    
    - **`<label>`**: Labels the form element, improving accessibility.
    - **`<input type="text">`**: Creates a single-line text input field.
    - **`<textarea>`**: Creates a multi-line text input field.
    - **`<button type="submit">`**: Creates a button to submit the form.
    
    ### 9. `<select>` and `<option>` Tags
    
    - Creates a dropdown selection box, and each `<option>` element represents an item in the dropdown list.
    
    ```html
    <label for="gender">Gender:</label>
    <select name="gender" id="gender">
        <option value="">Select</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
    </select>
    
    ```
    
    ### 10. `<video>` Tag
    
    - Embeds a video on the page. In your case, it has a height of 100px and controls for playing, pausing, etc.
    
    ```html
    <video src="flower.mp4" height="100px" controls="autoplay" >My Video</video>
    
    ```
    
    - **`controls`**: Adds playback controls like play/pause.
    - **`autoplay`**: Automatically plays the video when the page loads.
    
    ### 11. `<iframe>` Tag
    
    - Embeds another webpage within the current page.
    
    ```html
    <iframe src="<https://www.wikipedia.org/>" width="100px" height="100px"></iframe>
    
    ```
    
    - **`src`**: Specifies the URL of the page to embed.
    - **`width`** and **`height`**: Set the dimensions of the iframe.
    
    ### 12. Accessible Forms with `aria-label`
    
    - The `aria-label` attribute provides an accessible name for elements, especially for screen readers, making forms more accessible for users with disabilities.
    
    ```html
    <form action="">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" aria-label="Username"><br><br>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" aria-label="Password"><br><br>
        <button type="submit">Login</button>
    </form>
    
    ```
    
    ### 13. `<footer>` Tag
    
    - Defines the footer of the page, typically used for copyright notices, contact information, etc.
    
    ```html
    <footer>
        <p>&copy; By Tumpa Moni Mim</p>
    </footer>
    
    ```
    
    This is a complete breakdown of the tags used in your HTML code, explaining their purpose and usage in simple terms.
</details>

<details>
<summary>Assignment 03(CSS)</summary>

    
## Assignment about CSS, Syntax of CSS, External, Internal & Inline CSS, Selectors, Box model in CSS
    
### **HTML Code Breakdown:**
    
```html
<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS</title>
    <link rel="stylesheet" href="style.css"> <!-- External CSS link -->
</head>
    
<!-- Internal CSS -->
    <style>
    p {
        text-decoration: double;
        color: white;
        border: 100%;
        border-color: yellow;
        border-style: dashed;
        border-width: 3px;
        background-color: black;
    }
    </style>
    
    <!-- Inline CSS -->
    <body>
        <h1 style="color: blueviolet; text-align: center;">CSS(Cascading Style Sheet)</h1>
        <section>
            <div class="one">
                <p>CSS (Cascading Style Sheets) is a language used to describe the presentation and layout of web pages. While HTML provides the structure of a webpage, CSS controls how it looks, including colors, fonts, spacing, and overall layout</p>
            </div>
        </section>
        <section>
            <h2 id="two">This is Box Model</h2>
        </section>
        <div class="three"><h2>Class Selector</h2></div>
    </body>
    </html>
    
```
    
### **CSS Code Breakdown (style.css):**

```css
    /* CSS ID Selector */
    #two {
        color: orangered;
        border-color: turquoise;
        border-width: 5px;
        border-style: double;
    }
    
    /* Universal Selector */
    * {
        background-color: rgba(242, 163, 123, 0.5);
    }
    
    /* Class Selector */
    .three {
        background-color: orange;
        border-style: dotted;
        border-color: white;
        border-width: 2px;
        margin: 1px 2px 3px 4px;
        padding-left: 20px;
    }
    
```
### **Detailed Description:**
### **HTML:**
    
1. **`<head>` Section**: Contains meta-information about the HTML document:
        - **`<title>`**: Defines the title of the document.
        - **`<link rel="stylesheet" href="style.css">`**: Links to the external CSS file for additional styles.
2. **`<style>` Tag (Internal CSS)**:
        - **`<p>`**: Styles all `<p>` elements with a double underline, white text, a dashed yellow border, and a black background.
3. **`<body>` Section**:
        - **`<h1 style="...">`**: Uses inline CSS to set the color of the header to blueviolet and center-aligns it.
        - **`<section>` and `<div>`**: Contain text and other elements styled by the internal and external CSS.
    
### **External CSS (style.css):**
    
1. **`#two` (ID Selector)**:
        - Targets the element with the ID `two` (which is an `<h2>` in the HTML).
        - Applies an orange-red text color, turquoise border, double border style, and 5px border width.
2. **`` (Universal Selector)**:
        - Applies a semi-transparent orange background color to all elements on the page.
3. **`.three` (Class Selector)**:
        - Targets elements with the class `three` (a `<div>` in the HTML).
        - Sets an orange background, white dotted border, 2px border width, and specific margins and padding.
    
### **CSS Overview:**
    
**CSS (Cascading Style Sheets)** is used to control the presentation of HTML documents. In this code:
    
- **External CSS** is linked using `<link rel="stylesheet" href="style.css">`. This is useful for applying consistent styles across multiple pages.
- **Internal CSS** is included within the `<style>` tag in the HTML `<head>`. This is useful for styles that are specific to the current page.
- **Inline CSS** is applied directly to HTML elements using the `style` attribute. It is useful for quick, one-off styles but is generally not recommended for maintainability.
    
### **Usage in the Code:**
    
- **Internal CSS** is used to style the `<p>` element with text decoration, color, and border properties.
- **Inline CSS** is used to style the `<h1>` element directly.
- **External CSS** (in `style.css`) is used to define styles for the ID `two`, the universal selector ``, and the class `three`. This separates styles from the HTML structure, making it easier to manage and update.
    
This approach demonstrates the flexibility and power of CSS in web design, allowing for various methods of applying styles depending on the needs of the project.
</details>
