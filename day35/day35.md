# 🧩 Prompt Puzzle — Master AI Prompting Through Play

## Overview

**Prompt Puzzle** is an offline, single-file interactive learning game designed to help beginners practice writing better AI prompts for **Software Development and Coding**.

The application turns prompt engineering into a game through three challenge types:

1. **Build the Prompt**
2. **Clean the Prompt**
3. **Choose the Best Prompt**

Players solve randomized coding-related scenarios and receive a performance report at the end.

---

## 🎯 Learning Goal

The application teaches beginners how to transform vague coding requests into clear, useful AI prompts.

Players practice identifying the key components of an effective prompt:

* Context
* Role
* Exact task
* Constraints
* Expected output
* Audience
* Examples

The central principle is:

> **Precision beats unnecessary complexity.**

---

## 💻 Domain

**Software / Coding**

Example topics include:

* JavaScript debugging
* REST APIs
* React components
* SQL explanations
* Python functions
* Git errors
* CSS layouts

---

## 🟢 Difficulty

**Beginner**

The challenges are designed for users who are learning programming or are new to AI prompting.

---

## 🎮 Challenge Types

### 1. Build the Prompt

Players receive multiple prompt blocks.

Some blocks are useful while others are distractors.

The goal is to drag the correct blocks into the prompt area.

The player learns to recognize:

* Useful context
* Clear tasks
* Appropriate constraints
* Desired output
* Unnecessary complexity

---

### 2. Clean the Prompt

Players receive a weak prompt such as:

```text
Fix this code.
```

They must rewrite it into a more useful prompt containing relevant information.

For example:

```text
Act as a beginner-friendly JavaScript mentor.
Identify why the filter callback throws “price is not defined”.
Provide the corrected code and explain the fix in simple terms.
```

The game evaluates the optimized prompt based on useful signals such as:

* Technology
* Task
* Specific requirements
* Expected output

---

### 3. Choose the Best Prompt

Players receive multiple possible prompts and select the one most likely to generate a useful AI response.

The best prompt normally has:

* Enough context
* A clearly defined task
* Useful constraints
* A clear output requirement
* No unnecessary over-engineering

---

## 🧩 Scenario System

Scenarios are stored as reusable JavaScript objects.

Each scenario can contain:

* Scenario ID
* Title
* Challenge type
* Desired output
* Correct prompt blocks
* Distractor blocks
* Weak prompt
* Optimized prompt
* Over-engineered prompt
* Weak AI output
* Optimized AI output
* Prompt principle

This makes it easy to add additional coding scenarios later.

---

## 📊 Scoring System

The game provides live scoring using multiple performance factors.

### Accuracy

Measures how correctly the player solves the challenge.

### Time

Rewards users who solve challenges efficiently.

### Moves

Tracks interactions such as moving prompt blocks.

### Wrong Placements

Tracks incorrect or distractor blocks selected during prompt construction.

### Hints Used

Tracks how many hints the player uses.

### Optimization Bonus

Rewards the player for creating or selecting high-quality prompts.

---

## 🏆 Performance Report

After completing all challenges, the application generates a personalized report.

The report contains:

### Prompt Score

Overall game score.

### Rating

Possible ratings include:

* S+
* A
* B
* C

### Rank

Possible ranks include:

* 🧠 Prompt Architect
* ⚡ Prompt Engineer
* 🧩 Prompt Builder
* 🌱 Prompt Explorer

### Prompt DNA

A visual representation of the player's:

* Accuracy
* Time efficiency
* Precision
* Independence
* Optimization ability

### Personalized Feedback

The application analyzes performance and provides learning recommendations.

### Next Milestone

The player receives a specific improvement target for the next round.

### Final Optimized Prompt

The application displays a strong prompt based on the player's completed challenges.

---

## 🔄 Replay System

Players can select:

**Replay With New Scenarios**

The application randomizes the scenario order and starts a new game.

This allows repeated practice without manually refreshing or editing the application.

---

## 💡 Hint System

Every challenge includes a hint button.

