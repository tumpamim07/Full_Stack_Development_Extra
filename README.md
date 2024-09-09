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
