# The State of North Dakota — Multi-Page Website

A responsive, multi-page website built for WGU's Front End Web Development course (D277). The site introduces North Dakota, "The Peace Garden State," with dedicated pages for the capital and two additional cities, along with a contact form featuring client-side email validation.

🔗 **Live site:** [samoyatech.github.io/My-ND-Website1-D277](https://samoyatech.github.io/My-ND-Website1-D277/)

## Overview

This project demonstrates core front-end fundamentals: semantic HTML structure, external CSS styling with multiple selector types and positioning techniques, and vanilla JavaScript form validation — all built without any frameworks or libraries.

## Pages

- **Home** (`index.html`) — introduces North Dakota, its nickname, geography, and quality of life
- **Bismarck** (`bismarck.html`) - the state capital
- **Fargo** (`fargo.html`) — featured city
- **Wahpeton** (`wahpeton.html`) - featured city
- **Explore** (`explore.html`) - additional content page
- **Contact** (`contact.html`) - contact form with email confirmation validation

Each city page includes population, year incorporated, region of the state, urban/suburban/rural classification, and average income level relative to the rest of the state.

## Features

- Consistent navigation bar across all pages, including an external link (ND Jobs) that opens in a new tab
- Semantic HTML structure using `<header>`, `<nav>`, `<section>`, and `<aside>` elements
- Ordered and unordered lists, and a data table, used to organize page content
- Hover effects on navigation links and image thumbnails
- Layout built with a mix of float and absolute/relative positioning
- Contact form with first name, last name, email, confirm-email, and message fields, all with placeholders
- JavaScript validation (`formvalidation.js`) that checks the two email fields match before allowing submission

## Tech Stack

- HTML5
- CSS3 (external stylesheet, `style.css`)
- Vanilla JavaScript

## Running Locally

No build steps or dependencies required. Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/SamoyaTech/My-ND-Website1-D277.git
cd My-ND-Website1-D277
```

Then open `index.html` directly, or serve it with a simple local server (e.g. the VS Code Live Server extension).

## Course Context

Built for the Task 2 Performance Assessment in WGU's D277: Front End Web Development course.


## Task Requirements

A. Create 4–10 web pages of content for your website with a main page that introduces the state of your choice and additional pages for the capital and two other cities located within the state. The information for the capital and each city can vary but must include the following:


the city's population
the year the city was incorporated
the region of the state in which the city is located
the classification of the city: urban, suburban, and/or rural
the average income level of the city compared to the rest of the state



Include the following items on each page, using a suitable HTML element:

a title in the head of each document that describes the web page's individual topic
a relevant image, including alternative text for the image
a consistent menu that allows the user to navigate to any other page on the site



Include the following semantic elements from Task 1 on each page:

a header containing introductory content (pertaining to the document as a whole or a particular section of a document)
a nav to place the links to navigate throughout the site
a section to display the main content of the page
an aside to display information related to the content





B. Include each of the following elements within your website, using suitable markup:


a link that opens an external website in a new window or tab using the target attribute
an HTML-coded ordered list with at least three list items
an HTML-coded unordered list with at least three list items
an HTML-coded table consisting of 3–6 columns and 3–6 rows to organize content


C. Create an external CSS file with the following CSS rules and formatting, and apply these rules to enhance your website content:


each of the following styles for text:

one font-family declaration
a :hover pseudo-class to create a rollover effect for navigation buttons



a float property to position at least one HTML element to the side of another in your web page
absolute and relative positioning in at least one area of your web page
each of the following selectors:

one element selector to style the HTML elements
one class selector that is used at least two times to style HTML elements
one ID selector to format specific elements of a page





D. Add a form on one page of your website by doing the following:
Note: The form does not need to include a functional Submit button.


Include text fields for the user's first name, the user's last name, and the user's email address, as well as a confirmation field for the email address for verification purposes and a text box that allows the user to ask a question.
Ensure all fields contain placeholders.



Include JavaScript code that verifies the email fields match when a user enters a second email address.


E. Upload your website to one of the hosting sites listed in the Web Links section. Your website must include the following components:


HTML pages
external CSS document(s)
all images uploaded to the website
