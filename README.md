# bic21203-lab4b-JSONQuery


# Lab 4b – Client-Side Scripting (JSON and jQuery)

## Subject Information
- **Subject:** BIC21203 Web Development
- **Lab:** Lab 4b
- **Topic:** JSON and jQuery

## Project Description

This lab focuses on client-side scripting using JSON, modern JavaScript and jQuery. The activities involve creating JSON data, retrieving and displaying information using the fetch() API, and performing DOM operations using jQuery.

## Question 1 – Create and Structure JSON Data

Created a file named `books.json` containing two book objects. Each book includes:
- Title
- Author
- Publication year
- Genres

The JSON file was structured using a top-level books array and validated to ensure correct JSON syntax.

### Screenshot
<img width="1267" height="766" alt="picture1" src="https://github.com/user-attachments/assets/ec9875ab-25c7-48da-895e-2c14724c9e5a" />



## Question 2 – Retrieve and Display JSON Data

Created `books.html` using the JavaScript fetch() API to retrieve information from `books.json`.

The webpage displays:
- Title of the first book.
- Author of the second book.
- Genres of both books, grouped by book title.

The textContent and createElement() methods are used to display the information. Error handling is also implemented using try...catch.

### Screenshot
<img width="948" height="647" alt="picture2" src="https://github.com/user-attachments/assets/9a4a6a59-5725-474e-867a-dae682ec7902" />



## Question 3 – Compare Native JavaScript and jQuery

Created `jquery-dom.html` using jQuery 4.0.0 to perform three DOM operations:

1. `.text()` – Changes the text content to "Modified Text".
2. `.addClass()` – Adds the `myStyle` CSS class to the div element.
3. `.on("click")` – Handles the button click event and displays an alert message.

### Screenshots
<img width="948" height="358" alt="picture3" src="https://github.com/user-attachments/assets/a15d0e3c-df8a-47dd-9fef-2a2b700a4a12" />

<img width="956" height="546" alt="picture4" src="https://github.com/user-attachments/assets/568b2ba0-8c7c-4d33-8f08-e7b17e282d80" />


