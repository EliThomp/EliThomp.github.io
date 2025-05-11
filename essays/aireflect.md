---
layout: essay
type: essay
title: "Learning with AI: Debugging the Developer Brain"
date: 2025-05-10
published: true
labels:
  - Software Engineering
  - Reflection
  - Artificial Intelligence
---

## Learning with AI: Debugging the Developer Brain

Imagine sitting at your laptop, React components half-built, a stubborn ESLint error flashing in red, and you're not even sure why your form reloads the whole page. You Google, dig through docs, scroll through StackOverflow, and just as you're about to give up—you ask ChatGPT.

And just like that, a clear, human-readable explanation appears.

That moment of clarity? That’s what using AI in ICS 314 felt like. It wasn’t about taking shortcuts. It was about unblocking your brain and getting back into the flow. Throughout the course, AI tools—especially ChatGPT—acted like a second brain. They helped me troubleshoot React quirks, decode Bootstrap spacing classes, and set up PostgreSQL when the instructions didn’t quite match my setup.

But AI wasn’t perfect. It hallucinated syntax sometimes or misunderstood context. Still, when used thoughtfully, it was like having a tutor who never sleeps—ready to explain, correct, and suggest 24/7.

---

## Experience WODs

In one Experience WOD focused on layout using Bootstrap, I hit a roadblock trying to get items centered on the page. I wasn’t sure how spacing classes like mx-auto or px-3 actually worked. So I asked:
“What does mx-auto and px-3 do in Bootstrap?”
The AI’s breakdown helped me understand that mx-auto centers elements horizontally, and px-3 applies horizontal padding. While this didn’t directly solve the WOD, it helped me visualize what each class was doing and gave me the confidence to tweak layout utilities until I reached the correct structure.

## In-class Practice WODs

I avoided using AI during live practice WODs to stay in the mindset of a real coding interview or timed challenge. However, afterward, I used ChatGPT to reinforce areas I struggled with. For example, after a grid layout challenge, I asked:
“How do Bootstrap’s column breakpoints work for responsive layouts?”
The response clarified how classes like col-sm-12 and col-md-6 adapt to different screen sizes, which helped solidify the way Bootstrap’s grid system works.

---

## In-class WODs

In one of the React WODs, I encountered an issue where submitting a form caused the page to reload, wiping out the input values. Afterward, I asked:
“How do I prevent a page from refreshing when I submit a form in React?”
ChatGPT pointed out the need for event.preventDefault() in the onSubmit handler. That small line fixed the problem and helped me better understand how React handles form behavior differently from plain HTML.

---

## Essays

When working on my software engineering ethics essay, I wanted to improve readability and flow. I asked:
“Can you simplify this paragraph and make it more clear?”
ChatGPT didn’t generate my ideas, but it did help me polish sentence structure and transitions. It was like having a second pair of eyes—useful for editing without changing the core message.



---

## Final Project

During our final project, I experimented with Tailwind CSS before sticking with Bootstrap. I asked:
“How do I center a div inside another using Tailwind CSS?”
That response helped me better understand flexbox-based layout systems. For our backend, I asked:
“How do I write a Prisma query that includes a related table?”
We needed to pull in menu items alongside vendor information. The AI showed me how to use include, and I adapted the code for our database schema. This saved time and made our dashboard logic more efficient.

---

## Learning a Concept / Tutorial

React’s concepts of props and state were tricky at first. I asked:
“What’s the difference between props and state in React with examples?”
The AI explained it in beginner-friendly language and provided a simple component example. That gave me the foundational understanding I needed to build dynamic components without confusion.

---

## Answering a Question in Class or in Discord

Before answering a question in the class Discord about rendering lists in React, I double-checked my understanding by asking:
“Why are keys important in React list rendering?”
ChatGPT explained how keys help React track changes in arrays efficiently. This reinforced what I’d learned in class and helped me give a more confident, accurate answer.
---

## Asking or Answering a Smart-Question

I wanted to help a classmate understand destructuring but struggled to explain it simply. So I asked:
“Explain destructuring in JavaScript like I’m five.”
The AI gave a metaphor using food ingredients, which I rephrased and used in a peer study session. This made the concept more accessible and fun to explain.

---

## Coding Example

While building an interactive UI, I needed a toggle component. I asked:
“Write a React component that toggles text visibility with a button.”
The response gave me a simple example using useState, which I then customized for our specific UI. It sped up my prototyping and gave me a reusable structure.

---

## Explaining Code

A teammate was stuck on a useEffect bug. I copied the code into ChatGPT and asked:
“Explain what this React code is doing step-by-step.”
The AI broke it down line by line, helping us understand the dependency array and cleanup function. It turned what felt like a vague bug into something concrete and solvable.

---

## Writing Code

For repetitive components like forms, I asked:
“Write a form in React with controlled inputs for name and email.”
ChatGPT returned a clean base with state hooks and handlers. I edited it to match our design, which saved me time and reduced the chance of wiring errors.

---

## Documenting Code

To make our codebase easier to read for teammates, I asked:
“How do I write a good JSDoc comment for a React function?”
The AI gave me a solid template including parameter descriptions and return values. I adapted this for our functions, making our documentation more consistent and readable.

---

## Quality Assurance

When I got an ESLint error saying:
“‘React’ must be in scope when using JSX,”
I asked ChatGPT why. It explained that older versions of React required the import even if JSX was used alone, while newer setups (like ours) could use JSX without it thanks to updated Babel config. I resolved the issue and learned something new about how JSX is compiled.

---

## Final Thoughts

AI wasn’t a crutch—it was a learning accelerator. It helped me debug smarter, write cleaner, and understand deeper. Whether I was cleaning up code, fixing layout issues, or explaining concepts to others, AI gave me the confidence and clarity to move forward.

More than anything, it reminded me that asking the right questions is just as important as finding the right answers. When I used AI thoughtfully, I didn’t just write better code—I became a better problem-solver.

---
