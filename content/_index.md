---
title: Introduction
type: docs
---

# Fast F# - A Book for the Community

I am obsessed with performance, and I have longed for a book on writing fast F# code. There are some resources out there, but nothing that went to the depth I am interested in. I want to take the same passion that C++ developers take to low latency code and apply it to the F# language. Some may scoff and say this is foolish. I find the challenge interesting.

I hope this book will result from collaboration across the F# community. I plan to publish new chapters at a steady pace and solicit feedback from the community. This book will evolve as I learn. I plan to put my best ideas out there and get feedback and correction from the community. I fully anticipate being wrong a great deal of the time. I would rather present my ideas and learn from my mistakes than remain in my ignorance. If you have an idea or suggestion, I want to hear it!

## Why am I writing this book?

There are two reasons: I want to learn and offer something to the community. I'm spending most of my time focusing on writing fast code these days. I want to be a world-class developer someday, and that is not going to happen without me putting my ideas out there and letting others provide feedback. I expect my understanding to be entirely rewritten by the time I'm done with this.

I'm willing to be the person who's wrong so that I can hear from others how to do it right. Nothing invites feedback like stating something strongly on the internet. I'm hoping to save younger developers from having to ask all of the silly questions I have and will continue to ask. By documenting this understanding, the community will have a resource to understand how to get the most performance out of F#.

## Who's this for?

This book is targeted at intermediate F# developers. You've already learned a bit of the language, and now you want to know how to get the most performance out of F#. When I say performance, I refer to single-threaded code that runs in the least amount of time possible. I don't plan to cover things like `async` or multi-threading. I don't use them in my work, so I don't have as much experience. I am primarily concerned with how fast code runs. I would welcome collaborators who feel like they could provide an expert's opinion 😊.

## What this book is NOT!

I think it's important to state upfront that this is not a book on "proper" F# style. We may choose to model things in a way that is less elegant for the sake of achieving higher performance. There are already several excellent books that teach how to write concise, beautiful, and clean code. I refer you to them and their superior teaching. If you want to make F# go fast, though... I'll be waiting 😉. 

## Layout and Structure

This book will be a blend of theory and practice. The first half will focus on the internals of the F# language, the F# compiler, and the CLR. We will gain a deep knowledge of exactly how types work in F# and the implication on the performance of our code.

Once we have laid the groundwork, we will go into case studies. The case studies I will write are motivated by real-world problems. They will show how I went from an initial first draft and then used profiling and benchmarking to improve the performance.

## Tentative Table of Contents

The following are just some of what I hope to cover in this book. These aren't necessarily chapters but a rough list of what I want to cover.

1. Array vs. Map vs. Dictionary for lookup performance
2. Data Layout of Ref and Struct Types
   1. Default Tuple vs Struct Tuple
   2. Records vs. Struct Records
   3. Default DU vs Struct DU
3. Equality and Comparison
   1. When the defaults are good enough and when they need to be overloaded
4. Array + Units of Measure for typed indexing
   1. How to use Units of Measure on indices to get zero-cost abstraction on indexing arrays while still getting type checking
5. Byref: What is it and Where to Use It
   1. Where can they help, where do they hurt, 
6. Active Patterns and Partial Active Patterns
7. Types of Loops and which to use
8. Recursion: When it's slow, when it's fast
9. Minimizing GC
   1. Patterns for how to minimize the amount of GC you incur
10. Mutability: How to use it while not blowing your foot off
11. Data-Oriented Design: Some ideas on how to layout data that is both F# friendly but high-performance
12. SIMD: How to use SSE/AVX instructions from F# and when to use them
13. Stupid Bit Hacks: Wacky things you can do for speed
14. Case Study: Generic Topological Sort
15. Case Study: Topological Sort with Heterogeneous Node Types

More to come...

## Want to help?

I welcome other authors and editors. If you have something that you think would add value, I want it! Each chapter will note the author, so readers will know when they hear from a different voice. The book is not meant to be formal, so don't worry about having to create the most polished content. I hope that this feels like a conversation for those reading it.

If you would like to contribute, the books repo is [here](https://github.com/matthewcrews/fast-fsharp). You can reach out to me at my email (matthew@crews.email) or on Twitter, @McCrews.

This book is a Hugo website using the [Hugo-Book](https://github.com/alex-shpak/hugo-book#installation) theme, so all you need to contribute is to be able to write some Markdown!

I also welcome technical review. I want to know if I have misstated something or could dramatically improve my algorithms!

## Publishing Plan

This book will be authored in the open, and this digital version will **always** remain free. This book is my gift to the F# community for tolerating my endless questions. I may offer it as a physical book just because I'd like to have a physical copy, but that is a long way.