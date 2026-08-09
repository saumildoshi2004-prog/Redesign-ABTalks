Role

You are an expert UI/UX Designer, Frontend Developer, and ProductDesigner.

Your task is to redesign the ABTalks platform for a national-levelhackathon using only HTML, CSS, and Vanilla JavaScript.

The final result should look like a premium SaaS product, not astudent project.

Project Overview

ABTalks is a platform where Indian college students complete a 60-daycoding challenge.

Each day students:

Complete a coding task

Push code to GitHub

Share progress on LinkedIn

Submit both links

Maintain their learning streak

Most users access the platform late at night on mobile devices, sothe product must be mobile-first.

Primary Goal

Design a beautiful, engaging, and professional experience that motivatesstudents to:

Stay consistent

Complete all 60 days

Build a portfolio

Become visible to recruiters

The experience should feel inspired by products like Duolingo, GitHub,Notion, Linear, and Stripe, while maintaining a unique identity.

Technology Stack

Use only:

HTML5

CSS3

Vanilla JavaScript

Do NOT use:

React

Vue

Angular

Bootstrap

Tailwind CSS

jQuery

Backend

Authentication

Database

Use realistic mock JSON data only.

Suggested Folder Structure

/
├── index.html
├── dashboard.html
├── day12.html
├── css/
│   ├── style.css
│   ├── dashboard.css
│   ├── day.css
│   └── responsive.css
├── js/
│   ├── app.js
│   ├── dashboard.js
│   ├── day.js
│   ├── data.js
│   └── animation.js
├── assets/
│   ├── images/
│   ├── icons/
│   └── illustrations/
└── data/
    └── mockData.json

Required Pages

1. Landing Page

Include:

Hero section

Strong headline

CTA buttons

How ABTalks works

Benefits

Statistics

Testimonials

FAQ

Footer

2. Dashboard

Include:

Welcome section

Student profile

Current streak

XP & Level

Today's task

Progress bar

Challenge completion

Weekly activity

Achievements

Analytics

Leaderboard

Motivation card

Continue Challenge button

3. Challenge Day

Include:

Day number

Challenge title

Difficulty

Estimated time

Objectives

Instructions

Resources

Acceptance criteria

GitHub Repository URL input

GitHub Commit URL input

LinkedIn Post URL input

Notes

Submit button

XP reward

Badge reward

Previous / Next navigation

Mobile First

Design for 390px width first.

Requirements:

Thumb-friendly navigation

Large touch targets

Bottom navigation

Sticky action buttons

Fast loading

Fully responsive

Design System

Suggested palette:

Primary: #6366F1

Secondary: #8B5CF6

Accent: #06B6D4

Success: #22C55E

Warning: #F59E0B

Danger: #EF4444

Background: #0F172A

Surface: #111827

Cards: #1E293B

Text: #F8FAFC

Muted: #94A3B8

Typography:

Inter

Poppins

Manrope

Design principles:

Premium spacing

Glassmorphism where appropriate

Rounded corners

Soft shadows

Smooth gradients

Excellent visual hierarchy

Animations

Implement using CSS and JavaScript:

Fade-in

Scroll reveal

Card hover

Button animations

Counter animation

Progress animation

Loading skeleton

Confetti on successful submission

Animated streak flame

Smooth page transitions

Mock Data

Create realistic data for:

Student profile

Daily tasks

Leaderboard

XP

Badges

Analytics

GitHub submissions

LinkedIn submissions

Edge Cases

Handle:

New student (0-day streak)

Lost streak

Empty profile

Empty achievements

No submissions

Invalid GitHub URL

Invalid LinkedIn URL

Submission success

Submission failure

Challenge completed

Extra Features

Include at least one thoughtful improvement, such as:

Daily motivation

XP system

Level progression

GitHub-style heatmap

Focus timer

Weekly goals

Productivity score

Coding consistency graph

Skill tree

Career readiness meter

Daily reflection

Code Quality

Write:

Semantic HTML

Clean CSS

Modular JavaScript

Reusable functions

Responsive layouts

Meaningful comments

Organized folder structure

Avoid duplicated code.

Final Goal

Deliver a polished, production-quality, mobile-first frontend that isvisually impressive, responsive, accessible, and demonstratesoutstanding UI, UX, and frontend engineering.

The project should be hackathon-ready and stand out through its design,usability, and attention to detail.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

make all thing proper working like all day different different challenges and make all proper smooth and responsive

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#

This project has already been built. **Do not recreate it from scratch.** Instead, analyze the entire existing codebase, understand every component, and enhance it while preserving the current design language and project structure.

Your goal is to transform the current implementation into a **hackathon-winning, production-quality frontend**.

---

# Enhancement Rules

* Do **NOT** remove existing functionality unless it is broken.
* Keep the existing folder structure.
* Improve code quality while maintaining compatibility.
* Preserve the current design style and make it more polished.
* Ensure every feature works correctly.
* Optimize performance and responsiveness.
* Avoid duplicate code.
* Refactor repetitive logic into reusable JavaScript functions.

---

# Complete Challenge System

The current project represents a **60-Day Coding Challenge**, so implement it completely.

