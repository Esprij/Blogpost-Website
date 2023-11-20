# Blog-Post-site
A blogpost website with a Full-Stack architecture, a manifestation of everything we have learned this year.

## Technologies/Libraires & Modules used:
<ul>
  <li>Python</li>
  <li>CSS Bootstrap</li>
  <li>JavaScript</li>
  <li>Flask</li>
  <li>Jinja</li>
  <li>SQL_Alchemy</li>
  <li>PostgreSQL</li>
  <li>SMTPlib (email communication)</li>
  <li>OS (.env variables)</li>
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
2. Program handles returned data as a JSON type or Python dictionary and cleanses data as needed
3. Flask module is imported and is called to create web application along its routes
4. With 2 Jinja templates: footer.html and header.html, 6 routes were created 3 of them dynamically automated for each blogpost
5. On the contact page POST requests can be made thanks to the HTML form that is presented in the page, once the required fields are filled and submit has been clicked, an HTML form is handled by the program to create an email message and send it to designate recipient within the program
