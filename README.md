# 🚀 ABTalks — 60-Day Coding Challenge

> **Build every day. Ship every day. Grow every day.**

ABTalks is a **60-Day Coding Challenge platform designed for Indian college students** to build consistency, create real projects, maintain a public learning streak, and become more visible to recruiters.

Students complete a coding challenge every day, publish their work on GitHub, share their progress on LinkedIn, and build a verifiable record of their development journey.

---

## 🎯 Problem

Many students start learning to code but struggle with consistency.

They watch tutorials, complete courses, and solve occasional problems — but often don't build enough real projects or maintain a public record of their progress.

**ABTalks turns learning into a daily commitment.**

Instead of asking:

> "What should I learn today?"

ABTalks gives students a clear challenge to complete every day for **60 days**.

---

## 💡 Solution

ABTalks combines:

* 🧑‍💻 Daily coding challenges
* 🔥 Learning streaks
* 📈 Progress tracking
* ⭐ XP and levels
* 🏆 Achievements
* 💻 GitHub proof of work
* 🔗 LinkedIn proof of work
* 📊 Learning analytics
* 🎯 Progressive difficulty
* ⏱️ Submission countdown
* 📱 Mobile-first experience

The goal is simple:

**Build → Submit → Share → Learn → Repeat**

---

# ✨ Key Features

## 🏠 Landing Page

The landing page introduces ABTalks to new students and explains the challenge clearly.

Features include:

* Premium SaaS-style hero section
* Clear challenge value proposition
* Strong call-to-action
* How ABTalks works
* Challenge benefits
* Statistics
* Testimonials
* FAQ
* Responsive mobile experience
* Smooth scrolling and animations

---

## 📊 Student Dashboard

The dashboard acts as the student's daily command center.

### Includes:

* 🔥 Current streak
* 📅 Current challenge day
* 🎯 Today's task
* 📈 Overall progress
* ⭐ XP and level
* 🏆 Achievements
* 📊 Weekly activity
* 📈 Analytics
* 🥇 Leaderboard
* 🎯 Next milestone
* 💡 Personalized motivation
* 📝 Recent submissions
* ⏳ Next submission countdown

---

## 📅 Daily Challenge System

ABTalks contains a complete **60-day coding journey**.

Each day has its own challenge with:

* Challenge title
* Day number
* Difficulty
* Estimated completion time
* Learning objective
* Detailed instructions
* Acceptance criteria
* Helpful resources
* XP reward
* Badge reward

### Progressive Learning Path

| Days  | Focus                               |
| ----- | ----------------------------------- |
| 1–10  | HTML, CSS & JavaScript Fundamentals |
| 11–20 | DOM, APIs & Forms                   |
| 21–30 | Intermediate JavaScript             |
| 31–40 | Algorithms & Mini Projects          |
| 41–50 | Advanced JavaScript & Performance   |
| 51–60 | Portfolio-Level Projects            |

The difficulty gradually increases so students progress from fundamentals to larger projects.

---

# 🔗 Proof of Work

ABTalks is built around **public proof of learning**.

For each challenge, students can submit:

* GitHub Repository URL
* GitHub Commit URL
* LinkedIn Post URL
* Live Demo URL
* Screenshot
* Learning notes/reflection

This turns daily learning into a public portfolio.

---

# 🔥 Streak System

Consistency is the heart of ABTalks.

Students can track:

* Current streak
* Longest streak
* Completed days
* Remaining days
* Weekly activity
* Completion percentage

Completing challenges continuously helps students maintain their learning streak.

---

# ⭐ XP & Level System

Students earn XP by completing challenges.

XP contributes to:

* Level progression
* Achievements
* Milestones
* Progress tracking

The dashboard visualizes the student's development over the 60-day journey.

---

# 🏆 Achievement System

Students can earn badges for milestones such as:

* 🎯 First Challenge
* 🔥 7-Day Streak
* 🚀 10 Projects
* ⭐ Consistency
* 🏅 Progress Milestones
* 🏆 Challenge Completion

Achievements provide additional motivation throughout the challenge.

---

# ⏳ 24-Hour Submission Countdown

After submitting a daily challenge, ABTalks can display a countdown until the next challenge becomes available.

The countdown is visible within the experience so students always know:

> **When can I submit my next challenge?**

This creates a clear daily rhythm and gives students a natural break between challenges.

---

# 💾 Local Progress Persistence

Because the hackathon prototype does not require a production backend, the project uses **Local Storage** for client-side persistence.

The application can persist information such as:

* Student profile
* Completed challenges
* Current streak
* XP
* Badges
* Submission history
* Theme preference
* Last visited page
* Challenge progress

Refreshing the page does not unnecessarily reset the student's progress.

---

# 📱 Mobile-First Design

ABTalks was designed specifically with mobile users in mind.

The primary target viewport is:

**390px**

The interface also supports:

* 📱 Mobile
* 📲 Tablet
* 💻 Laptop
* 🖥️ Desktop

### Mobile UX considerations

* Thumb-friendly navigation
* Large touch targets
* Bottom navigation
* Sticky actions
* Responsive cards
* Responsive typography
* No horizontal overflow
* Optimized spacing
* Fast interactions

---

# 🎨 Design Philosophy

ABTalks aims to feel like a **real SaaS product rather than a typical student project**.

The visual direction takes inspiration from modern products such as:

* GitHub
* Linear
* Notion
* Duolingo
* Stripe

while maintaining a unique ABTalks identity.

