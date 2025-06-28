# 📘 Day 3 Coursebook: JavaScript Fundamentals

[Build a Tip Calculator with Vanilla JavaScript for Beginners (HTML, CSS, JS)](https://www.youtube.com/watch?pp=ygURI3RpcGNhbGN1bGF0b3JhcHA%3D&v=Q3PjnZxW6i0&utm_source=chatgpt.com)
 </br>

## Table of Contents

1. [🎯 Objectives](#1-objectives)
2. [🧠 Why JavaScript?](#2-why-javascript)
3. [🔎 Core Concepts](#3-core-concepts)

   * 3.1 [Variables & Data Types](#31-variables--data-types)
   * 3.2 [Conditionals](#32-conditionals)
   * 3.3 [Loops & Iteration](#33-loops--iteration)
   * 3.4 [Functions](#34-functions)
   * 3.5 [DOM Manipulation & Events](#35-dom-manipulation--events)
4. [🚀 Guided Project: Tip Calculator](#4-guided-project-tip-calculator)
5. [🛠 Practice Activities](#5-practice-activities)
6. [📚 Resources](#6-resources)
7. [📝 Summary & Homework](#7-summary--homework)



## 1. Objectives

By the end of Day 3, students will:

* Declare variables, and use JS data types: strings, numbers, booleans
* Write conditional logic (`if`, `else`)
* Implement loops (`for`, `while`) using JavaScript
* Define and invoke functions
* Manipulate DOM and respond to user events
* Build a functional tip calculator web app



## 2. Why JavaScript?

* Adds **behavior** to your HTML structure—making websites dynamic
* Powers interactivity and user engagement
* Lays the foundation for further learning: frameworks, APIs, server-side code



## 3. Core Concepts

### 3.1 Variables & Data Types

* Examples: `let`, `const`
* Types: numbers (`42`), strings (`"hello"`), booleans (`true/false`)
* Practice: log variables using `console.log()`

### 3.2 Conditionals

* Syntax:

  ```js
  if (condition) {
    // ...
  } else {
    // ...
  }
  ```
* Use cases: validate input or responses

### 3.3 Loops & Iteration

* `for`: runs code repeatedly

  ```js
  for (let i = 0; i < 5; i++) console.log(i);
  ```
* `while`: loops with a condition
* `break` / `continue` to control flow
* Why? Automate repetition (e.g., iterate through arrays)
  ([learn-js.org][1], [developer.mozilla.org][2], [learnjavascript.online][3], [blog.teamtreehouse.com][4], [dev.to][5], [spacebro.io][6])

### 3.4 Functions

* Define reusable code blocks:

  ```js
  function calculateTip(amount, percent) {
    return amount * percent;
  }
  ```
* Call, pass arguments, and use return values

### 3.5 DOM Manipulation & Events

* Use `document.querySelector`, `addEventListener`
* Change content/styles (`innerText`, `textContent`)
* Handle user input and clicks



## 4. Guided Project: Tip Calculator 💡

**Overview**: Combine HTML, CSS, and JS to build an interactive tip calculator.

**Steps**:

1. **HTML**: Inputs for bill, tip %, number of people; calculate button; display area.
2. **CSS**: Basic styling for clarity and layout.
3. **JS Logic**:

   * Get input values
   * Validate inputs
   * Calculate tip per person
   * Display result and handle edge cases (“each” label)
     ([blog.teamtreehouse.com][4], [reddit.com][7], [geeksforgeeks.org][8])

**Live Demo & Code**: Follow the video above for complete walkthrough.



## 5. Practice Activities

* **Mini-Calculator Variants**:

  * **Geometry calculator** (area = base × height / 2)
  * **Currency converter** (divide/multiply rates)

* **Loop Exercises with Learn‑JS**:

  * Visit learn‑js.org "Loops" section
  * Build small loop tasks: iterate through arrays, print values
    ([learn-js.org][9])



## 6. Resources

* **Interactive JS Course**: LearnJavaScript.online (free intro, includes variables, loops, DOM)
  ([learnjavascript.online][3])
* **Codecademy JavaScript Course**: loops, conditionals, functions, projects
  ([codecademy.com][10])
* **MDN JavaScript Loops**: in-depth guide
  ([developer.mozilla.org][2])



## 7. Summary & Homework

**Today’s Highlights**:

* Learned JS fundamentals: variables → events
* Built a working tip calculator

**Homework**:

* Polish your tip calculator: add features (reset button, validation messages)
* Try a mini-project: geometry or currency converter
* Share your live page on GitHub, ready for review in Day 4



### ✨ Pro Tips

* Use `let` and `const` correctly
* Log values to debug (`console.log`)
* Modularize: one function per behavior
* Validate user input before calculation

</br>

Great work today, Ready for Day 4 to refine your programming logics and explore integration with your site!

[1]: https://www.learn-js.org/en/Loops "Loops - Learn JavaScript - Free Interactive JavaScript Tutorial"
[2]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration "Loops and iteration - JavaScript - MDN Web Docs - Mozilla"
[3]: https://learnjavascript.online/ "Learn JavaScript"
[4]: https://blog.teamtreehouse.com/build-a-javascript-tip-calculator "Build a JavaScript Tip Calculator - Treehouse Blog"
[5]: https://dev.to/thedevdrawer/create-a-restaurant-bill-and-tip-calculator-in-javascript-25ep "Create A Restaurant Bill and Tip Calculator in JavaScript"
[6]: https://spacebro.io/articles/create-tip-calculator-javascript "How To Create a Tip Calculator in JavaScript | Alan Medina"
[7]: https://www.reddit.com/r/learnjavascript/comments/nhn03s/i_created_a_free_interactive_7hour_js_course_for/ "I created a free & interactive 7-hour JS course for beginners - Reddit"
[8]: https://www.geeksforgeeks.org/design-a-tip-calculator-using-html-css-and-javascript/ "Design a Tip Calculator using HTML, CSS and JavaScript"
[9]: https://www.learn-js.org/ "Learn JavaScript - Free Interactive JavaScript Tutorial"
[10]: https://www.codecademy.com/learn/introduction-to-javascript "Learn JavaScript - Codecademy"
