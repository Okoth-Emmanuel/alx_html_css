Here is a clean and professional **README.md** for your `css_basic` project.
You can paste this directly into a README.md file inside the `css_basic` directory.

---

# **CSS Basic Project**

This project is part of the **ALX Front-End Curriculum**, focusing on introducing basic CSS concepts and applying them to previously created HTML files.
The goal is to link external CSS files to HTML pages and understand how styling rules affect the appearance of a webpage.

---

## **Project Structure**

```
alx_html_css/
└── css_basic/
    ├── index.html
    ├── tweets.html
    ├── base.css
    ├── styles.css
    └── README.md
```

---

## **Tasks Completed**

### **1. Created `css_basic` Directory**

A new directory named **css_basic** was created inside the main repository `alx_html_css`.

### **2. Copied HTML Files**

The following HTML files were copied from the `html_basic` directory into `css_basic`:

* `index.html`
* `tweets.html`

These files will now be styled using CSS.

### **3. Added CSS Files**

Two CSS files were created:

* **base.css** – contains global default styles (layout, fonts, body structure).
* **styles.css** – an empty file meant for custom user-defined styles.

### **4. Linked CSS Files to HTML**

Both HTML files (`index.html` and `tweets.html`) were updated by adding the following lines inside the `<head>` tag:

```html
<link href="base.css" rel="stylesheet">
<link href="styles.css" rel="stylesheet">
```

This links the CSS files to the pages so that the styling rules are applied.

---

## **Purpose of the Files**

### **base.css**

Includes foundational styles such as:

* Smooth scrolling
* Body margin reset
* Font styling
* Basic header and footer layout
* Link color definition

These rules improve the default appearance of the webpage.

### **styles.css**

This file is intentionally empty.
It is meant for adding your own custom CSS later in the project.

---

## **How to View the Styled Pages**

1. Open the `css_basic` directory.
2. Open `index.html` and `tweets.html` in your browser.
3. You should notice:

   * Cleaner layout
   * Better spacing
   * Consistent fonts
   * Improved readability

These improvements come from the CSS rules in `base.css`.

---

## **Author**

Project completed by **Okoth Emmanuel** as part of the ALX Front-End Web Development course.


