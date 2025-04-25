---
layout: essay
type: essay
title: "Recipes for Smart Programming"
# All dates must be YYYY-MM-DD format!
date: 2025-04-25
published: true
labels:
  - Software Engineering
  - Reflection
  - Learning
---

## Building a Marketplace Without Chaos

Imagine you're opening a bustling food court. Vendors from all over town are setting up shop: poke bowls, acai stands, plate lunch counters—you name it. Each vendor has different needs, different menus, and different ways of running things. If you tried to build each booth from scratch, one by one, your project would quickly spiral out of control.

Instead, smart builders use *patterns*: strategies and recipes they can adjust depending on the vendor. Software development isn't much different. In coding my final project, Manoa Munchies, I realized that design patterns are the reusable recipes that keep a project organized, efficient, and adaptable as it grows.
<center>  <img src="../img/marketplace.jpg" alt="Busy Marketplace" width="700" style="height: auto;" /> </center>

## Flexibility Through the Strategy Pattern

One example that worked for me was the **Strategy Pattern**. In Manoa Munchies, vendors needed to manage their menus, but not every vendor followed the same process. Some menus updated daily and some vendors had "specials" that appeared only on certain days. Rather than hard-coding one menu management method, my team and I built flexible logic where the system could *choose* a strategy based on the vendor's needs.

If a vendor haed a special they were able to list it while also giving them an option to create static menu items. This was like choosing different ways to run a kitchen depending on what cuisine you wanted to make.

## Efficiency Through the Factory Pattern

Similarly, the **Factory Pattern** became a silent workhorse of the project. Whenever a new menu item needed to be created—whether it was a "Garlic Shrimp Plate" or a "Spam Musubi"—we didn’t manually build the item piece by piece.

Instead, we used functions that acted like factories: plug in the name, price, description, and out came a fully-formed `MenuItem` ready to be added to the database and shown on the site. This made creating new entries reliable and predictable, no matter how many vendors or items we added.

Much like a bakery can use the same oven to make different kinds of bread, the Factory Pattern let us mass-produce menu items without reinventing the process every time.

## Lessons Learned From Using Design Patterns

<center> <img src="../img/designpattern.png" alt="Design Patterns" style="max-width: 100%; height: auto;"> </center>

Before Manoa Munchies, design patterns felt abstract, like something you only read about in textbooks. But once the project grew bigger, I saw how vital they really are. Without patterns like Strategy and Factory, the codebase would have been a cluttered mess, impossible to maintain or scale.

Instead, the project felt more like running a well-organized market—where each vendor and menu item had a clear place and a clean process behind it.

## What Design Patterns Really Are

At their core, **design patterns are set ways to solve common problems in software engineering**. They aren't strict rules, but rather flexible guides that help developers build projects that are easier to understand and modify.

In my own work, especially with Manoa Munchies, I’ve leaned heavily on patterns like Strategy and Factory to manage complexity and keep the project on a organized path as we grow the project.

And just like a good restaurant thrives by following reliable recipes while leaving room for creativity, good code thrives by following strong patterns while adapting to the unique flavors of each new challenge.
