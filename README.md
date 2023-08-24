# Blog-Post-site
A website that is designed for blog posting, 
please keep in mind that this is just a template and no content within this website is relevant.

## Technologies/Libraires & Modules used:
<ul>
  <li>HTML requests</li>
  <li>HTML forms</li>
  <li>CSRF tokens</li>
  <li>API routing</li>
  <li>Bootstrap</li>
  <li>Flask</li>
  <li>Jinja</li>
  <li>SMTPlib</li>
  <li>Python</li>
  <li>HTML</li>
  <li>CSS</li>
  <li>JS</li>
</ul>

## What was learned/practiced:
<li>HTML templating</li>
<li>HTML requests</li>
<li>HTML forms</li>
<li>Contacting APIs</li>
<li>Flask-Jinja templating</li>
<li>Manipulating/Clensing JSON data</li>

## Future updates/Further implementations:
1. WTForm templating in "contact" page instead of regular HTML form
2. Database architecture, that gives us the ability to manage users on our website

## Thorough explanation:
Although it is a simple blog post site on the outside with an attractive styling, 
how it was put together may tell you the opposite.
This project is an acclamation to the techologies & methods we have learned over the summer of 2023.

1. The program uses an API to generate all the content inside each blog post
2. Program handles returned data as a JSON type or Python dictionary and clenses data as needed
3. Flask module is imported and is called to create web application along its routes
4. With 2 Jinja templates: footer.html and header.html, 6 routes were created 3 of them dynamically automated for each blog-post
5. On the contact page POST requests can be made thanks to the HTML form that is presented in the page, once the required fileds are filled and submit has been clicked, an HTML form is handled by the program to create an email message and send it to designated recipient within the program
