---
title: ServerTopPlays
description: Python Discord bot that announces top plays in the rhythm game "osu!" in real-time
date: 2025-09-08
layout: default
permalink: /projects/servertopplays/
---

# ServerTopPlays
*A Discord bot to listen to and announce top plays in the game osu!*

<img src="/docs/assets/top_announcer.jpg" alt="top-announcer" width="400"/>

This bot was initially made since a bot that did this exact same thing got taken down from the Discord bot directory, so I took it upon myself to make one on my own.

Using `discord.py` and osu!API, the bot fetches all recent plays in the top 10 plays for every user.
If the bot finds such a play, the play is converted to an embed and sent in a dedicated announcment channel in a dedicated private Discord server.

[Here's the main repo.](https://github.com/JovKun/ServerTopPlays)

[Home](https://jovkun.github.io/)
