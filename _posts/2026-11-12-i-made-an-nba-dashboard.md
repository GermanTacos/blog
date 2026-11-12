---
title: I Made an NBA Dashboard
description: Because I'm two lazy for 3 clicks.
date: 2026-11-12 15:00:00 -0400
categories: [SPORTS, TECH]
tags: [sports, basketball, east, eastern conference, west, western conference]
image:
  path: /assets/img/nba-dashboard.png
  alt: Keeping in line with my retro database.
---

I have a very specific, very first-world problem: multiple times a day, I'm referring to the Eastern Conference standings when making updates to my predictions chart, or when seeing what's been going on in the league that day. I also like to check what teams have games going on in the evenings, so I'm always referring to schedules and other info from Google and ESPN.

The problem is in the tiny amount of effort I have had to expend to arrive at that specific info. For standings, I go to Google, type "Eastern Conference Standings," press enter, click the graph, and then click "see more" in order to get a full overview. This is a very easy set of instructions, but daunting when I'm doing it fifty times a day, over and over. To fix that, I made a quick-and-dirty json parser for ESPN's datasets that show, in my own website design, what's going on around the league.

[Visit my NBA Dashboard here](https://tobographic.xyz/utils/nba/)

The info it contains is stripped down, and bare-bones for what I care about seeing: Seed numbers, wins/losses, win percentage, games behind, last 10, and win streak. That's it. The dashboard compacts when viewed on mobile, and when shown side-by-side always places the Western Conference on the left to show the geographical alignment of the conferences.

Additionally, I'm testing out a feature to track live game data, when a team is currently playing: a hoverable pop-up during live games showing the score, game clock, and the most recent play in the play-by-play tracker. The idea is to give a quick at-a-glance overview of the game, rather than worrying about all of the unnecessary data upfront.

I have yet to test all the live features and iron out just how I want them to work, since I pushed the initial version in the middle of the night. But later today I'll get to see if its fully functional and what else I can add to make it more interesting to look at.

In the future, I'd like to add links to stat pages (on ESPN.com) and maybe even find a way to parse the games being played to show live footage, or to link to a reputable stream of the game. Right now I'm focusing on simple, easy data that isn't too overwhelming, though, so that'll come based on what I find myself looking for once I see it in action.

If you'd like me to review a product, email me: [me@jaw.fyi](mailto:me@jaw.fyi)

{% include embed/spotify.html id='1he20mKw1eq2OVp1BKBlpt' %}