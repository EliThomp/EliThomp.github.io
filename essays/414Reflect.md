---
layout: essay
type: essay
title: "Building Kitchen Coordinator: What I Learned From Developing a Full-Stack App"
date: 2026-05-12
published: true
labels:
  - Software Engineering
  - Reflection
  - Full-Stack Development
---

## Introduction

Honestly, working on the Kitchen Coordinator project taught me way more than I expected about actual software engineering and what it’s like building a real full-stack application. Going into the project, I mostly only had experience with smaller assignments and coding problems, but this project forced me to deal with frontend design, backend logic, databases, validation, debugging, deployment, and UI/UX decisions all at once. The project itself was a pantry and recipe management website where users can store pantry items, create shopping lists, and compare recipes against what they currently have in stock.

## Learning Backend Logic and Data Handling

One of the biggest things I learned was how difficult it is to keep frontend input, backend storage, and database structure all consistent with each other. This became really obvious when I worked on the two-tier common item conversion system. I wanted users to be able to enter realistic kitchen measurements like “1/2 jar” or “1 1/2 cups” while still storing everything in decimals in the backend so calculations would work properly. Building this taught me a lot about parsing, validation, TypeScript types, and why normalization matters in databases. I also learned that something that sounds simple at first can become surprisingly complicated once you start thinking about edge cases and user experience.

## Unit Conversion and UI Design

Another thing I learned a lot about was unit conversion and display formatting. At first I thought conversions would just be basic math, but once recipes, pantry items, fractions, and different units started interacting together, it became a lot more complicated. I had to build systems for converting between units, rounding values properly, and making sure the UI stayed consistent across the pantry and recipe pages. This also taught me how important good UI design is because even small inconsistencies, like mixing fractions and decimals randomly, made the app feel confusing.

## Debugging and Troubleshooting

I also got a lot better at debugging and troubleshooting. Throughout the semester I dealt with Prisma migration issues, database drift, deployment problems on Vercel, API bugs, and random TypeScript errors that sometimes took hours to figure out. At first these problems were honestly frustrating, but over time I got way more comfortable reading logs, tracing bugs, and solving problems step by step instead of panicking when something broke.

## Conclusion

Overall, I think this project gave me a much better understanding of what real software engineering actually looks like. It wasn’t just about writing code anymore. It was about designing systems, handling edge cases, maintaining consistency across the app, and constantly improving the user experience. Even though the project became way bigger and more complicated than I expected, I feel way more confident now working on larger full-stack applications and debugging real-world problems.
