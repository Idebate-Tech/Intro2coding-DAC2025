# 📘 Day 4 Coursebook: Advanced JavaScript
Day 4 Coursebook** for **“Advanced JavaScript: Logic, Loops, Functions & DOM”**, designed to help students deepen their skills in programming logic and interactivity:

## Table of Contents

1. [🎯 Objectives](#1-objectives)
2. [🧠 Why We Level Up Today](#2-why-we-level-up-today)
3. [🔎 Core Topics](#3-core-topics)

   * 3.1 Logical Expressions & Conditionals
   * 3.2 Loops Refresher + Introduction to Complex Use
   * 3.3 Functions: Parametric & Reusable
   * 3.4 DOM & Event Handling Deep Dive
4. [🚧 Guided Challenges & Mini Projects](#4-guided-challenges--mini-projects)
5. [💡 Group Activity: Dynamic List App](#5-group-activity-dynamic-list-app)
6. [📚 Recommended Resources](#6-recommended-resources)
7. [📝 Summary & Homework](#7-summary--homework)



## 1. Objectives 🎯

By the end of today, students will:

* Combine conditionals with loops for complex logic
* Utilize functions effectively for abstraction
* Build reusable code modules
* Enhance web pages with event-driven JavaScript
* Create a dynamic list app with add/remove/edit abilities



## 2. Why We Level Up Today

* **Complex logic** (nested-if, switch) powers intelligent behaviors
* **Loops + conditions** allow searching, filtering, sorting
* **Functions** reduce repetition and introduce modularity
* **Events & DOM** make pages interactive and responsive to user input


## 3. Core Topics

### 3.1 Logical Expressions & Conditionals

Reinforce branching:

```js
if (score >= 90) {
  grade = 'A';
} else if (score >= 80) {
  grade = 'B';
} else {
  grade = 'C';
}
```

Compare to **switch statements**:

```js
switch(day) {
  case 'Mon': activity = 'Work'; break;
  case 'Sat': activity = 'Relax'; break;
  default: activity = 'Unknown';
}
```

### 3.2 Loops Refresher + Complex Use

* **for, while, do…while** loops
* Looping constructs: **nested loops**, `break`, `continue`
* Using loops in arrays, or to generate UI elements dynamically
* Practice with **FizzBuzz**, grading systems — 60+ problems on loops and logic ([scribd.com][1], [gurukultti.org][2], [w3resource.com][3])

### 3.3 Functions: Parametric & Reusable

Design modular code:

```js
function calculateGrade(score) {
  if (score >= 90) return 'A';
  else if (score >= 80) return 'B';
  else return 'C';
}
```

Explore:

* Named vs anonymous functions
* Parameter defaults & return values
* Arrow functions: `(x, y) => x + y`
* Higher-order functions: passing functions as arguments

### 3.4 DOM & Event Handling Deep Dive

Learn how to:

* Select elements using `querySelector` / `getElementById`
* Attach `click`, `input`, `submit`, `keydown` handlers
* Dynamically update DOM (`.innerText`, `.appendChild`, `.classList`)
* Prevent default form behaviors

Use **javascript.info** for well-structured explanations and examples ([scribd.com][1], [codecademy.com][4], [javascript.info][5])


## 4. Guided Challenges & Mini Projects

| Task                           | Description                                                                              |
| ------------------------------ | ---------------------------------------------------------------------------------------- |
| **FizzBuzz Extended**          | Loop 1–100 and replace numbers with “Fizz”, “Buzz”, or “FizzBuzz”                        |
| **Grade Calculator**           | Loop through an array of student scores and assign grades                                |
| **Counter App**                | Add +1/-1 buttons that update a displayed counter                                        |
| **Tip Calculator Enhancement** | Build on yesterday’s project: include reset button, input validation, and error messages |

Each challenge encourages using loops, functions, and DOM alongside events.


## 5. Group Activity: Dynamic List App

**Objective**: Build an interactive to-do or shopping list with:

* Text input field
* "Add" button
* List items that can be removed via button click
* Modular structure: `addItem()`, `removeItem()`, `renderList()`

This uses:

* Loops to rebuild lists
* Functions for each behavior
* Event listeners on inputs and buttons

Pseudocode outline:

```js
let items = [];

function renderList() {
  list.innerHTML = '';
  items.forEach((text, idx) => {
    const li = document.createElement('li');
    li.innerText = text;
    const btn = createDeleteButton(idx);
    li.append(btn);
    list.append(li);
  });
}

function addItem(text) {
  items.push(text);
  renderList();
}

function deleteItem(idx) {
  items.splice(idx, 1);
  renderList();
}

addBtn.addEventListener('click', () => {
  const text = input.value.trim();
  if (text) {
    addItem(text);
    input.value = '';
  }
});
```


## 6. Recommended Resources

* **W3Resource**: 60+ exercises on loops and logic ([gurukultti.org][2], [w3resource.com][3])
* **javascript.info**: Deep-dive tutorials on functions and DOM ([javascript.info][5])
* **Codecademy JavaScript Path**: Interactive lessons on functions and events&#x20;


## 7. Summary & Homework

* **Today**: Built advanced flow with loops and functions, and created interactive UI with DOM & events
* **Homework**:

  1. Finalize the dynamic list or tip calculator enhancements
  2. Add input validation and at least one extra feature (e.g., `Edit`, `Clear all`)
  3. Push to GitHub and prep a 3-minute demo of your application

</br>

✨ Pro Tips:

* Use functions to keep code organized and DRY
* Use loops to dynamically handle arrays or DOM elements
* Always validate user input before processing

You're mastering the fundamentals of logic & interaction. Tomorrow (Day 5), you'll level up with your capstone project!

[1]: https://www.scribd.com/document/504581227/JS-Crash-Course "7 Day Free Javascript Crash Course: 7 Classes - 14 Hours | PDF"
[2]: https://www.gurukultti.org/admin/notice/javascript.pdf "[PDF] JavaScript from Beginner to Professional"
[3]: https://www.w3resource.com/javascript-exercises/javascript-conditional-statements-and-loops-exercises.php "JavaScript conditional statements and loops - Exercises, Practice ..."
[4]: https://www.codecademy.com/catalog/language/javascript "JavaScript Courses & Tutorials - Codecademy"
[5]: https://javascript.info/ "The Modern JavaScript Tutorial"
