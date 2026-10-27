
# Interactive Quiz Website

## This Project is implementation of following topics:

* Single Page Application
* DOM Manipulation
* Event Listeners (click)
* JavaScript State Management
* Array Methods (forEach, Array.from())
* Async JavaScript (setTimeout)
* CSS Flexbox & Responsive Layouts (@media queries)
* HTML5 Custom Data Attributes (data-*)

---

## Topics Covered & What I Learned

### 1. Core Web Development Topics
* Dynamic DOM Manipulation: Capturing references, modifying string elements, and dynamically generating button child nodes.
* JavaScript State Management: Tracking variable pointers through interactive loops.
* Array-to-Collection Conversions: Forcing strict object translations to unblock robust loop iterators.

### 2. Practical Engineering Learnings
* State Locking (Input Guards): How to utilize conditional flags to discard rapid clicks during processing intervals.
* Class-Based Interface Toggling: Switching parent window visibility matrices using clean utilities.
* Visual Layer Debugging: Resolving overlapping declaration errors that hid layout entities (such as recovering an invisible progress bar container).

---

## Getting Started

### 📂 File Structure
Single Page Application (SPA). 

* **`index.html`** — The skeletal UI mapping all interactive quiz views, text frames, containers, and action hooks.
* **`style.css`** — Manages visual reset variables, layout structures, active screen switches, and responsive breakpoints.
* **`script.js`** — Houses runtime variables, algorithmic loops, array-based question banks, and DOM tracking logic.


## Requirements
* A modern web browser: Chrome, Firefox.
* Code editor: Visaul Studio Code
* Basic understanding of HTML5, CSS3, and JavaScript (ES6+).

---

## DOM Elements Reference

Select any interface entity below to jump directly to its role definition within the codebase architecture:

* 🟦 [startScreen](#startscreen)
* 🟦 [quizScreen](#quizscreen)
* 🟦 [resultScreen](#resultscreen)
* 🟦 [startButton](#startbutton)
* 🟦 [questionText](#questiontext)
* 🟦 [answersContainer](#answerscontainer)
* 🟦 [currentQuestionSpan](#currentquestionspan)
* 🟦 [totalQuestionsSpan](#totalquestionspan)
* 🟦 [scoreSpan](#scorespan)
* 🟦 [finalScoreSpan](#finalscorespan)
* 🟦 [maxScoreSpan](#maxscorespan)
* 🟦 [resultMessage](#resultmessage)
* 🟦 [restartButton](#restartbutton)
* 🟦 [progressBar](#progressbar)

---

### DOM Element Definitions

#### startScreen
```javascript
const startScreen = document.getElementById("start-screen");
```
* **Role:** The application's entry panel wrapper node. It acts as the isolation bucket holding initial descriptive headers and call-to-actions before entering the running loop.

#### quizScreen
```javascript
const quizScreen = document.getElementById("quiz-screen");
```
* **Role:** The primary interactive parent panel tracking current question state arrays, answer configurations, and live-updating session headers.

#### resultScreen
```javascript
const resultScreen = document.getElementById("result-screen");
```
* **Role:** The end-state interface component. Configured to display aggregate point tallies and feedback strings evaluated upon session resolution.

#### startButton
```javascript
const startButton = document.getElementById("start-btn");
```
* **Role:** Intercepts click triggers to launch the quiz loop and initial state setups.

#### questionText
```javascript
const questionText = document.getElementById("question-text");
```
* **Role:** The targeted text block container where active question strings are dynamically injected.

#### answersContainer
```javascript
const answersContainer = document.getElementById("answers-container");
```
* **Role:** The empty shell node where multiple-choice response buttons are programmatically constructed and cleared.

#### currentQuestionSpan
```javascript
const currentQuestionSpan = document.getElementById("current-question");
```
* **Role:** A minor text span tracker displaying the base-1 index value of the active question context.

#### totalQuestionsSpan
```javascript
const totalQuestionsSpan = document.getElementById("total-questions");
```
* **Role:** Static target rendering the total bounds length of the underlying questions collection.

#### scoreSpan
```javascript
const scoreSpan = document.getElementById("score");
```
* **Role:** Displays the live incremental player point variables during ongoing question sequences.

#### finalScoreSpan
```javascript
const finalScoreSpan = document.getElementById("final-score");
```
* **Role:** Injects the completed running score aggregate into the results presentation layer.

#### maxScoreSpan
```javascript
const maxScoreSpan = document.getElementById("max-score");
```
* **Role:** Standard placeholder node capturing the perfect potential total score benchmark for user tracking.

#### resultMessage
```javascript
const resultMessage = document.getElementById("result-message");
```
* **Role:** Evaluates user grade matrices to print tailored final validation feedback lines.

#### restartButton
```javascript
const restartButton = document.getElementById("restart-btn");
```
* **Role:** Flushes remaining runtime values and screen active properties to reset user status markers back to the launch conditions.

#### progressBar
```javascript
const progressBar = document.getElementById("progress");
```
* **Role:** Timeline calculation node. Its inline width pixel layout percentage updates in real-time as individual question offsets advance.

---

