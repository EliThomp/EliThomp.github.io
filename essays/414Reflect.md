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

Honestly, working on the Kitchen Coordinator project taught me way more than I originally expected about software engineering and full-stack development. Before this project, most of my experience came from smaller assignments or isolated coding problems where the goal was usually just to make the code work. This project was completely different because everything was connected together. Instead of only focusing on one file or one feature at a time, I had to think about frontend design, backend logic, databases, APIs, user input validation, deployment, debugging, and overall user experience all at once.

The goal of the project was to create a website where users could manage pantry items, shopping lists, and recipes all in one place. Users could log in, track ingredients they already had, create shopping lists, and compare recipes against their pantry inventory to see what they were missing. Over time, the project evolved far beyond the original idea because we kept adding more realistic features and improving the overall system. Looking back, I think this project gave me one of the best hands-on experiences I’ve had with real software development because it forced me to deal with both technical problems and design decisions at the same time.

## Learning Backend Logic and Data Handling

One of the biggest things I learned during this project was how important it is to keep frontend input, backend logic, and database structure all synchronized with each other. At first, I underestimated how difficult this actually was. I originally thought that once data was entered into a form, saving it to the database would be pretty straightforward. However, once the application became larger and more features started interacting with each other, I realized how easy it was for inconsistencies to appear between the frontend and backend.

A major example of this was the two-tier common item conversion system that I worked on. The idea behind this feature was to let users enter realistic kitchen-style measurements like “1/2 jar,” “1 1/2 cups,” or “1/4 can,” while still storing everything internally as normalized decimal values for calculations and comparisons. At first this sounded relatively simple, but implementing it became much more complicated once I started thinking about validation, database consistency, and edge cases.

To solve this, I had to create reusable parsing and formatting systems that could convert fractions into decimals for storage while also converting decimals back into readable fractions for display. This taught me a lot about data normalization and why backend systems often need to store information differently from how users interact with it on the frontend. I also learned more about TypeScript type safety and validation because I needed to make sure users could not enter invalid values that would break calculations later in the application.

Another thing I learned from this process was how important reusable utilities are in larger projects. Instead of writing separate parsing logic in multiple components, I created centralized helper functions that handled fraction parsing and display formatting across the entire app. This made the project easier to maintain and helped keep the UI consistent.

## Unit Conversion and UI Design

Another major learning experience for me was working on unit conversion and display formatting throughout the pantry and recipe systems. Originally, I thought unit conversion would mostly just involve multiplying values by conversion constants. However, once recipes, pantry items, fractions, and user-generated inputs all started interacting together, the problem became much more complicated.

One challenge was making sure quantities displayed in a way that felt natural to users. For example, displaying “0.5 cups” everywhere technically worked, but showing “1/2 cup” felt much more intuitive in a cooking application. At the same time, I also had to avoid awkward fractions like “13/37” or strange floating-point numbers caused by decimal rounding errors. This forced me to think more about user experience and consistency instead of only focusing on raw functionality.

I also worked on improving how recipes compared against pantry items. Earlier versions of the project only checked whether an ingredient name existed in the pantry, but later I updated the logic to consider quantities and units as well. This meant the system needed to recognize valid conversions such as kilograms to grams or cups to tablespoons while also identifying invalid comparisons between unrelated measurement categories like grams and milliliters. Working on this taught me how quickly small features can become complex once real-world edge cases are introduced.

Another important lesson I learned was that simplifying the UI often improves usability more than adding more information. For example, when redesigning the recipe availability system, I originally considered displaying many different ingredient states and detailed labels. However, I realized that simplifying the system into green, yellow, and red ingredient indicators made the interface much easier to understand, especially on mobile devices. This helped me understand that good frontend design is not only about adding features, but also about reducing unnecessary complexity for users.

## Debugging and Troubleshooting

One of the hardest but most valuable parts of the project was learning how to debug larger systems when multiple parts of the application were interacting together. Throughout the semester I dealt with Prisma migration issues, database drift problems, deployment failures on Vercel, TypeScript build errors, API route issues, and random frontend bugs that sometimes took hours to diagnose.

At first, these problems were honestly frustrating because the errors often looked overwhelming and did not clearly explain what was actually wrong. Sometimes fixing one issue would accidentally create another issue somewhere else in the application. Over time though, I became much more comfortable approaching debugging step by step instead of panicking immediately when something broke.

I learned how important logs, console output, and careful testing are when trying to isolate bugs. I also got better at reading stack traces and tracing problems through multiple layers of the application instead of assuming the error was happening exactly where it first appeared. This project also taught me the importance of Git and version control. Since the project evolved constantly throughout development, using branches and commits properly became really important for safely testing new features and reverting broken changes when necessary.

Another thing I learned was how important consistency is in larger projects. Many bugs came from frontend expectations not matching backend structures, or components formatting data differently from each other. Because of this, I started relying much more on reusable helper functions and shared utilities instead of rewriting logic in multiple places.

## Conclusion

Looking back, I think the Kitchen Coordinator project gave me one of the most realistic software engineering experiences I’ve had so far. The project became much larger and more complicated than I originally expected, but because of that I ended up learning significantly more than I would have from a smaller assignment. I improved not only my technical skills, but also my ability to troubleshoot problems, design systems, and think about user experience.

Even though there were definitely frustrating moments throughout development, especially when debugging difficult issues or handling edge cases, I think those experiences were some of the most valuable parts of the project. Overall, the project gave me a much better understanding of what real-world software development looks like and made me feel much more confident working on larger full-stack applications in the future.
