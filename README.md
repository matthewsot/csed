# csed
Intro to CS lessons targeted for middle schoolers.

Most of these were adapted from the Develop Summer Academy 2017 Intro to Computer Science course. Learn more at http://develop.academy.

# Retrospective
In retrospect, there are a number of things I believe we did well and not-so-well with this course. I have provided an incomplete below of my thoughts on the subject, which I hope may prove to be more helpful than the limited set of resources in this repository.

1. This course should have been named "intro to computer programming." We named it "Intro to Computer Science" almost completely because of marketing concerns. The goal of the course was clearly to enable students to get up and running with simple, interactive Javascript programs as fast as possible -- which is great! But I think recognizing and acknowledging the fact that that was our goal (vs. trying to hit the field more broadly) would have helped to focus the course/materials more.
2. YAEPL was a good idea, Javascript really wasn't. I feel very strongly that intro courses should start with a non-OO language with as simple of a syntax as possible, so that students can focus on solving problems instead of trying to work out syntax quirks or dealing with very high-level abstractions. YAEPL hit all of those boxes very well, and the students seemed very responsive to it. Unfortunately, due to the short timespan of the course, we spent only a single day on YAEPL before transitioning completely to Javascript, an OO language with _much_ messier syntax rules, which understandably caused a lot of confusion. We attempted to only cover the non-OO parts of Javascript in this course, but it's practically impossible when you need to use things like ".length" on strings. In retrospect, I wish we had used C as the main language in the course. Unfortunately, you can't really use C with a webpage (we wanted to keep some continuity with our web dev course), so that adds an extra layer of difficulty to the choice. But if you're just teaching programming, I believe that YAEPL -> C would be a great transition.
3. We had very little time. It would have been nice to expand this over multiple weeks.

# YAEPL
We started the class using an educational programming language named YAEPL. There is a reference sheet for the language inside this repository that was provided to the students, and you can learn more about YAEPL at its repository page here: https://github.com/matthewsot/asm-yaepl

After the first day, we transitioned to using Javascript exclusively.

We also used a custom, cross-platform application to code in, that supports both YAEPLE and Javascript, has some graphical helper functions for the Hangman project, has a command-line-like interface (including support for "write" and "prompt"), and is avalable here: https://github.com/matthewsot/yaepl-app

# License
Registered non-profits may use these lessons for free to help teach middle-school age students.

For all other uses, or to ask any questions about the lessons, please feel free to contact me at matthewsot@outlook.com
