---
draft: true
date: 2020-04-11T13:52:39-07:00
title: "Revisit WWF Project"
description: ""
slug: ""
tags: []
categories: []
externalLink: ""
series: []
---

I have a lot of free time on my (washed) hands whilst staying inside due to COVID-19. I noticed my boyfriend got back into playing the popular Zynga game Words with Friends.

Years ago while on my commute to work, I started dabbling with mitmproxy and monitoring the network traffic and API, but never got to the meat of solving the game.

Thinking of looking back into it now, perhaps as a sequence of interview-type problems.

### Part One: Make a Move

> Given a set of words, a board, and a set of N tiles, where 1 <= N <= 7 and tiles represent one character [A-Z], determine the best possible move.

``` java
public Move makeMove(String[] words, char[][] board, char[] chars)
```

Not necessarily a trivial problem, especially since `best possible move` is loosely-defined. For the sake of this exercise, we'll assume an offensive play for now and disregard. Since I wanna get this up and running today, I will do a simple brute force solution.

Just gonna throw a quick outline of what I'd do:

- normalize and index words
- represent and relate words on board as `Word` objects
- find all places a `Word` can be placed
- return the move with highest score

Guess I'll get started!

### Part Two: Consider Letter and Word Multipliers

> Given a board configuration with `DL`, `TL`, `DW`, `TW` multipliers, adjust the `makeMove` method to take the configuration into account.

### Part Three: Connect to WWF API

Most of this is done [here](https://github.com/josh-dot-com/words-with-fiends)

### Part Four: Scan Board Screenshot (Computer Vision)

### Part Five: Defensive Play AI

### Part Six: Will I Even Get This Far

TBD?!?
