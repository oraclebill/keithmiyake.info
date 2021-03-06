---
layout: single
title: All That is Digital Melts into Code
date: 2013-10-22 08:15:55.000000000 -07:00
type: post
published: true
status: publish
categories:
- Digital Humanities

tags:
- coding
- digital humanities
- modernity

author:
  login: kmiyake
  email: keith.miyake@gmail.com
  display_name: Keith Miyake
  first_name: Keith
  last_name: Miyake

excerpt: |
  Is 'coding' an essential skill for Digital Humanists? I argue that it depends on how you define code and propose a taxonomy for different tasks that might be considered 'coding' to show that code is not something to be feared.

featured:
  src: "/assets/img/code.jpg"
  alt: "All that is Digital Melts into Code"
  caption: "Code. Credit Michael Himbeault via Flickr"
  url: "https://www.flickr.com/photos/riebart/4466482623"
---

One of the [longstanding](http://miriamposner.com/blog/some-things-to-think-about-before-you-exhort-everyone-to-code/) [debates](http://aaronknoll.commons.gc.cuny.edu/on-technology/on-coding-in-the-digital-humanities/) [within](http://www.leeannghajar.com/i-code-you-code-we-code-why-code/) the [world](http://cac.ophony.org/2012/02/06/the-academic-call-to-code-and-the-networked-self/) of [Digital](http://www.hastac.org/blogs/cathy-davidson/2011/10/31/what-are-4-rs-essential-21st-century-learning) [Humanities](http://www.jamesgottlieb.com/2012/03/coding-and-digital-humanities/) is the question of "coding." I'm going to take a different approach—rather than insert myself into that particular debate, I want to explore the much more basic question, "What does it mean to 'code'?" I figure that since so many people entering DH seem to be concerned with the general assertion that one ought to, in some way, learn how to 'code', that it is perhaps even more important that people fully grasp what is meant by the term so that they can figure out what exactly it is that they are trying to learn. My general argument is that this thing called "code" is far too obfuscated to be the lynchpin of any debates. 

Borrowing from the recently passed Marshall Berman, I observe that "all that is digital (humanities) melts into code." For those modernists whose will to transform the world and society through massive infrastructural undertakings (think [Robert Moses](http://www.robertcaro.com/the-books/the-power-broker/) and [New York](http://www.temple.edu/tempress/titles/2252_reg_print.html)) a utopic vision of change is often confronted by "a terror of disorientation and disintegration, of life falling apart," consumed by "the thrill and the dread of a world in which 'all that is solid melts into air'"[[1](#fn1){:id="ret1"}]. 

Similarly, the world of DH is one in which lofty dreams and visions of the digital transforming the social are frequently confronted by the challenges of coding, the limitations of the real (i.e., the social), and the contradictions, perhaps fallacies, of modernity and modernization. This analogy lends caution to DH undertakings ignorant of the realities of implementation. But the second, more literal interpretation, is that all that is within the world of DH is somehow collapsed onto the aether or morass of "coding". Meaning that despite the realities of coding and implementation of DH projects, there is an assumed teleological link between project and coding. Without going into counterexamples of where this link breaks down, allow me to instead provide a brief clarification of the concept of 'coding' that I think underlies some of this confusion. 

## Abstracting "Coding" To Reach A Working Definition

At its most general level, to "code" is to put together abstract informational "input" in some form for the computer to decode, act on, and then produce output. To stretch this logic to an extreme level of abstraction, the series of mouse clicks and movements that allow you to open a web browser might be thought of as a very high-level form of coding. The "coder" produces inputs (mouse clicks and movements) that the computer decodes (what is the active window? what is the icon under the mouse pointer? how many times and how quickly was the mouse button pushed? etc.) resulting in new output (the web browser opens because the "coder" "double clicked" on the "location" associated with executing the web browser application). The language in this extreme instance is "Windows 7 Explorer" or "Mac OS X Finder". 

At the other end of the "coding" spectrum might be the task of designing the hardware and low-level software that interpret binary or assembly "code" into things like operations (addition, multiplication), conditional statements (if <em>x</em> is true then execute this chunk of code, otherwise go to the next chunk of code), loops (repeat this <em>n</em> times), and storage (save this chunk of information here and then retrieve that other chunk of information over there). Most of the stuff people think of when they hear the term "code" is somewhere in between these extremes.

The reason for casting such a wide net around the concept of "coding" is that getting a computer to do what you want is always, to some extent, about coding information into binary logic operations to generate new output from a given input. Obviously there are numerous layers of abstraction between high level coding such as mouse movements or HTML and computer processors. But by understanding all interactions with computers in terms of this process of coding, I want to emphasize that all of the work done with computers can be (overly) reduced to a process of "coding", and that there are different "languages" associated with every computer program.

{% include figure image_path="/assets/img/real_programmers.png" caption="Image via xkcd.org" alt="Real programmers set the universal constants at the start such that the universe evolves to contain the disk with the data they want." %}

## Coding Taxonomy

From this extremely broad understanding of coding, we can think of different categories of coding, from the highest level abstraction to the lowest hardware level bleep-blooping with digital circuits:

 * Coding as interacting with computer operating systems and graphical end-user applications. Input from the mouse/trackpad, keypresses, and operating system provided interfaces
 * Coding as using or interacting with programs that employ parametric commands. For example, using the terminal/command line/shell; [advanced Google searching](http://www.googleguide.com/advanced_operators_reference.html); command-based applications like Mathematica, Excel formulas, AutoCAD, etc. Input uses specific text- or symbol-based commands and requires some knowledge of the syntax and command structure.
 * Coding in a [markup language](http://en.wikipedia.org/wiki/Markup_language). Examples include HTML, XML, markdown, LaTeX, Postscript, etc. "Commands" consist of tags that allow for things like complex formatting and layout of text and graphics.
 * Coding as writing interpreted scripts. Examples include shell scripts, Applescript, Automator, .bat executables, etc.; Python, Javascript, BASIC, etc.; Matlab/Octave, ArcGIS scripting, etc. "Code" snippets are scripts that consist of a series of commands, often including functions, conditionals, loops, and different data types. The scripts require a separate program (the interpreter) to execute them.
 * Coding as programming applications using interpreted or compiled languages. Examples include web applications in Ruby, PHP, perl/cgi, Java, ASP, etc.; interpreted and bytecode-compiled languages like Python, Java, .Net, etc.; and compiled languages like C, Haskell, Lisp, Fortran, etc. Coding requires knowledge of the language syntax and usually more in-depth understandings of things like complex data types and objects, functions, classes, compiling/Make systems, and debugging.
 * Coding as writing hardware interfaces in assembly or compiled languages. Hardware-specific coding for developing lower level tools and drivers to interface with input/output devices. Also used for developing firmware, BIOS software, etc.
 * Coding as hardware design. "Coding" consists of designing electrical components to implement assembly commands (input) and "executing" those commands in terms of digital signals, and producing new sets of commands or output to other hardware components.

This is one possible taxonomy of different types of coding based on my own experience and knowledge of how different types of inputs are encoded, or translated, for a computer to interpret, transform, act upon, and produce outputs. There are plenty of exceptions and absences within this basic taxonomy, but hopefully this schematic demonstrates the really broad range of things that might fall into various categories of coding.

Critics will probably take issue with the first couple of items because there is little or no discernible "code" being generated. My contention is that at a heuristical level, there are too many continuities in working within these different categories to dismiss some of them, and also too many differences between those things traditionally considered coding (e.g., markup vs. compiled languages) to limit the categories.

## A Semi-Concrete Example

To take an example from DH, let's say that I want to analyze and visually display information related to NYPD stop-question-and-frisk. Assuming I already have a [handful](http://www.nyc.gov/html/nypd/html/analysis_and_planning/stop_question_and_frisk_report.shtml) of [datasets](http://www.nyclu.org/content/stop-and-frisk-data), my next step might be to figure out what tools will help me to sort through the data, create maps, perform geospatial statistics, etc. If you are familiar with statistical analysis or ethnographic research, you might already be thinking that one of the first steps before doing any of this is "coding" the data so that you can meaningfully use the qualitative components of these data with quantitative methods. For those unfamiliar, this might include assigning numerical categories to racial classifications, assigning geographical shapes to precinct numbers, or developing weighted values for increasing degrees of force used during stop-question-and-frisk incidents. 

This form of coding is essentially the same as other forms of "digital" coding. There is the need to translate informational input into some other form of information that is meaningful to the tool used in the next step of analysis, such as statistical algorithm. Once the data is coded, it can be given as input to my statistical program to produce output based on statistical algorithms.

If the statistical algorithms in the example above produce meaningful output, then that output can be used as the input to the next step, say visualization, and the coding process begins again. If the results from the statistical analysis were not sufficient for some reason, the algorithms or data might need to be adjusted. In this case, the adjusting is another layer of coding, requiring a related but probably more advanced skill set. That is to say, using regression analysis doesn't require a deep understanding of the statistical theory behind it. But to tweak specific variables or to modify the regression algorithm requires a slightly deeper or much deeper understanding of statistical theory, respectively. Similarly, using a statistics program to run the regressions for you only requires knowledge of how to enter data and run commands. But tweaking the data to work better within the program, or getting it to use an alternate algorithm instead of the built in regression options both require a deeper understanding of how the program works and subsequently, how to get it to do something not already available.

This deeper understanding doesn't require learning an entirely new skill set, it just requires the application of existing skills (using the program's basic commands and functionality) in more complex ways. In coding terms, this is like moving from an elementary school level of basic language comprehension to being able to converse or write in the new language. Just being able to use the program is like knowing enough key phrases in another language to get around and survive in a foreign country. Learning to converse or compose in that language means you have new possibilities for engaging with people and ideas. 

Taking this analogy with language further, the ways in which we interact with different computer programs or programming languages is a lot like our interactions with languages with similar etymological backgrounds. If one speaks English, they are likely to be able to figure out words or learn more quickly other Latin or Germanic based languages. In coding terms, if one can interact with a program based on Apple's user interface components, they can probably figure out other programs designed with those same interface components. If one knows basic HTML, then understanding any XML or markup-based code is like learning a new dialect or expanding one's vocabulary.

Returning to the previous example, the next step after statistical analysis might be to produce geospatial visualizations of the data and to use geospatial analysis to better understand the spatial relationships between data variables such as incident counts, racial characteristics, and clustering based on neighborhood income levels. Knowing how to plot data on a map is the most basic level of coding for this phase. It doesn't require deep knowledge of GISc, let alone any spatial statistics or geographical theory. It also doesn't require any "coding" knowledge other than how to use a simple mapping tool to convert database records into dots on a map. But if simply mapping points on a map isn't sufficient to the objectives of the research project, then additional knowledge of goegraphical theory and how to use more complex GISc tools and methods opens up a range of different possibilities for analysis and presentation, as well as new sets of questions that can be asked and potentially answered. 

So it's not just the complexity of the programs or how one interacts/codes within them, but entirely new ways of working with, manipulating, and understanding data that are revealed by diving deeper into the intricacies of using and coding with a set of tools. And if the theory precedes the capabilities of the tools, then developing new tools to accomplish the desired tasks might be that big scary next step that the researcher or developers need to take on next.

## Conclusion

This lengthy abstraction of the concept of "coding" serves multiple functions. First and foremost is to clear up some of the confusion surrounding the mystique of code. Second, I want to provide a framework for thinking about the diverse set of things that might fall under the umbrella of coding. Third, I want to emphasize that most of us are already engaging in various forms of coding without even realizing it, and thus, learning new languages and forms of coding might be approached the same way that we think about learning a new software package, a new version of Word, or even a new genre of reading.

Moving from one category of "coding" to another based on the taxonomy outlined above is almost always an involved learning process. And at some point, gaining an understanding of programming and computer science theory is necessary. But that doesn't mean that the first thing one has to do to learn how to "code" is to dive head-first into theory or learning the syntax of a specific language. 

Rather, thinking about coding as a continuum of skills, techniques, theories, and practices means that challenging oneself to learn a new set of tools specific to the types of research questions, interests, or novelties at hand is always about building a familiarity with new aspects of coding, interacting with data, and experiencing different theoretical approaches to computing. But the most important parts of learning how to code, like any other skill, are patience, practice, and lots of trial and error. 

So next time the question comes up, "How do I learn to code?" or "Do I need to code to be a Digital Humanist?" it might be helpful to approach the question not from a position within existing DH debates, but rather from the perspective of what skills does the person possess and what categories of coding do they fall into, and what might be a logical next step for building out that repertoire? 

## Notes

[[1](#ret1){:id="fn1"}] Berman, Marshall. 1988 (1982). *All That Is Solid Melts into Air*. New York: Penguin Books. pp 15.
