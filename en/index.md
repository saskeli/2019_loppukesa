---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
title: Data Structures Project, 2019 end of summer intensive period
---
<script src="../assets/fuu.js"></script>
## Course assistant

* Saska Dönges, (given-name@cs.helsinki.fi), saskeli@IRCnet

## 📅 Time table

Detailed course timing is available [here](timing/).

<script>
    script = document.scripts[document.scripts.length - 1];
    script.parentElement.insertBefore(makeCalendarEn(), script);
</script>

## 📣 News

* <script>
   if (doodleSent) {
    if (timing["demo"]) {
      document.write("Time an place for demonstration sessions has been set. Contact a course assistant if you can't make it.");
    } else {
      document.write("Doodle link for demo session planning has been sent to registered students. The email address is the one configured in weboodi.");
    }
   } else {
    document.write("A poll will be sent out around the half way point of the course to schedule demo session(s).");
   }
 </script>
 * The final submission deadline is on <script>document.write(enString(timing["end"].date));</script>. There are no time extensions available.
 * If you find typos or other errors on the course pages, please submit a Pull Request with the fix ([instructions]( 	bug_bounty.md)). A bug bounty of 1 course point will be awarded for significant fixes (capped at 1 per student).

## Links to course material

* [Detailed course schedule](timing/)

* [Topic ideas](topics)

* [Information about the required documentation](documentation/)

* [Guide to using git](git/)

* [Guide and examples on testing in java projects](https://github.com/TiraLabra/Testing-and-rmq)

* [Simple instructions for creating Gardle or Maven projects](maven-gradle/)

* [Information on submissions and weekly reports](submissions/)

* [Information on peer reviews](peer_review/)

## 🗒️ Labtool

 * [https://studies.cs.helsinki.fi/labtool/](https://studies.cs.helsinki.fi/labtool/)
 * Sign in with your University of Helsinki account.

## IRC and telegram
The course IRC channel is **#tiralabra** @IRCnet.
The Telegram channel can be found [here](https://t.me/tkttiralabra).

Generally the Telegram and IRC chats are linked (bridged) together, so the course assistant will be available through both channels.

## Guidance

* There is no weekly course assistance during the summer intensive period. If you want face to face assistance on campus please contact the course assistant.
* You may also contact the course assistant through [Telegram](https://t.me/tkttiralabra) or IRC.
* E-mail also works.

<!--### Algorithm workshop

* The primary guidance for the course is organized in conjunction with the [algorithm workshop](https://courses.helsinki.fi/en/tkt20000/126082463) on Fridays (BK107 15-18).
* You can attend the algorithm workshow at other times as well to get help with data structures or algorithms. The assistant may not be able to help you with course specific things other than on Fridays.
-->
## Demonstration

* * <script>
  if (timing["demo"]) {
    document.write("Paikka ja aika: " + enEvent(timing["demo"]) + ".");
  } else {
    document.write("Time and place for the demo session will be confirmed later.");
  }
</script>
* **Mandatory!** Contact the course assistant if you can not make the Demo session. The Demo session is mandatory to get a passing grade!
* You can present with your own laptop. In this case you may want to arrive early to test that the laptop works properly with the projector.
* All projects will also be loaded onto a presentation machine, which you may use for the demonstration. However there have been issues with this in the past so presenting with your own laptop is recommended.
* Approximately (at most) 5 minutes per project.
* Slides are not required for the presentation and generally not recommended unless you have a specific reason to use them.

## Example projects

* [Saskeli's project](https://github.com/saskeli/NonogramSolver_TiRa) **Note:** The course has changed somewhat after this project was made.
* Jussi was also kind enough to allow [his project](https://github.com/yussiv/Compress) to be provided as an example. But stated that the project was made with pretty minimal effort.
* Both of these still have a good project structure.

## 🏆 Conduct of the course
Based on the number of credits (4) offered, the expected amount of work to complete the course should be approximately 107 hours. Plan to spend 15-20 hours on the course every week.

In this course the student creates a program that solves some sort of a problem. For solving the problem the student will apply suitable data structures and algorithms. The problem to solve is selected by the student with the help of the course assistant. A passing (or even good) grade does not require developing an algorithm from scratch. A student may develop their own algorithm(s) if desired. The main point of the course is that the created program works correctly and efficiently. The size of the problem instances and required efficiency will depend on the topic, and will be decided with help from the course assistant. Some example topics can be found [here](topics/).

The course will be partially (mostly) done online. All weekly submissions will be done online. The only mandatory meetings for the course are the first lecture and the demo session. More information on the submissions can be found [here](submissions/).

The program will be written in a language **approved by the course assistant**, which is almost always Java.

The primary goal of the course is to learn to implement data structures and algoritms. For this reason all required data structures and algorithms will have to be implemented by the student. Generally only primitive types, arrays and strings may be used, everything else has to be implemented using these. Other tools such as IO and GUI libraries may be used. **Data structures from standard libraries (such as ArrayList, HashMap and so on from Java) or algorithms (Collections.sort...) may not be used in the final submission**, and it is suggested that the imports for these are completely removed. If you are unsure if a particular class/library is allowed, ask the course assistant.

Generally a good approach to incrementally complete a project has been to first implement the core functionality of the program by using ready-made data structures and algorithms (queues, heaps, sorting algorithms). That is, it may be a prudent to first quickly implement the core functinality and later replace library implementations with self-made ones, i.e. replace implementations defined by interfaces with data structures and algorithms made from scratch. This is the assumed working idea for the project timeline. If you want to approach the project in a different way, you should decide on progress milestones for the project with the course assistant during the first week of the course.

## 📈 Grading criteria
* Program: 30 p
   * Functionality and features 10 p
   * Testing 10 p
   * Code documentation (JavaDoc and self documenting) 5 p
   * Clarity of the code 5 p

* Documentation 10 p
   * Topic definition 2p
   * Implementation 3p
   * Testing 3p (unit- and performance-!)
   * User guide 2p

* During the course 20p
    * Code reviews 2 * 2p = 4p
    * Weekly submissions 1p + 5 x 3p = 16 p

(All in all 60 p)

For a passing grade the project needs to contain self-made implementations for data structures and algorithms. Every project is separately graded. Below are typical gradings based on points.

* 5: 50 p
* 4: 45 p
* 3: 40 p
* 2: 35 p
* 1: 30 p
