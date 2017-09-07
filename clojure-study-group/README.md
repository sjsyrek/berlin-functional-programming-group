# Clojure Study Group

## Introduction and goals

The Clojure Study Group is a meetup series organized as part of the larger [Berlin Functional Programming Group](https://www.meetup.com/de-DE/Berlin-Functional-Programming-Group/) effort. Although its goal is to introduce attendees to the Clojure programming language, it is also a good starting point for learning about [functional programming](https://en.wikipedia.org/wiki/Functional_programming) in general. 

Additionally, the group should provide a forum for discussion of the topics covered by the learning material.

We assume no previous knowledge of Clojure or FP, but we still need you to at least be familiar with the fundamentals of programming (i.e., you know what a compiler is, variables/constants, functions, conditional statements, loops etc.).

### Why Clojure? 

If you've already decided to join, you're probably familiar with the "why" and you can skip directly to the [learning materials](#learning_material). Otherwise, please keep reading in order to figure out if the group is the right fit for you. 

There are probably several, good reasons why Clojure should be the language of choice for your next project. To name a few:
* __Simplicity:__ Clojure has a very concise Lisp-like syntax that is easy to pick up but powerful at the same time.
* __Interoperability:__ It can run on the [JVM](https://en.wikipedia.org/wiki/Java_virtual_machine) or compile to JavaScript for use with [Node.js and in the browser](https://clojurescript.org/), together with your existing code and using existing libraries.
* __Encourages functional programming:__ It was built with immutability, higher-order functions, avoiding side-effects and other FP principles in mind.
* __Designed for concurrency:__ With immutability, [Software Transactional Memory](https://en.wikipedia.org/wiki/Software_transactional_memory), and agents, Clojure simplifies the development of concurrent applications.
* __Maturity:__ It has already been used in production systems for years, has a big and growing community, and has been adopted by [many companies](https://clojure.org/community/companies).
* __Other:__ You can find out a lot more about the motivations for Clojure [here](https://clojure.org/about/rationale).

## Learning material<a name="learning_material"></a>

We will use _Clojure for the Brave and True_ by Daniel Higginbotham as our primary textbook.

Although the book is available [online at no cost](https://www.braveclojure.com/clojure-for-the-brave-and-true/), we'd really like to encourage you to [buy the printed](https://www.amazon.de/Clojure-Brave-True-Ultimate-Programmer/dp/1593275919/ref=sr_1_1?ie=UTF8&qid=1504465315&sr=8-1&keywords=clojure+for+the+brave+and+true) version and support the author. 

![Clojure for the Brave and True](img/clojure-for-the-brave-and-true.png) 

## Plan

We should be able to cover the complete book over the course of 12 weeks. The initial session will cover the first two chapters, after which we'll proceed at a pace of one chapter per week.

#### How to prepare for each session:
* Read the chapter(s) for the current week.
* Type out, compile, and run the code from the book, or run it in the REPL. By "type out" we really mean _type out and __not__ copy-paste! Typing will make you think and reason about the code, ideally leading to a better understanding of it.
* Optional: Take note of your questions, ideas, or discussion topics related to each chapter as you go through it.

#### What we will do during the sessions: 
* Take 5 minutes to quickly review what we covered the previous week. 
* Redo the exercises from the book, potentially without using it.
* Cover questions and discussion topics.
* If there is time left, we will solve exercises from other sources. The difficulty of the exercises should match what we've covered in the sessions up to that point.

#### What the sessions are *not* for:
* The sessions _will not_ cover the weekly material in the form of a lecture, as we want to use our meeting time for more hands-on tasks. We believe that interactivity and open discussion provide better learning results than passive attendance, however that also necessitates doing your "homework" beforehand.

## Requirements for attending

You will need to ensure that you do the following in order to participate in this group successfully:
* Join the [Berlin Functional Programming Group](https://www.meetup.com/de-DE/Berlin-Functional-Programming-Group/) on Meetup and the [FPChat](https://fpchat-invite.herokuapp.com/) community on [Slack](https://slack.com/downloads/). All announcements pertaining to this study group will be sent out via Meetup and Slack. On the FPChat Slack, look for the `#berlin` channel.
* Buy a printed copy of the learning material (no pirated versions!!!) or use the online version.
    * Please keep in mind we can't always guarantee you access to the Internet, so if you decide to use the online version of the book, make sure you have a means of accessing it.
* You'll need a laptop with Linux, macOS or Windows installed.
* Make sure you install the following:
    * [Leiningen](https://leiningen.org/)
    * [GNU Emacs](https://www.gnu.org/software/emacs/) (recommended but optional)
        * A default editor or IDE won't be enforced and feel free to choose whatever you feel most comfortable with. Having said that, there is a chance it will be harder for us to assist you with a problem if you go the custom route.
        * If you decide to go with Emacs, the second chapter of the book already covers [how to set it up for Clojure](https://www.braveclojure.com/basic-emacs/). Since we plan to cover this chapter already in the first week, ideally you'll have it set up before the first session. In case you run into any problems on your own, there should be enough people at the session who can help you. 

## Location and dates

Refer to the [Berlin Functional Programming Group on Meetup](https://www.meetup.com/de-DE/Berlin-Functional-Programming-Group/).

## Useful resources

* [Clojure for the Brave and True](https://www.braveclojure.com/) by Daniel Higginbotham, the primary textbook for this study group
* [Official Clojure guides](https://clojure.org/guides/getting_started)

### Talks by Rich Hickey, author of Clojure

* [Simplicity Matters](https://www.youtube.com/watch?v=rI8tNMsozo0)
* [Simple Made Easy](https://www.infoq.com/presentations/Simple-Made-Easy)
* [The Value of Values](https://www.youtube.com/watch?v=-6BsiVyC1kM)
