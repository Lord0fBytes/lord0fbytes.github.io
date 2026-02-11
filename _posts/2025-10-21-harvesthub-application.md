---
layout: post
tags: [project, digital, application]
highlight: wip
title: HarvestHub - Shopping List App
categories: digital
permalink: /:categories/:slug/
---

## Building a Shopping List App That Doesn’t Fight My Brain

This project started for a very unglamorous reason:
our family shopping list kept falling apart.

As our needs changed, most apps either felt too simple to be useful or too rigid to adapt. I wanted something that could grow with us — **but also something structured enough to eventually plug into AI systems without duct tape**.

That idea became **Harvest Hub**.

---

## The Original Goal (and Why I Didn’t Just Use an Existing App)

I wanted a shopping list that could:

* Scale with a family (quantities, categories, multiple stores)
* Work equally well while planning *and* while standing in a grocery aisle
* Expose clean, predictable data that an AI or LLM could reason about later

Most shopping apps optimize for checking boxes.
I wanted one that understood **intent**, **quantity**, and **context**.

---

## How the App Is Structured (Right Now)

The app currently revolves around four main pages. This wasn’t obvious at the start — it took a few rewrites to land here.

### Planning Page (Where Everything Starts)

This is the “thinking” page.

It contains a raw list of all items I might ever buy. From there I can:

* Assign quantities
* Tag items (staples, kids, adults, beverages, etc.)
* Mark items as pending, skipped, or completed

The planning view only shows:

* Items with a positive quantity
* Or items marked as pending

From there, I can sort things:

* Alphabetically
* Or by **store aisle order**, which turned out to be way more important than I expected

This page is mostly used *before* shopping, but it’s also where a lot of cleanup happens.

---

### Shopping Page (Optimized for Reality)

This page exists because shopping is chaotic.

Here the goal is speed and clarity:

* Clean list view
* Swipe gestures to delete or edit
* Quantity adjustments as items are checked off
* Sorting by store and aisle so I’m not zig-zagging through the building

This is the page I actually have open in the store.

---

### Review Page (What Actually Happened)

After a shopping trip, I wanted some lightweight feedback:

* How many items were purchased
* Quantities
* (Eventually) prices
* Breakdown by store
* Simple ratios of where things were bought

Nothing fancy — just enough to see patterns over time.

This page also lets me clear a completed list or review past purchases.

---

### Edit Page (Still a Bit Rough)

This is where items themselves are managed:

* Create, update, delete
* Assign tags
* Adjust defaults

It works, but it’s not pretty yet. This page is high on the polish list.

---

## The Tech Stack (So Far)

The first phase of this project was mostly about **getting the data model and flow right**, not perfecting the UI.

Current setup:

* **Next.js** for the app
* **Supabase** (or similar) for backend/data — still evaluating long-term fit
* **Tailwind CSS** for styling
* **Claude Code** to help scaffold the initial structure and unblock me when I stalled

A lot of this evolved mid-build. I changed my mind more than once.

---

## Versions, Rewrites, and Reality

The app went through versions 2 through 8 faster than I expected.

Each rewrite fixed one thing and broke another:

* Navigation felt wrong
* State didn’t match how I actually shopped
* Features made sense on paper but not in real life

The current version is **v1.0**.

It’s been running for a couple of weeks now and:

* It works
* I use it regularly
* There are still bugs

That feels like the right time to call something “1.0”.

---

## What’s Next (Short-Term Roadmap)

Next versions are mostly about polish and speed:

* Improving the edit page
* Quick-add and quick-edit actions
* Fewer taps, fewer screens
* Better gesture handling

No big architectural changes planned — just tightening things up.

---

## The AI Part (Why This Exists at All)

The long-term idea was always automation.

Eventually, I want to be able to:

* Feed an LLM a recipe and have it:

  * Identify ingredients
  * Adjust quantities
  * Update the shopping list automatically
* Feed in a weekly meal plan and:

  * Parse all linked recipes
  * Generate a complete shopping list
  * Deduplicate items intelligently

The goal is a mostly automated flow that still lets me override things when needed.

This is why the data structure matters more than flashy UI right now.

---

## Sharing This as I Go

This post is part documentation, part checkpoint.

I’ll be adding screenshots as the UI stabilizes and posting updates as the project evolves. Some parts are polished, some parts are still janky — and that’s kind of the point.

This is me building in public, not presenting a finished product.

