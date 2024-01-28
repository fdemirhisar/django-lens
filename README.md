Blogger Website using Django

This project is a simple website created using Django, HTML, and CSS, designed for a blogger to showcase their content. The website includes features such as a homepage, about page, contact page, and services page. It utilizes Django's powerful framework to handle routing and data rendering, while HTML and CSS are used for the frontend design and layout.

Features

Homepage: Welcome page for visitors with a brief introduction to the blogger and their content.
About Page: Provides information about the blogger, their background, and interests.
Contact Page: Allows visitors to get in touch with the blogger via a contact form or provided contact details.
Services Page: Highlights any services or offerings provided by the blogger, such as consultations, coaching, or content creation.
Responsive Design: The website is designed to be responsive, ensuring optimal viewing experience across various devices and screen sizes.
Technologies Used

Django: Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design.
HTML: HTML is the standard markup language for creating web pages and web applications.
CSS: CSS is a style sheet language used for describing the presentation of a document written in HTML.

Project Structure

project/
│
├── main/
│   ├── templates/
│   │   └── main/
│   │       ├── base.html
│   │       ├── home.html
│   │       ├── about.html
│   │       ├── contact.html
│   │       └── services.html
│   │
│   └── static/
│       └── css/
│           └── styles.css
│
├── project/
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   └── wsgi.py
│
├── manage.py
│
└── README.md
Getting Started

To run this project locally, follow these steps:

Clone the repository to your local machine.
Navigate to the project directory.
Run the Django development server with python3 manage.py runserver.
Access the website at http://localhost:8000 in your web browser.
