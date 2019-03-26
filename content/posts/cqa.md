---
title: "Colossal Quad Adventure"
date: 2017-01-23T00:00:00Z
showDate: false
draft: false
tags: ["fun","python","games"]
---

Colossal Quad Adventure (CQA) is a text-based game, inspired by Adventure and Ready Player One. The game was born out of a series of light-hearted pranks on my Networks & Distribute Systems professor and features him as the main character. CQA is my passion project, in collaboration with my friend, Zayne Khouja, and will hopefully be played by CS Dept. students & faculty alike. Like Ready Player One, CQA involves three keys, each with their own challenges, mirroring significant concepts all students learn within the UChicago CS major.

<br />
*Technical Details*

Colossal Quad Adventure functions as a state machine, developed in Python. When run, the program creates a multi-threaded socket server so many users can connect (via `telnet`) and play at once, with a leaderboard tracking the top scores. The program is run 24/7 on my headless Raspberry Pi so it can be played at any time.