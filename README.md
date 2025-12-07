# CIS 260 - Business-Personal Webpage
Project Description: A brief summary of the project's goals, functions, and usage. 
A business-personal webpage to highlights business-personal human character, inclusive to an a breif character overview
with an idenifing photo intergration, current, most pertinent or most recent experience, work, and/or project, to also include an education section, publications and/or porfolio section, with downloadable pdf documentation, and to include ontact message data entry intergrations to an end-user data intergration to a database spreadsheet
License: A statement of the license under which the software is released. 
1: HTML specification maintained by the WHATWG (Web Hypertext Application Technology Working Group), is released under the CC0 1.0 Universal (Public Domain Dedication) license
Iva M. Brooks — Cybersecurity Portfolio
Overview

This is the personal portfolio website of Iva M. Brooks, a cybersecurity enthusiast and continuing education student. The site showcases her bio, experience, publications, awards, and includes a mock contact system with Excel integration for collecting and exporting contact messages.

The project uses HTML, Tailwind CSS, and SheetJS (XLSX) to handle Excel functionality directly in the browser.

FEATURES

Modern design with mobile-first approach using Tailwind CSS

Smooth scrolling for links

Dark-mode 

Bio, Education, Experience, Publications, Awards sections

Downloadable resume

Contact form:

Add new messages

Preview in-page as a table

Export all contact form messages to Excel (ContactData.xlsx) **live version not mock version**

Load existing Excel files to prefill contact list

Prevent duplicate email entries

Clear all in-memory contacts

Auto-updating copyright year

Accessible and semantic HTML structure

Tech Stack

HTML5 & CSS3

Tailwind CSS (via CDN)

JavaScript (vanilla)

SheetJS (xlsx.full.min.js) for Excel file handling

Optional PDFs for resume and publications

File Structure
/project-root
│
├─ index.html              # Main portfolio HTML file
├─ static/
│   ├─ favicon.png          # Light mode favicon
│   ├─ favicon-dark.png     # Dark mode favicon
│   ├─ profile.png          # Profile image
│   ├─ resume.pdf           # Downloadable resume
│   ├─ presentation.pdf     # Publication PDF 1
│   └─ publication-1.pdf    # Publication PDF 2
└─ README.md               # This file

Usage Instructions
1. Open the Website

Simply open index.html in any modern web browser.

No server setup is required; all functionality runs in the browser.

2. Contact Form Features

Add Contact: Fill in Name, Email, and Message → Click Send. The entry appears in the table below.

Load Excel: Click Load Excel to import contact messages from a .xlsx file.

Export Excel: Click Export ContactData.xlsx to save all current messages locally.

Clear All: Clears in-memory contact data (does not delete existing Excel files).

3. Accessibility

Mobile-first, responsive layout

Semantic headings and form labels

Fallback for no JavaScript (form still visible but Excel export/import unavailable)

How It Works (Contact System)

In-memory array: Contacts are stored in a JavaScript array, with headers: ["Name", "Email", "Message"].

Excel import: Reads the first sheet from an uploaded Excel file and populates the in-page table.

Excel export: Converts the current contacts array to an Excel file (ContactData.xlsx) and triggers browser download.

Duplicate prevention: Checks for duplicate emails before adding new entries.

Table preview: Renders all contacts in a clean, scrollable table.

Customization

Update colors in <style>:

.accent { color: #a8c256; }
.accent-bg { background-color: #cde3a3; }
.btn-primary { background-color: #a8c256; color: white; }


Replace static PDFs and images in /static with your own content.

Modify education, experience, awards, and publications sections directly in HTML.

Adjust table headers or form fields in JavaScript if needed.

Deployment

Can be hosted on GitHub Pages, Netlify, Vercel, or any static hosting platform.

Simply push all files including /static folder and index.html.

No server-side processing is required.

License

This project is personal and free to use for portfolio purposes. All content belongs to Iva M. Brooks.

Contact

Email: contactme@mindingmyownbusiness.org

Phone: +1 312-111-1111

Location: PO Box 100 Main Street, Chicago, Illinois 60601
## Dependencies
1. HTML 
2. CSS
3. phpoffice/phpspreadsheet


This HTML page runs entirely in a browser
