## 1. Website type and content

The website I created is a personal portfolio website for Joseph Phiri. It is designed as a clean, professional one-page profile that presents who I am, what I do, my skills, projects, experience, and how to contact me.

The content includes:
- Intro section with a welcome message and headline
- About Me section
- Skills and expertise section
- Featured Projects section
- Experience timeline
- Notes and interests
- Contact form and address details

This structure is visible in `index.html`.

---

## 2. HTML Elements

### 1) Five elements that were most challenging and why
1. form  
   This was challenging because it requires several related elements such as label, input, select, textarea, and button to work properly and remain understandable.

2. table  
   Tables require careful use of caption, thead, tbody, tr, th, and td so the information is readable and accessible.

3. dl, dt, dd  
   This structure is less common than lists, and it can be confusing to organize definitions and terms correctly.

4. nav  
   It needed to support internal page navigation with multiple anchor links, which required careful use of href values and section IDs.

5. section and article  
   These elements are semantic and powerful, but choosing where to break content into sections and articles required planning so the page remained clear and logical.

### 2) How semantic elements were used
The page uses semantic HTML to organize content clearly:
- header contains the main navigation
- nav provides links to different parts of the page
- main wraps the primary content
- section separates each major content area such as About, Skills, Projects, Experience, and Contact
- article groups related content within sections, such as a project description or skill category
- aside contains a short quote
- footer includes secondary navigation and copyright information

This structure makes the website easier to read, easier to navigate, and more accessible to screen readers.

### 3) Most useful element for organizing layout
The most useful element was section. It allowed the page to be divided into strong content blocks with clear headings. This made the page easy to organize and gave each part a distinct purpose.

---

## 3. HTML Attributes

### 1) Three essential attributes
The most essential attributes used were:
- href: required for navigation links and external links
- id: used to target anchors and identify unique sections
- required: used in form fields so users must provide information before submitting

Other useful ones included:
- aria-label for navigation accessibility
- type for input fields
- placeholder for form guidance
- target and rel for external links
- rows and cols for textarea size

### 2) Difference between class and id
I used id attributes to identify unique sections and elements such as home, about, skills, projects, experience, and contact. These are important because they support internal navigation using anchor links.

I did not use class attributes in this version of the website because the page was kept simple and semantic, and the structure was already organized with section IDs. In a larger page, class would be useful for grouping similar elements for styling or reuse.

### 3) Attribute that improved user experience most
The attribute that improved user experience the most was aria-label on the nav elements. It helps screen readers announce the purpose of the navigation clearly, which makes the website more accessible and easier to use for all visitors.

---

## 4. Development process

### 1) Planning before coding
Before writing code, I planned the website structure around the main goals:
- create a homepage
- include personal introduction
- add about, experience, and skills
- show project examples
- include a form for contact
- use semantic sections for organization

I sketched the content flow first, then matched it to meaningful HTML elements and section headings.

### 2) Testing and debugging
I checked the page structure carefully while building it. This included:
- confirming all closing tags were correct
- making sure headings were used in a logical order
- checking that internal links matched section IDs
- ensuring form controls had labels
- reviewing the page in the browser to confirm it looked and behaved as intended

This helped catch broken layout structure and missing attributes early.

### 3) Challenges and how they were overcome
The main challenges were:
- organizing content semantically without overusing tags
- keeping the page readable and structured
- making sure the form and navigation worked correctly

These were solved by keeping the structure simple, using clear section labels, and testing each part as it was added.

---

## 5. Git and GitHub implementation

### 1) Git commands used
The Git workflow included:
- git clone
- git config user.name
- git config user.email
- git branch -M main
- git add `index.html`
- git commit -m "Add personal website"
- git push -u origin main

### 2) Number of commits and commit strategy
There was one commit made for the initial repository version:
- Add personal website

The commit strategy was simple and direct: one clear message describing the main purpose of the change.

### 3) Why version control is important
Version control is important because it:
- saves progress over time
- allows you to track changes
- makes it easy to revert mistakes
- supports teamwork and collaboration
- helps keep projects organized and professional

For web development, it is especially useful when improving features, fixing errors, or preparing a final website release.

---

## 6. Code quality and best practices

### 1) How HTML validity and error-free code were ensured
I checked the code manually for:
- properly nested elements
- matching opening and closing tags
- unique IDs for each section
- valid attribute values
- consistent semantic structure

This helps keep the HTML clean and understandable.

### 2) Best practices followed
I followed these best practices:
- semantic HTML structure
- meaningful section headings
- proper use of labels and form controls
- internal navigation through anchor links
- organized content flow from top to bottom
- readable indentation and spacing

### 3) Improvements if more time were available
If more time were available, I would:
- add styling to make the page more visually appealing
- make it responsive for mobile devices
- include more project detail and contact information
- add a stronger visual identity using color and spacing
- refine the contact form and add a real submission destination

---

This website is now represented in `index.html`, and the GitHub repository was updated with the project as requested.
