---
layout: info
title:  "Course timing"
categories: jekyll update
tag: info
permalink: /en/timing/
---

# Week 1:

* Submission 1: **<script>document.write(enString(timing["dl1"].date));</script>**
    * You have a topic, programming language and sense of project scope.
      * You should consult with the course assistant if anything is unclear. If you are using Java and have selected a clearly valid topic you can move on to creating the project specification. If you have a topic you are uncertain about or if you are considering not using Java you should definitely discuss with the course assistant.
    * Documentation: Project specification done.
    * Check [documentation instructions](../documentation/)
    * Week 1 report: First weekly report is done (see [submissions](../submissions/))
    * Make sure that you have linked your weekly report and project specification to the repository front page to ease grading. If you need help with Markdown you can check this [guide](https://guides.github.com/features/mastering-markdown/), ask for help from the course assistant or just look at the source code for this file!
    * Project: Project has been created. Check [here](../maven-gradle/) for instructions if needed. GitHub version control is set up. Everything that needs to be submitted has been added to version control, nothing is submitted by email or pidgeon!
    * Enable adding issues to your repository for code reviews. [enabling issues](../issues/)
    * Register to Labtool: [https://studies.cs.helsinki.fi/labtool/](https://studies.cs.helsinki.fi/labtool/)
    * [Quick guide](../labtool/) for Labtool.

# Week 2:

* Submission 2: **<script>document.write(enString(timing["dl2"].date));</script>**
    * [Documentation](../documentation/): Written code is clear and commented (e.g. Java program contains Javadoc comments).
    * Week 2 report: see [submissions](../submissions/)
    * Program: Work on implementing the core functionality has been started possibly using library implementations of algorithms and data structures. These will later be replaced with self-made implementations, but in many cases it's easier to use library implementations first.
    * Testing: *Comprehensive* unit testing of the code. (e.g. JUnit tests for Java)
		* Ensure that when creating new classes you also create tests as soon as possible (preferably in the same submission as the class was created) to make sure that you new implementations work as expected. See [supplementary material on testing](https://github.com/TiraLabra/Testing-and-rmq) if needed (Finnish).

# Week 3:

* Submission 3: **<script>document.write(enString(timing["dl3"].date));</script>**
    * [Documentation](../docuementation/): Written code is clear and commented.
    * Week 3 report.
    * Program: Werk on implementing core functionality has continued. Possibly started implementing data structures.
    * Testing: *Comprehensive* unit testing of the code.

# Week 4:

* The first round of code reviews will be given out after the week 4 deadline. Check Labtool for a link to the repository to review. **The deadline for the first code review is the same as the week 5 deadline.**
* See instructions for code reviews [here](../peer_review/)
* Remember to enable issues for your repositories. See [enabling issues](../issues/)

* Submission 4: **<script>document.write(enString(timing["dl4"].date));</script>**
    * [Documentation](../documentation/): Written code is clear and commented. Started on testing and implementation documentation.
    * Week 4 report.
    * Program: Core functionality completed. Working on implementing data structures.
    * Testing: *Comprehensive* unit testing of the code. Started working on performance evaluation or similar applicable testing (write about these in the testing documentation).

# Week 5:

* The second round of code reviews will be given out after the week 5 deadline. Check Labtool for a link to the repository to review. **The deadline for the second code review is the same as the week 6 deadline.**

* Submission 5: **<script>document.write(enString(timing["dl5"].date));</script>**
   * **The first code review is completed**. (See [Labtool](https://studies.cs.helsinki.fi/labtool/) for link to repository)
   * [Documentations](../documentation/): Written code is clear and commented. Started on testing and implementation documentation.
   * Week 5 report.
   * Program: Core functionality of program is complete. Working on implementing data structures and algorithms.
   * Testing: *Comprehensive* unit testing of the code. Started working on performance evaluation or similar applicable testing.

# Week 6:

* Submission 6: **<script>document.write(enString(timing["dl6"].date));</script>**
   * **The first code review is completed**. (See [Labtool](https://studies.cs.helsinki.fi/labtool/) for link to repository)
   * [Documentation](../documentation/): Written code is clear and commented. Mostly done with testing and implementation documentation.
   * Week 6 report.
   * Program: Data structures and algorithms implemented from scratch.
   * Testing: *Comprehensive* unit testing of the code. Work done on performance evaluation or similar applicable testing.

# Demo session:

* <script>
  if (timing["demo"]) {
    document.write("Time and place: " + enEvent(timing["demo"]));
  } else {
    document.write("The exact time and date will be available later.")
  }
</script>
* You can either present using the class computer or by using your own laptop. Typically using your own laptop is recommended.
* A short approximately 5 minute presentation of your project and possibly some questions and answers.

# FINAL DEADLINE

**<script>document.write(enString(timing["end"].date));</script>**

* **Documentation:**
    * 100% clear and commented code. (If you are using Java, you should generate the Javadoc files and add or link them to your repository)
    * Done documentation:
         * Project definition (No need to update unless specifically requested)
         * Testing document
         * Implementation document
         * Weekly reports
         * User guide

* **Program:**
    * Preferable and executable program in [github releases](https://help.github.com/en/articles/creating-releases) (e.g. a JAR-file for Java)
    * All data structures and algorithms are created from scratch
    * Project is done and polished

* **Testing:**
    * *Comprehensive* unit testing of the code.
    * Testing that has been done has also been documented in the testing documentation.
    * A graphical depiction of performance based on empirical testing.
