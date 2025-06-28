# 📘 Day 2 Coursebook: Your First Website (HTML & CSS)

Day 2 coursebook for **“Your First Website”**, covering HTML and CSS fundamentals. It’s designed to be interactive and empowering:

## Table of Contents

* [1. Course Objectives](#1-course-objectives)
* [2. Why HTML & CSS Matter](#2-why-html--css-matter)
* [3. Lesson Breakdown](#3-lesson-breakdown)

  * [3.1 HTML Fundamentals](#31-html-fundamentals)
  * [3.2 CSS Styling Basics](#32-css-styling-basics)
* [4. Suggested Activities](#4-suggested-activities)
* [5. Resources & Further Learning](#5-resources--further-learning)
* [6. Summary & Next Steps](#6-summary--next-steps)

</br>

## 1. Course Objectives 🎯

By the end of Day 2, students will:

* Understand HTML structure and build a basic webpage.
* Learn core HTML tags (headings, lists, images, links).
* Apply styling with CSS (colors, typography, layout).
* Use browser dev tools to inspect and adjust styles interactively.
* Develop confidence building and styling their "About Me" page.



## 2. Why HTML & CSS Matter

* **HTML** is the backbone of the web—it defines content and structure.
* **CSS** styles that structure: it brings pages to life visually.
* Learning both together instills a web-development mindset: structure + design.
* These skills are fundamental and essential stepping stones toward more advanced web development.



## 3. Lesson Breakdown

### 3.1 HTML Fundamentals

**a. Introduction (10 min)**
Explain HTML’s purpose: markup language describing elements on a page. Emphasize it’s like the skeleton.

**b. Live Demo (20 min)**
Build a basic HTML file together, covering:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About Me</title>
</head>
<body>
  <h1>Your Name</h1>
  <p>This is my first web page!</p>
  <h2>My Hobbies</h2>
  <ul>
    <li>Reading</li>
    <li>Music</li>
    <li>Code</li>
  </ul>
  <a href="https://example.com" target="_blank">Visit Example</a>
  <img src="https://via.placeholder.com/150" alt="Placeholder Image">
</body>
</html>
```

**c. Hands-on Practice (20 min)**
Students create their own HTML page exploring:

* Headings & paragraphs
* Lists (ordered/unordered)
* Links (internal and external)
* Images (with alt text)

**d. Pair Share (10 min)**
Students pair up to review each other’s HTML structure and ask questions.



### 3.2 CSS Styling Basics

**a. Why CSS? (5 min)**
Explain separation of concerns: structure (HTML) vs. style (CSS). Introduce the **box model** concept.

**b. Live Styling Demo (25 min)**
Add a `<link rel="stylesheet" href="style.css">` to HTML and explore CSS:

```css
body {
  font-family: Arial, sans-serif;
  margin: 20px;
  line-height: 1.6;
}

h1 {
  color: #2c3e50;
}

ul {
  list-style-type: square;
}

a {
  color: #3498db;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

img {
  max-width: 100%;
  border: 2px solid #ccc;
}
```

Use DevTools in the browser to tweak CSS live and observe changes.

**c. Customize Your Page (20 min)**
Students adjust styles with encouragement to experiment:

* Change fonts, colors, spacing
* Add margins/padding
* Style links and images

**d. Showcase & Feedback (15 min)**
Each student presents their styled page. Group gives quick feedback using CSS vocabulary ("nice margin", "cool color choice").



## 4. Suggested Activities

1. **About Me Page**

   * Build a simple webpage with heading, bio, hobbies, link, and image.
   * Style it using CSS—focus on color and readability.

2. **Resource Scavenger Hunt**

   * Locate examples of HTML tags and CSS styles in MDN or W3Schools.
   * Encourage exploration of semantic HTML, the box model, and CSS selectors ([w3schools timeline guide](https://www.w3schools.com/howto/howto_css_timeline.asp)) ([youtube.com][1], [youtube.com][2], [teaching-materials.org][3], [khanacademy.org][4], [codecademy.com][5], [w3schools.com][6]).

3. **CSS Timeline Project (Extra Credit)**

   * Challenge: create a simple vertical timeline using HTML & CSS grid or Flexbox based on tutorials like the W3Schools timeline ([geeksforgeeks.org][7]) or DEV Community timeline ([dev.to][8]).



## 5. Resources & Further Learning

* **Video Course**: “Learn HTML & CSS – Full Course for Beginners” (YouTube) ([youtube.com][9])
* **Interactive guide**: Shay Howe’s *Learn to Code HTML & CSS* ([learn.shayhowe.com][10])
* **Hands-on tutorial**: W3Schools HTML/CSS editors
* **Practical book**: *HTML & CSS: Design and Build Websites* by Jon Duckett


## 6. Summary & Next Steps

* **Today**: you learned HTML syntax, structure, basic CSS, and styling skills.
* **Tonight**: refine your "About Me" page and push it to GitHub (practice your Day 1 Git skills!).
* **Tomorrow**: we’ll dive into **JavaScript**, bringing your page to life with dynamic behavior.

</br>

✨ **Pro Tip**: Doesn’t have to be perfect—start simple and iterate. This is your demo playground!

[1]: https://www.youtube.com/playlist?list=PLgGbWId6zgaWZkPFI4Sc9QXDmmOWa1v5F "30 Days to Learn HTML & CSS (Full Course) - YouTube"
[2]: https://www.youtube.com/watch?pp=0gcJCfwAo7VqN5tD&v=t5AE66WgQD0 "Create Timeline Design For Website Using HTML & CSS - YouTube"
[3]: https://www.teaching-materials.org/htmlcss-1day/ "Intro to HTML/CSS - teaching-materials.org"
[4]: https://www.khanacademy.org/computing/computer-programming/html-css "Intro to HTML/CSS: Making webpages - Khan Academy"
[5]: https://www.codecademy.com/catalog/language/html-css "Best HTML + CSS Courses & Tutorials - Codecademy"
[6]: https://www.w3schools.com/howto/howto_css_timeline.asp "How To Create a Timeline - W3Schools"
[7]: https://www.geeksforgeeks.org/css/how-to-create-timeline-using-css/ "How to create timeline using CSS? - GeeksforGeeks"
[8]: https://dev.to/divyeshkamalanaban/making-a-simple-css-timeline-for-beginners-1ccg "Making a simple CSS timeline for beginners! - DEV Community"
[9]: https://www.youtube.com/watch?pp=ygUMI2Nzc3dpdGhodG1s&v=a_iQb1lnAEQ "Learn HTML & CSS – Full Course for Beginners - YouTube"
[10]: https://learn.shayhowe.com/html-css/ "Learn to Code HTML & CSS - Shay Howe"