## Every day must have its own challenge.

Create realistic programming challenges for **Day 1 through Day 60**.

Each day should include:

* Unique challenge title
* Difficulty level
* Estimated completion time
* Learning objective
* Detailed task description
* Acceptance criteria
* Helpful resources
* XP reward
* Badge reward (where applicable)

The challenges should gradually increase in difficulty.

Example progression:

* Days 1–10 → HTML, CSS, JavaScript Basics
* Days 11–20 → DOM, APIs, Forms
* Days 21–30 → Intermediate JavaScript
* Days 31–40 → Algorithms & Mini Projects
* Days 41–50 → Advanced JavaScript & Performance
* Days 51–60 → Portfolio-Level Projects

Each day must feel unique.

---

# Navigation

The user should be able to:

* Move to previous day
* Move to next day
* Jump to any unlocked day
* See completed days
* See locked days
* Continue from the last completed challenge

Prevent access to future locked days.

---

# Submission Workflow

Implement a realistic submission flow.

Student submits:

* GitHub Repository URL
* GitHub Commit URL
* LinkedIn Post URL

Validate:

* Empty fields
* Invalid URLs
* Duplicate submissions

Show:

* Loading animation
* Success message
* XP earned
* Badge earned
* Updated streak
* Updated progress

Save progress using Local Storage.

---

# Progress System

Implement a complete progress system.

Track:

* Current day
* Completed days
* XP
* Current level
* Total badges
* GitHub submissions
* LinkedIn submissions
* Completion percentage
* Daily streak
* Longest streak

Everything should update automatically.

---

# Dashboard Improvements

Improve the dashboard with:

* Better analytics
* Weekly progress
* Monthly progress
* Coding consistency
* XP history
* Daily activity graph
* Challenge completion percentage
* Recent submissions
* Next milestone
* Personalized motivation

---

# Landing Page Improvements

Make the landing page feel premium.

Improve:

* Hero section
* CTA buttons
* Scroll animations
* Statistics
* Testimonials
* FAQ
* Footer
* Mobile experience

Include beautiful transitions and smooth scrolling.

---

# UI Improvements

Improve every section.

Add:

* Better spacing
* Better typography
* Better icons
* Better illustrations
* Better gradients
* Better shadows
* Better cards
* Better hover effects
* Better loading states
* Better empty states

The UI should feel comparable to modern SaaS products.

---

# Animations

Every interaction should feel smooth.

Include:

* Page transitions
* Card hover animation
* Button ripple effect
* Floating cards
* Fade-in animations
* Scroll reveal
* Counter animation
* Progress animation
* Skeleton loading
* Success confetti
* Toast notifications
* Smooth modal animations

Animations should remain lightweight and performant.

---

# Responsive Design

Ensure every page works perfectly on:

* 390px Mobile
* Tablets
* Laptop
* Desktop

No overflow.

No broken layouts.

No hidden buttons.

---

# Accessibility

Improve accessibility.

Include:

* Keyboard navigation
* Visible focus states
* ARIA labels
* Semantic HTML
* Sufficient color contrast
* Screen-reader friendly components

---

# Local Storage

Store:

* Student profile
* Completed days
* Current streak
* XP
* Badges
* Theme preference
* Last visited page
* Submission history

Restore all data automatically after refresh.

---

# Performance

Optimize:

* JavaScript execution
* CSS
* Images
* Animations
* DOM updates

Avoid unnecessary re-rendering or expensive operations.

---

# Code Quality

Improve:

* Readability
* Comments
* Naming conventions
* Function organization
* File organization

Follow best frontend development practices.

---

# Bug Fixes

Analyze the complete project and fix:

* Broken buttons
* Navigation issues
* Incorrect calculations
* Responsive bugs
* Validation problems
* Animation glitches
* UI inconsistencies
* Edge-case failures

Ensure every feature functions correctly.

---

# Final Deliverable

The final website should feel like a real startup product rather than a hackathon prototype.

Every screen should be polished.

Every animation should be smooth.

Every challenge should work.

Every button should function.

Every statistic should update correctly.

Every page should be responsive.

Every interaction should provide user feedback.

The complete project should be production-ready, mobile-first, visually impressive, and capable of standing out in a national-level hackathon.

Before finishing, verify that:

* All 60 challenge days are implemented.
* Navigation between days works correctly.
* Dashboard statistics update dynamically.
* Local Storage persists all progress.
* Forms validate correctly.
* Animations perform smoothly.
* No console errors remain.
* The website is fully responsive.
* All existing features continue to work after enhancements.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

add and improve reset button and some smoothness in website make it perfect and professional

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

can you add these things into this website and make it more amazing with these new features :- 1.Certificates

* Auto-generate certificate after Day 60.

* Download as PDF.

* QR code verification.

2. GitHub Integration

* Connect GitHub username.

* Verify daily commits automatically.

* Show contribution graph.

3. LinkedIn Proof

* Upload LinkedIn post link.

* Mark challenge completed only after verification.

4. Daily Submission

* GitHub URL

* Live Demo URL

* Screenshot

* Notes about today's learning

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