Hints provide guidance without directly giving the answer.

For example:

> Keep the blocks that define the role, exact task and requested output. Ignore unnecessary complexity.

Hints are tracked and affect the final Prompt DNA.

---

## 🎨 User Interface

The application uses a premium modern interface featuring:

* Dark theme
* Gradient backgrounds
* Glass-style panels
* Rounded cards
* Responsive layout
* Hover effects
* Drag-and-drop interactions
* Animated progress bars
* Score animations
* Floating notifications
* Challenge timers
* Micro-interactions
* Responsive mobile layout

---

## 📴 Offline Support

The application is designed to work completely offline.

There are:

* No backend servers
* No database
* No API calls
* No authentication
* No external data dependencies

Everything is contained inside a single HTML file.

The user can simply open the HTML file in a browser.

---

## 🛠️ Technology Stack

### Frontend

* HTML5
* CSS3
* Vanilla JavaScript

### Architecture

Single-file application.

```text
prompt-puzzle.html
```

All HTML, CSS and JavaScript are contained in the same file.

---

## 📁 Recommended Project Structure

```text
prompt-puzzle/
│
├── prompt-puzzle.html
│
└── README.md
```

The application itself requires only:

```text
prompt-puzzle.html
```

---

## ▶️ How to Run

### Method 1 — Directly Open

Double-click:

```text
prompt-puzzle.html
```

The application will open in the default browser.

### Method 2 — Browser

Right-click the file and select:

```text
Open with → Google Chrome
```

No installation is required.

---

## 🧪 How to Play

### Step 1

Open the HTML file.

### Step 2

Read the desired output.

### Step 3

Complete the challenge.

For **Build the Prompt**, drag useful blocks into the prompt area.

For **Clean the Prompt**, rewrite the weak prompt.

For **Choose the Best Prompt**, select the strongest prompt.

### Step 4

Click:

```text
Check Prompt
```

or:

```text
Optimize Prompt
```

or:

```text
Lock Choice
```

### Step 5

Review your feedback.

### Step 6

Continue to the next puzzle.

### Step 7

Review the final Prompt Performance Report.

---

## 🧠 Prompt Engineering Principles Taught

The game reinforces several fundamental prompting principles.

### 1. Be Specific

Instead of:

```text
Fix this.
```

Use:

```text
Identify why the JavaScript filter callback throws an error and provide the corrected code.
```

### 2. Provide Context

Mention the relevant technology.

Example:

```text
Using Node.js and Express...
```

### 3. Define the Task

Clearly state what the AI should do.

Example:

```text
Create a POST /students endpoint.
```

### 4. Define the Expected Output

Tell the AI what it should return.

Example:

```text
Provide the route code and a sample request.
```

### 5. Identify the Audience

Example:

```text
Explain this as a beginner-friendly JavaScript mentor.
```

### 6. Avoid Unnecessary Complexity

A longer prompt is not automatically a better prompt.

The objective is:

```text
Maximum clarity
+
Minimum unnecessary complexity
```

---

## 🚀 Possible Future Improvements

The project can be expanded with:

* More programming languages
* Intermediate difficulty
* Advanced difficulty
* Expert challenges
* Java challenges
* React challenges
* Node.js challenges
* MongoDB challenges
* AWS challenges
* Git/GitHub challenges
* SQL challenges
* TypeScript challenges
* Prompt history
* High-score persistence
* LocalStorage
* Achievement badges
* Daily challenges
* Leaderboards
* More advanced Prompt DNA
* Accessibility improvements
* Sound effects
* Keyboard-only drag-and-drop support

---

## 🏅 Educational Value

Prompt Puzzle combines:

**Prompt Engineering + Programming + Gamification**

Instead of simply explaining prompting theory, it gives learners repeated opportunities to practice making decisions about prompt quality.

The learner gradually develops the ability to ask:

> What does the AI need to know to produce the result I actually want?

That question is the foundation of effective AI-assisted software development.

---

## 📜 License

This project can be freely modified and extended for educational and personal learning purposes.
