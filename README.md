# Solo Study

#### A day of self-directed study, practice, discovery and magical wonderment, January 26th, 2018

#### By **Luke Bertram**

## Description

This repository is intended to house the results of my day of independent self-directed study during the Epicodus Javascript track. At the time of this writing, even I do not know exactly how this will be manifested.

## Setup/Installation Requirements

The notes in this README represent the majority of this week's project. If you'd like to view the progress I've made on my version of the Rails Tutorial's "Sample App", just visit the version I have hosted [here on Heroku](https://luke-solo-study.herokuapp.com/) or check out [my github repo for the project](https://github.com/lukebertram/sample-app).

## Process

### Prompt

>"Today your project will be your own development. Focus on the things you feel you don't know yet; and the things you don't yet feel good at. This exercise is meant to expose your blind spots, and allow you to actively work on improving any weaknesses so you can progress through the rest of the program confidently and efficiently."

### Weaknesses/Topics of Interest

|Technical | Non-technical|
|:---------|:-------------|
| Unfamiliarity with SQL databases - research and/or implement| Need polished, comprehensive resume (including work prior to Epicodus) |
| Research Tone.JS library (music synthesis in JS) | Practice succinctly answering common interview questions (both technical and non-technical) |
| Determine how to effectively implement an RPG within an AngularJS framework (for next week's project)| Try out the Pomodoro technique to help with time-management/focus |
| AWS - start a free account and try to build/host something with it| * |
| Study, start compiling into a single file several examples of the algorithms discussed in [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms).| * |
| Brush up on Rails for a bit of potential upcoming work and to help justify its inclusion on my resume | * |

### SQL Study

* Look through Java/Ruby Epicodus curriculum for introduction to database Topics

* Write a little summary of knowledge attained right here:

>Here is what I learned about SQL today:
> * I upgraded my laptop's version of Postgres - then researched how to reinitialize the database cluster directory so I could once again run a Postgres server from the command line. I then reinitialized that directory.

> * Data is organized into `tables` which can be related to each other by `primary keys`. Each table is comprised of `rows` which represent entries (or `records`) in the table. Each row is comprised of `columns` (or `fields`), each of which represents a property of the entry described by that row.

> * Common SQL data type keywords: `int`, `float`, `varchar` (SQL's keyword for strings of variable character length), `text` (for long blocks of text), `timestamp`, and `boolean`

> * SQL command keywords are conventionally written in all caps, and SQL statements must end with a semicolon.

> * A table can be related to another by means of a column whose value is the unique ID (or `key`) of a record in the other table. This entry is known as a `foreign key`.


### Algorithm Study

* Binary Search
* Big O Notation
* Arrays & Linked Lists
* Selection Sort

### Rails Study

Follow along with the [Rails Tutorial's](https://www.railstutorial.org/) creation of a Twitter clone (from chapter 3 onward).

* Created a new repository on [my Github](https://github.com/lukebertram/sample-app).

* Added a 'hello world' action (renders 'hello' html statement to the page) to the base application controller and set that action as the root route

* Deployed [my new application](http://luke-solo-study.herokuapp.com/) to Heroku at http://luke-solo-study.herokuapp.com/.

* Reread the first two chapters of the Rails Tutorial in order to refresh my knowledge of how Rails implements RESTful routes and MVC architecture, as well as data validations on and associations between models.

* Found a great description of [how to grep for stray processes from the Unix command line](https://www.railstutorial.org/book/static_pages#_aside-processes) near the end of Chapter 3 of the Rails Tutorial. I can remember wanting to reference this aside in the past and not being able to find it.

* Removed the simple 'hello world' page at the root route of the site and replaced it with a very slightly dynamic home page.

## Known Bugs

No known bugs as yet.

## Support and contact details

Flag me down in class, or send me a tweetbook on facestagram if you have any troubles.

### License

MIT License

Copyright (c) 2017 **Luke Bertram**
