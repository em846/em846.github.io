---
layout: essay
type: essay
title: "Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2023-11-29
published: true
labels:
  - Design Patterns
  - Software Engineering
---

## Something I wish I knew sooner

The subtitle above is what design patterns are to me. I think it's a great organizational tool and think of it similar to building off a template. With templates, you don't have to think much about the big-picture arrangement of things, which I think helps to minimize other issues arising since it should already be tidy and to make looking for errors easier later.

This can also be applied to when collaborating with others, where those same benefits can apply to people you work with, but it also makes the communication of errors a lot less painful.

Knowing this ahead of time could have saved me time and brain power, but also, looking back, I should've realized there was a pattern.

## New Tools

Continuing on the idea of it being a template, that's exactly what happened in a team project of mine. The site should hold a collection of events with certain attributes that users can submit to then display on the site. This collection is a Singleton, based on an example my team saw for a different site that used a Singleton design pattern to instantiate a collection of objects that can then be used in other parts of the site.

I also think that the Observer design pattern could be useful in another function of our application that deals with sending out a notification to users of an upcoming event, but I have not looked further into this in particular or whether it would even be a good fit for our goals.
