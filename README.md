
# Personal Portfolio Website

A semantic, accessible, and well-structured personal portfolio website built using **HTML5** and **basic JavaScript**.  
This project demonstrates core HTML concepts, accessibility best practices, and clean document structure.


##  Project Overview

**Project Name:** Personal Portfolio Website  
**Author:** Nishit Jadiya  

### Objective
To design and develop a personal portfolio website that showcases skills, projects, and contact information using **pure HTML** and minimal JavaScript.

### Key Goals
- Learn and apply semantic HTML5
- Build accessible web pages
- Structure content logically
- Implement basic client-side form handling

---

##  HTML Concepts Learned & Portfolio Structure

### HTML Concepts Used
- **Semantic HTML5:** `header`, `nav`, `main`, `section`, `article`, `footer`
- **Accessibility (ARIA):**
  - `aria-label`
  - `aria-labelledby`
  - `aria-live`
  - `role="list"` and `role="listitem"`
- **Forms & Inputs:**
  - Required fields
  - Email validation
  - Consent checkbox
  - Honeypot spam protection
- **Anchor Navigation:** Section-based internal links
- **Client-side JavaScript:** Validation and dynamic content update

### Portfolio Structure
1. **Header:** Navigation menu
2. **Intro Section:** Personal introduction and current status
3. **Skills Section:** Categorized technical skills
4. **Projects Section:** Project summaries with tech stack and links
5. **Contact Section:** Interactive contact form
6. **Footer:** Copyright information



## Setup Instructions

No external dependencies or installations required.

### Steps
1. Clone or download the repository
2. Open `index.html` in any modern web browser
3. The website runs locally without a server



##  Code Structure

```text
index.html
│
├── <head>
│   ├── Meta tags
│   └── Title
│
├── <header>
│   └── Navigation
│
├── <main>
│   ├── Intro Section
│   ├── Skills Section
│   ├── Projects Section
│   └── Contact Section
│
├── <footer>
│   └── Copyright
│
└── <script>
    ├── Form validation
    └── Dynamic year update


```
## Visual Documentation
<img width="1737" height="1003" alt="landing-page-image" src="https://github.com/user-attachments/assets/fcd28b5c-91ac-487c-bf2f-6189aed8808b" />
<img width="531" height="345" alt="contact-pg-image" src="https://github.com/user-attachments/assets/6b3e9247-04c2-45a6-bebc-9964687fc55b" />
<img width="490" height="350" alt="contact-response-image" src="https://github.com/user-attachments/assets/59fb4a73-6246-442d-b87f-7a5e3f027550" />




## Technical Details
### Navigation

1. Implemented using <nav> and anchor links

2. Smooth section-based navigation

3. ARIA labels improve screen-reader support

### Skills Section

1. Uses semantic roles for grouped items

2. Custom data-skill-category attributes allow future extensibility

### Projects Section

1. Each project wrapped in <article>

2. Clear separation of project details

3. External links open securely using rel="noopener"

### Contact Form

1. Required field validation

2. Honeypot field for bot prevention

3. Consent checkbox enforcement

4. Real-time feedback using aria-live

### JavaScript Logic

1. Prevents invalid submissions

2. Displays user feedback messages

3. Dynamically updates the footer year

## Testing Evidence

| Test Case             | Expected Result    | Status |
| --------------------- | ------------------ | ------ |
| Empty form submission | Error message      | Passed |
| Consent unchecked     | Submission blocked | Passed |
| Valid submission      | Success message    | Passed |
| Honeypot filled       | Spam detected      | Passed |
| Navigation links      | Scroll correctly   | Passed |
| Footer year           | Shows current year | Passed |

## Conclusion

This project demonstrates effective use of:
1. Semantic HTML
2. Accessibility best practices
3. Clean and maintainable code
4. Basic JavaScript for interactivity

It serves as a solid foundation for future enhancements like CSS styling, animations, or backend integration.

## Author

Nishit Jadiya,
Software Engineering Student
```
MERN Stack | Flutter | Web Development
```
## License

This project is for academic and personal portfolio use.
