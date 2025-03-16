---
layout: post
title:  "We’re in transition."
date:   2020-08-23 08:41:00 +0000
categories: design, development, reviews, upgrade
author: Diviyesh Patel
---

Following on from my previous post, we’ve updated and maybe tidied a few duplicates.

There’s also been many discoveries along the way too. Stuff that doesn’t work nor spotted in system, which makes one think are these features ever been used?

Prioritising the ‘must’ from ‘nice to have’ fixed bug features is good, but could be better managed. Questioning whether they are in use or not, and to fix any major issues found along the way.

Of course business doesn’t just stop when there’s a major change, so there’s new features made in the pipeline ready for deploy.

The issue is having merge conflicts, between branches especially if there’s been many tweaks across branches.

Sometimes doing less is as valuable as doing more. So the point to take away here is accept temporary changes inbetween branches.

Yes, it’s not great for the user experience as things may look different between merges, but then again question whether there’s greater value in doing these changes in a time of merging features?

Reducing number of conflicts reduces number of hours spent revisiting repositories to review changes and a larger gain to being productive developing and improving features.

A valid point, do users prefer working software oppose to something just looking nice?

Ideally, best of both worlds would be great, but the reality is, there’s a limit to most things in development and a far greater possibility to revise designs/styles once features are merged and streamlined into few branches.

That’s where we can now develop new features in priority starting with aesthetics.

On a side note, how many developers have worked with Bootstrap 4 and noticed something interesting?

There’s a class for nearly every style, no need to customise the CSS, but for colours.

Why so many classes?

It also reduces the amount of conflicts found across the system when styling with classes especially if you’re not used to CSS (from an entry level) or the system if it was made before your time.

It’s also safe when upgrading a system, if a team were to use existing classes instead of custom classes or CSS.