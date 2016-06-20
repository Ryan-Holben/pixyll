---
layout: page
title: Coding
permalink: /coding/
tags: navbar
---
[<img src="/assets/img/post_slope.png" style="float:right; width: 45%; height: 45%">](/assets/img/post_slope.png)
I enjoy coding as a creative outlet.  It allows me to nurture a wide variety of interests in the applied spectrum.  I have most recently been using Python in the following pursuits:

* A means to supplement mathematical research
* Machine learning
* Data scraping & analysis
* Physical simulations & cellular automata
* Programming utilities

Technologies I use include:

* Languages: Python, C/C++, Processing, Lua, Javascript, HTML, ...
* Python modules: Numpy, Pandas, Matplotlib, Seaborn, Graph-Tool, scikit-learn, Beautiful Soup, Flask, PRAW, ...
* Other technologies: SQL, MongoDB, Amazon Web Services, Git, Mathematica, \\(\LaTeX\\), ...

## Projects
Here is a selection of projects that I have worked on, with [GitHub](https://github.com/Ryan-Holben/) links where available.

* [Prettify](https://github.com/Ryan-Holben/prettify): [<img src="/assets/img/prettify.png" style="float:right; width: 40%; height: 40%">](https://github.com/Ryan-Holben/prettify) A project which converted raw text notes for [Dr. Richard Pattis' ICS-33 class](https://www.ics.uci.edu/~pattis/ICS-33/) at UC Irvine into a more readable format.  The primary challenge involved was differentiating code and diagrams from natural language.

* [OKC](https://github.com/Ryan-Holben/OKC): This project's lofty goal is to detect fake user profiles on the website OKCupid.  It is a work in progress, and succeeds RedditDB in many ways.  It has 3 primary components: scraping, maintaining a remote database using AWS, and analysis in user-friendly Jupyter notebooks.

* [Game Theory Problem Generator](https://github.com/Ryan-Holben/game-theory-IESDS-generator): A script I wrote to produce problems & step-by-step solutions for the IESDS class of problems in game theory, output in \\(\LaTeX\\), for usage in a course that I teach.

* <a name="Venn"></a>[Venn](#Venn): Code used to verify solutions to a combinatorial problem about the number of regions \\(\mathbb{R}^n\\) can be divided into using \\(k-\\)many \\(n-\\)spheres.

* [RedditDB](https://github.com/Ryan-Holben/RedditDB): [<img src="/assets/img/RedditDB.png" style="float:left; width: 35%; height: 35%">](/assets/img/RedditDB.png) A class used for scraping data from Reddit and storing in a local Mongo database.  This has been used in other projects, including a website hosted on AWS using Flask, in which anybody could populate the database with a user's posts and then view basic analytics.  The site has since ended its run.

* [Run](https://github.com/Ryan-Holben/run): A simple utility for running scripts and other executables from the command line.  Functionality includes notification when a script terminates, and keeping a script alive upon crashing.