### Design principles

* Premium spacing
* Strong visual hierarchy
* Rounded components
* Soft shadows
* Smooth gradients
* Carefully controlled glassmorphism
* Clear typography
* Consistent interaction patterns
* Mobile-first layouts

---

# ⚡ Animations & Interactions

The interface includes lightweight interactions such as:

* Page transitions
* Fade-in animations
* Scroll reveal
* Card interactions
* Button animations
* Progress animations
* Counter animations
* Skeleton loading
* Toast notifications
* Success feedback
* Confetti effects
* Modal transitions
* Streak animations

Animations are designed to improve feedback without unnecessarily slowing down the experience.

---

# ♿ Accessibility

Accessibility considerations include:

* Semantic HTML
* Keyboard navigation
* Visible focus states
* ARIA labels
* Color contrast
* Touch-friendly controls
* Screen-reader-friendly structure

---

# 🧪 Edge Cases

The application considers common student scenarios including:

* New student with a 0-day streak
* Lost streak
* Empty profile
* Empty achievements
* No submissions
* Invalid GitHub URL
* Invalid LinkedIn URL
* Submission success
* Submission failure
* Duplicate submission
* Locked challenge
* Completed challenge
* Challenge completion state

---

# 🛠️ Technology Stack

The project intentionally uses a lightweight frontend stack.

### Frontend

* HTML5
* CSS3
* Vanilla JavaScript

### Browser APIs / Frontend Technologies

* Local Storage
* HTML Canvas where applicable
* CSS Animations
* Responsive CSS
* Client-side validation

### No Backend Required

The hackathon prototype does **not** require:

* React
* Vue
* Angular
* Bootstrap
* Tailwind CSS
* jQuery
* Backend
* Authentication
* Production database

Mock data is used where appropriate.

---

# 🗺️ Route Map

The required routes for the hackathon submission are:

```text
/
/dashboard
/day/12
```

---

# 🚀 Getting Started

## 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

## 2. Open the project

```bash
cd ABTalks
```

## 3. Run the project

Because this is a frontend-only application, it can be opened using a local development server.

For example, using VS Code:

```text
Right Click → Open with Live Server
```

Or use any static HTTP server.

---

# 🌐 Live Demo

**Live Demo:**
`YOUR_LIVE_DEMO_URL`

> Replace the placeholder above with your deployed application URL before submission.

---

# 📸 Project Preview

Add screenshots/GIFs of the following screens to this section:

### Landing Page

```text
Add landing-page screenshot here
```

### Student Dashboard

```text
Add dashboard screenshot here
```

### Challenge Day

```text
Add challenge-day screenshot here
```

### Mobile View

```text
Add 390px mobile screenshot here
```

---

# 🤖 AI Usage

AI was used throughout the development process as a **design and development assistant**.

AI assistance included:

* Product planning
* UI/UX ideation
* Frontend development guidance
* Challenge-system planning
* Responsive design
* Accessibility
* Animation ideas
* Debugging
* Code-quality suggestions
* Feature ideation
* Final UI refinement

The development was iterative rather than generated from a single prompt.

The complete AI prompt history and usage details are available in:

**`AI_USAGE_LOG.md`**

---

# 🧑‍💻 Development Approach

The project followed an iterative workflow:

```text
Requirements
     ↓
AI-assisted planning
     ↓
Initial implementation
     ↓
Testing
     ↓
Feature improvements
     ↓
Bug fixing
     ↓
Responsive optimization
     ↓
UI/UX refinement
     ↓
Final testing
     ↓
Hackathon submission
```

AI suggestions were reviewed and adapted to the existing codebase rather than blindly accepted.

---

# 🎯 Hackathon Focus

ABTalks was designed specifically around the challenge requirements:

### Landing Page

Help a student understand ABTalks and feel motivated to join the 60-day challenge.

### Student Dashboard

Give students a clear overview of:

* Streak
* Today's task
* Progress
* Completion
* Achievements
* Standing

### Challenge Day

Provide a complete daily workflow:

```text
Understand the task
        ↓
Build the project
        ↓
Push to GitHub
        ↓
Post on LinkedIn
        ↓
Submit proof
        ↓
Earn XP
        ↓
Continue the streak
```

---

# 💡 Core Product Idea

ABTalks is not simply a coding-task website.

It is designed around a simple principle:

> **Consistency creates proof. Proof creates visibility. Visibility creates opportunity.**

By completing one project every day for 60 days, students gradually build:

* Coding consistency
* GitHub activity
* LinkedIn presence
* Project experience
* A public learning history
* A stronger portfolio

---

# 🔮 Future Improvements

Potential future versions could include:

* GitHub OAuth
* Automatic commit verification
* LinkedIn verification
* Real-time leaderboards
* Certificate generation
* QR certificate verification
* Public developer profiles
* Portfolio generation
* Advanced analytics
* Team challenges
* AI-powered code review

These are intentionally separated from the current hackathon prototype where they are outside the required scope.

---

# 📄 AI Usage & Transparency

For hackathon authenticity and transparency, the repository includes:

```text
AI_USAGE_LOG.md
```

This document records the AI-assisted prompts and development areas used during the project.

---


# ⭐ Acknowledgement

Built as a national-level hackathon submission focused on helping college students build consistent coding habits and publicly document their development journey.

---

## 🚀 Build Every Day. Ship Every Day. Grow Every Day.

**ABTalks — 60 Days. 60 Builds. One Better Developer.**
