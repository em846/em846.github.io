---
layout: essay
type: essay
title: "Effective Communication and Asking Questions"
# All dates must be YYYY-MM-DD format!
date: 2023-09-03
published: true
labels:
  - Questions
  - StackOverflow
---

## How To Succeed in Life! (Not Clickbait!)

The key to success, I've found, is knowing where and how to ask for help. Unfortunately, there is rarely someone who will hold your hand all the way through and there exists no telepath that knows your needs better than you do. Communication is key in society, and precise communication even more so when time and attention is a valuable and finite thing. This requires a degree of independence and critical thinking.

To tie this into software engineering for example, I have already run into many problems while coding that have left me stuck, my brain exploding in a plume of smoke, thinking, "I have no idea what I'm doing or looking at." Here's where the solution might be to ask for help, and also where this solution could be wrong depending on how I ask for that help.

The following are two examples from StackOverflow, a site for asking programming questions, that I think show a good way and a bad way to ask for help.

## A "Smart" Question

First, the [good example](https://stackoverflow.com/questions/513832/how-do-i-compare-strings-in-java).

This user wanted to understand the difference between the `==` operator and `.equals()` method in Java after encountering that changing the code from using the former to the latter had fixed an issue with comparing strings.

At first glance, it seems like a needlessly simple question. However, how this problem was presented is interesting and shows the user is working and thinking. The user encounters the problem and manages to fix it on their own which is the independence and critical thinking I mentioned earlier. Again, other people's time and attention are finite, so trying to search for answers independently first is the best course of action. This also means that if there's any dead ends, those can be communicated so that others don't try those paths and waste their time; it's efficient for both the user and the people helping.

The issue the user is presenting is the lack of understanding as to why the fix worked. The answers provided below answer the question this user has at the end of the user's explanation: "When should it and should it not be used?" Instances of usages of each `==` and `.equals()` and how they are not interchangeable are provided. These answers convey a concept and can be kept in mind and applied to future projects, so the same mistake is less likely to happen again. Not only that, but with the title "How do I compare strings in Java?" will easily appear with a quick search for others to learn from in the same manner; therefore, no one else should be asking it again, making it a very good resource to return to, even for the user who asked the question. It's a clear and smart question!

## Unclear Communication

Now, the [bad example](https://stackoverflow.com/questions/47765274/android-studio-appcompat-v726).

This user is facing some sort of issue when attempting to create a new project in Android Studio. I can't tell what exactly else is happening, and though it may be just me not knowing how this IDE works, I think it is a point that the details of the problem is not immediately apparent with words alone. The user also doesn't mention any sort of troubleshooting and has attached a handful of screenshots, a few of which look the same but, upon close inspection, have some changes.

In my opinion, it would have been nice if that had been indicated somewhere or relayed in the user's words in the beginning. Other users have provided answers to this post, but it doesn't seem that the original user has interacted with any of them, leaving responders in the dark about the situation. With so little feedback and a hard to parse problem, it's understandable that there aren't more answers to this. It's overall a confusing and time-consuming experience.

## Effective Questions

People can't help if they can't see what the problem is, and it's a moot point trying to ask for help with a problem that isn't well defined. This is true in life as well as software engineering. It's like calling an ambulance and not knowing where you are or how you're hurt; or worse, knowing but not saying. They're not going to show up! Help others help you; get your ducks in a row before asking questions.
