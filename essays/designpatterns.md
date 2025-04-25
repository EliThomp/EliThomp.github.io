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

Instead, smart builders use patterns: strategies and recipes they can adjust depending on the vendor. Software development isn't much different. In coding my final project, Manoa Munchies, I realized that design patterns are the reusable recipes that keep a project organized, efficient, and adaptable as it grows.

But beyond structure and reusability, design patterns serve a deeper purpose. They offer a shared idea that makes it easier for teams to collaborate. When I worked with others on Manoa Munchies, I noticed how helpful it was to recognize and discuss familiar solutions. For example, choosing a strategy for vendor menus or using a factory-like function to create new menu items. Instead of wasting time explaining every detail from scratch, we could build on ideas that were already tested and understood.

Design patterns also reduce the risk of bugs and make maintenance far easier. By following known conventions, we avoided messy code duplication and made the app easier to debug and extend. It was like building with cookie-cutter parts instead of carving everything by hand. We were able to focus more on innovation and less on reinventing the wheel.

Ultimately, I learned that design patterns are more than programming tricks. They are tools for thinking, communicating, and building better software as a team. They are the glue that helps keep complex projects like Manoa Munchies running smoothly, even as they grow and change.
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

Before Manoa Munchies, design patterns felt like something from a textbook—interesting, but not very practical. As our project got bigger, I realized how important they really are. Without patterns like Strategy and Factory, our code would’ve become messy and hard to manage.

At the start, we didn’t even know we were using design patterns. We were just solving problems in ways that felt natural. But as we learned more about patterns, we began to see them in our own work. That helped us write better code. We made more organized decisions and could explain our ideas more clearly to each other.

In the end, the project started to feel like a well-run market—where each vendor and menu item had a place, and everything worked smoothly behind the scenes.

## What Design Patterns Really Are

At their core, **design patterns are set ways to solve common problems in software engineering**. They aren't strict rules, but rather flexible guides that help developers build projects that are easier to understand and modify.

In my own work, especially with Manoa Munchies, I’ve leaned heavily on patterns like Strategy and Factory to manage complexity and keep the project on a organized path as we grow the project.

And just like a good restaurant thrives by following reliable recipes while leaving room for creativity, good code thrives by following strong patterns while adapting to the unique flavors of each new challenge.
