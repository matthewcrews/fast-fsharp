---
title: Introduction
type: docs
---

# Fast F# 0.0.1-alpha

I am obsessed with performance, and I have longed for a book on writing fast F# code. There are some resources out there, but nothing that went to the depth I am interested in. I want to take the same passion that C++ developers take to low latency code and apply it to the F# language. Some may scoff and say this is foolish. I find the challenge interesting.

I hope that this book will result from collaboration across the F# community. I plan to publish new chapters at a study pace and solicit feedback from the community. I fully anticipate being wrong a great deal of the time. I would rather present my ideas and learn from my mistakes than remain in my ignorance. If you have an idea or suggestion, I want to hear it!

## Who's this for?

This book is targeted at intermediate F# developers. You've already learned a bit of the language and now you want to know how to get the most performance out of F#. When I say performance, I am referring to single-threaded code that runs in the least amount of time possible. I don't plan to cover things like `async` or multi-threading. I don't use them in my work so I don't have as much experience. I am primarily concerned with how fast code runs. I would welcome collaborators who do feel like they could provide an expert's opinion 😊.

## What this book is NOT!

I think it's important to state upfront that this is not a book on "proper" F# style. We may choose to model things in a way that is less elegant for the sake of achieving higher performance. There are already several excellent books that teach how to write succinct, beautiful, and clean code. I refer you to them and their superior teaching. If you find yourself want to make F# go fast though... I'll be waiting 😉. 

## Layout and Structure

This book will be a blend of theory and practice. The first half will focus on the internals of the F# language, the F# compiler, and the CLR. We will gain a deep knowledge of exactly how types work in F# and the implication on the performance of our code.

Once we have laid the groundwork, we will go into case studies. The case studies I will write are motivated by real-world problems. They will show how I went from an initial first draft and then used profiling and benchmarking to improve the performance.

## Want to help?

I welcome other authors and editors. If you have something that you think would add value, I want it! Each chapter will note the author, so readers will know when they hear from a different voice. The book is not meant to be formal, so don't worry about having to create the most polished content. I hope that this feels like a conversation for those reading it.

If you would like to contribute, the books repo is [here]()

This book is a Hugo website using the [Hugo-Book](https://github.com/alex-shpak/hugo-book#installation) theme, so all you need to contribute is to be able to write some Markdown!

I also welcome technical review. I want to know if I have misstated something or could dramatically improve my algorithms!

## Publishing Plan

This book will be authored in the open, and this digital version will **always** remain free. This book is my gift to the F# community for tolerating my endless questions. I may offer it as a physical book just because I'd like to have a physical copy, but that is a long way.