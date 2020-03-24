# Title

* Evan Cole.
* Supervisors.
* Date

Many of the initial stumbling blocks for novice programmers can be overcome using custom languages and programming environments specialized for helping learners overcome key thresholds.  However these interventions are not practical or possible in many contexts.

Is it possible to achieve similar learning outcomes for adult learners outside of formal education by applying what is known of effective computing education by adapting/configuring industry-standard programming languages & environments for education?

### Contents

1. [Research Statement](#research-statement)
1. [Context](#context)
    * [Target Settings](#target-settings)
    * [Adapt the Existing](#adapt-the-existing)
    * [Fluid Roles](#fluid-roles)
    * [Quantify Adopt/Adapt-ability](#quantify-adoptadapt-ability)
1. [Literature Review](#literature-review)
1. [Objectives](#objectives)
1. [Research Methodology](#research-methodology)
1. [Potential Artifacts](#potential-artifacts)
1. [Doctoral Formation](#doctoral-formation)
1. [Bibliography](#bibliography)

---

## Research Statement

Much is already known about effective pedagogy for novice programmers, and many great resources, curricula, tools & learning environments have been developed to implement known best practices.   However there are very practical limitations to applying these interventions in many contexts outside of formal learning institutions, by non-specialized educators, or by learners themselves. 

The aim of this thesis is to explore whether the same understanding of effective pedagogy can be used to develop a suite of methodologies and supporting tools that enable learners to self-direct, non-specialized educators to teach computing, and experienced programmers to effectively transfer their knowledge outside of well-heeled formal institutions.

To this end it will be necessary to define a target context, and  understand in more detail what is preventing educators and learners from implementing existing artifacts or best practices.  This will include developing a viable measure of adopt/adapt-ability. Achieving this will expand our understanding of computing education from what is theoretically effective when applied correctly to a grounded understanding of how the theory can be practically applied in all settings.  

[TOP](#title)

---

## Context

Much is already known about effective pedagogy for novice programmers, and many great resources, curricula, tools & learning environments have been developed to implement known best practices. 

* _Curricula_: bootstrap, runestone academy, how to design programs, ...
* _Programming languages_: pyret, racket, configurable & language-leveled languages, ...
* _Teacher guides & resources_: teachtogether.tech, software carpentry, ...
* _Teaching & Study tools_: pythontutor.com, js-parsons library, ...
* _Programming environments_: thonny, alice, blockpy, pyret, blueJ, ...
* _Non-textual languages_: general purpose blocks, Scratch, BlockPy lego mindstorms, ...

These strategies/tools/techniques have led to improved learning outcomes in the settings and with the technologies studied.   However there are very practical limitations to applying these interventions in many contexts outside of formal learning institutions, by non-specialized educators, or by learners themselves.  Some of these constraints are related to the skills and experience of the individuals involved, while others are placed by the duration, objectives or resources available.  These include:

* entire curriculums are impractical to adapt to different needs
* a competent and experienced educator is often required for them to be applied correctly
* however informative a general guide may be, it is unrealistic for educators to apply learned practices because of constraints in time, technical, or competency
* many of these interventions are anticipated as the very beginning of (or part of) a full degree program
* they are often aimed at educators, but do not provide as much support for learners to guide their own learning
* they are not directly transferable to applied/professional contexts (custom environments/languages, ...)
* are generally limited to "learnable" programming languages (which are not necessarily the most current ones)

These limitations leave many of the best practices out of reach for (arguably) the majority of educational settings where "difficult" programming languages & environments are the learning goal, trainings must take place in under 1 year, and there is often much more professional competence than pedagogical competence available.

So, can a combination of pedagogical methodology and technical solutions be found that allow learners and peers/seniors/educators to apply the same understanding of effective programing pedagogy in their home settings and programming languages within their existing means? And if so, can the learning outcomes be comparable to the more controlled settings envisioned by most interventions?

### Target Settings

Many of the settings where theoretically sound interventions are impractical have severe time, resource and expertise constraints as well as far more narrow learning objectives than a standard degree program.  The settings of interest for this thesis are trainings outside of standard degree programs, aimed at learners aged 17/18+, of short duration (12 months or less), and geared towards applied computing skills. This type of learning is typically the domain of private professional courses, online video tutorials, on or off-line mentorship programs, on-the-job training, public schooling, self or peer-guided learning, or government provided trainings (among others).  

The aim of this thesis is to explore whether the same understanding of effective pedagogy can be used to develop a suite of methodologies and supporting tools that enable learners to self-direct, non-specialized educators to teach computing, and experienced programmers to effectively transfer their knowledge.

### Adapt the Existing

It is also interesting to explore if there are viable strategies for adapting existing languages and environments into effective novice learning environments rather than attempting to design "ideal" learning artifacts that must be treated separately from the target languages & environments. Besides practical considerations, this could be interesting for reducing loss of skill transfer as students transition from learning to professional programming environments.

### Fluid Roles

A feature that sets these contexts apart from the more commonly studied settings (academic institutions, or younger learners) is the more fluid roles taken on by all participants during the learning process. Often in the course of a single day, a single individual will need to take on most or even all of these roles.  To understand this dynamic, it is interesting to think of the roles that need to be supported rather than the individuals that will be taking on these roles:

* _the learner_: this role is taken on when someone's objective is to attain the objectives of the training
* _the companion_: taken on when someone is helping another to attain a course objective, but has not yet mastered the objective themselves
* _the teacher_: taken on when someone is helping another to attain a course objective, and has mastered the object
* _the overseer_: taken on when someone is assessing and tracking others' progress through the course objectives.  an individual will often take on the role of their own or a peer's overseer

It is hypothesized that for any methodology or tool to effectively reach the defined target settings, it must address each of these four roles on a more even footing and with a more similar message than is typically present in computing education resources.  All roles are taken on by engaged adults, and so a strong change in tone or medium should not be required (in contrast to ie. artifacts created for younger audiences).  

All actors will need a solid understanding of the same core principles of computing education, clearly and actionably stated:

1. What are key learning objectives & thresholds?
1. Which of these are reliably difficult to teach and learn?
1. What are effective and ineffective ways to reach these objectives?
1. How can mastery of these objectives be assessed and quantified?

The main difference in messaging for the four roles will be which actions to take at each point.  But as it is often the same individuals playing multiple roles, it should be more effective to provide a shared resource with the same core messaging and more specific actionable advice for each role - equally available to all individuals.

### Quantify Adopt/Adapt-ability

To validate any such intervention it is necessary to quantify not only student learning outcomes, but also how easily the intervention can be adopted & adapted by existing educational programs. (Keeping in mind that many roadblocks exist not at the teacher/student/classroom level, but at the institutional/administration/policy level.)

To this end it will be necessary to understand in more detail what is preventing educators from using existing artifacts (is it exposure? educational philosophy? time and resources? incompatibility between required & ideal curricula?).  After understanding the blocks, it will be necessary to find an objective measure of adopt/adapt-ability that can be used to determine which types of interventions are most practical for educators/learners to introduce into their classroom incrementally rather than as a whole-sale transformation.  

[TOP](#title)

---
## Literature Review

> this needs to be fleshed out and connected to citations

This literature review is structured to address an ordered list of 4 questions, which lay the ground works for the rest of this thesis:

### What are key threshold concepts & learning objectives for novice programmers?

This topic has been adequately covered in the literature for the purposes of this thesis.

* syntax & writing
  * visual complexity
  * syntactic rigidity
  * inconsistent syntax rules
  * language & pronunciation barriers
* dynamics of programming execution & memory
  * tracing lines in order of execution
  * source vs. runtime
  * function execution
  * variables
  * list comprehension
  * classes & instances
* computing & computers
  * computers have volition
* problem comprehension & addressing
  * matching language features to specific problems
  * generalizing solution patterns
  * identifying when a pattern is relevant
  * using pseudo-code
* program structuring
* reading and understanding code

### Which of these are most important for the context of this thesis?

All of them are important, and difficult to teach/learn or they wouldn't be the subject of research. But which are common across a wide variety of applied computing settings?  Which are least tied to a particular domain, programming language, or paradigm?  Narrowing down the list of thresholds and objectives using this criteria will help to find more general tools & methods which are more adaptable across different programming languages and environments.  

Another important consideration given the goals of this thesis is that many factors which are generally controlled for in computing education research are not controllable in the context of this thesis - the goal is to study how to learn & teach industry-standard languages+environments in context.

With that in mind, these concepts may the most interesting to pursue as a first step:

* program structuring
* syntax & writing
  * language & pronunciation barriers
* dynamics of programming execution & memory
  * tracing lines in order of execution
  * source vs. runtime
  * function execution
  * variables
* problem comprehension & addressing
  * matching language features to specific problems
  * generalizing solution patterns
  * identifying when a pattern is relevant
* reading and understanding code

### What are effective and ineffective methods for reaching these objectives?

Having an overview of what has worked to overcome these target objectives will be helpful to define specific avenues of research.

A more detailed understanding of what is _missing_ in successful learning languages+environments compared to industry-standard languages+environments will help.  It is likely that some of the lowest hanging fruit will be finding ways to intentionally configure or restrict certain pieces of a languages or environment to make them more similar to specialized learning environments.

> fill in details

An overview of successful methods for studying code (visualization tools, static study techniques, error message explanation, ...) is important to understand what minimal plugins or study tools may have the highest impact for the least overhead.

> fill in details

### How can mastery of these objectives be assessed and quantified?

There is already a body of research exploring how to evaluate novice programmers: identifying taxonomies, automated code assessment & feedback, which competencies to assess for at what stages in learning, how to design assessments for computing skills, to name a few. 

The open question in relation to this thesis is not how can a perfect assessment of programming skills be acquired in a controlled environment, but how can adequate and authentic assessment be achieved in an authentic setting.  And one step further, what methods of evaluation are easily adapted by educators or even administrable by learners themselves.  

[TOP](#title)

---

## Objectives

1. Specify and understand the target context in general
1. Identify specific participating organizations
1. Learn how they actually operate
1. Determine metrics of success in partnership with partner organizations
1. work with each organization to find the tools & methods that are easily and effectively integrated into their existing trainings.  Measure outcomes according to determined metrics as we go along.
1. attempt to generalize findings into a set of common guidelines, tools & resources for similar settings

[TOP](#title)

---

## Research Methodology

Design Research is the most appropriate methodology, it is best suited to research that seeks to extend an existing knowledge base through application and validation in novel settings.  The goal of this thesis is to apply what is known about effective computing education to finding a generalized method for adapting industry-standard languages & environments for educational purposes. 

Design research is made up of cycles.  These steps will be carried out repeatedly both at a small scale to develop individual artifacts, and a the scale of the thesis in an attempt to find a general methodology.

1. __Relevance__: Requirements & Field Testing
1. __Design Cycle__: Build & Evaluate
1. __Rigor Cycle__: Grounding & Knowledge Base Contributions

[TOP](#title)

---

## Potential Artifacts

To make the best practices the common practices, they must be the easiest to adopt/adapt.  Some possible artifacts to achieve this end include:

* Develop methodologies and accompanying tools for generating exercises & learning projects from existing code. These can be used by students or teachers to dive deeper into the challenges they actually encounter
* Granular open-source content (exercises, projects, lesson plans, ...) that can be incrementally adopted, and easily adapted.  These can either be used as-is or treated as exemplars for creating content more suited to different contexts.
* Accessibly open sourced tools that allow learners and educators to adapt their learning environments without the support of professional developers.
* Accessibly open sources tools for studying code from more perspectives than execution (ie. parsons problems, removing random lines/words, ...)
* Guidelines for curriculum creation/curation

Some possible avenues of investigation for adapting professional tools into learning environments include:

* Turning existing but common "challenging" languages into learnable languages using imposed language levels, this could be achieved using custom configurations of standard linting tools.  Different config files can be included in the same directory as assignments to allow tailor-made language constraints based on the assignment's objectives.
* Turning common IDE's (ie. visual studio code, brackets, sublime, or atom) into progressive learning environments using editor configurations that are shared with learners as certain thresholds are passed.
* Developing language support in professional IDE's for popular tailor-made novice languages
* Developing plugins for these editors that ...
  * ... provide novice-friendly visualizations of program execution
  * ... provide novice-friendly syntax highlighting & feedback
  * ... help learners interpret and act on error messages
  * ... provide language support for specialized novice-friendly languages, reducing transfer costs to eventually learning only a new language instead of a new language and environment
  * ... blockifying defined subsets of common languages directly in the editor, like Blockly or PencilCode.  This could go hand-in-hand with linting & styling configurations to reduce the blockifying complexity
  * ... enable students to study their code from more perspectives than execution (ie. switch to parsons mode and lines are shuffled, correctly replacing the lines will allow the student to continue developing)

[TOP](#title)

---

## Doctoral Formation

> TBD, possibly decided by masters requirements

[TOP](#title)

---

## Bibliography

> to be organized and cited correctly

```
lastName, I., lastName, I. and lastName, I. (year). title.  _journal_

a thesis - 
Gilligan, D. (1998). An Exploration of Programming by Demonstration in the Domain of Novice
Programming. Master’s thesis, School of Mathematics, Statistics and Computer Science, Victoria
University of Wellington.
```

Juha Sorva. (2012). Visual Program Simulation in Introductory Programming Education. _Doctoral Thesis, Department of Computer Science and Engineering, Aalto University_.

Sorva, Juha. (2013). Notional Machines and Introductory Programming Education. ACM Transactions on Computing Education. 13. 8:1-8:31. 10.1145/2483710.2483713. 

Van Merriënboer, J. J., Clark, R. E., & De Croock, M. B. (2002). Blueprints for complex learning: The 4C/ID-model. Educational technology research and development, 50(2), 39-61.

Robins, A., Rountree, J., & Rountree, N. (2003). Learning and teaching programming: A review and discussion. Computer science education, 13(2), 137-172.

Sorva, J. (2010, October). Reflections on threshold concepts in computer programming and beyond. In Proceedings of the 10th Koli calling international conference on computing education research (pp. 21-30).
  
Sorva, J., & Seppälä, O. (2014, November). Research-based design of the first weeks of CS1. In Proceedings of the 14th Koli Calling International Conference on Computing Education Research (pp. 71-80).

Sajaniemi, J. (2002, September). An empirical analysis of roles of variables in novice-level procedural programs. In Proceedings IEEE 2002 Symposia on Human Centric Computing Languages and Environments (pp. 37-39). IEEE.

Abdul-Rahman, S. S., & Du Boulay, B. (2014). Learning programming via worked-examples: Relation of learning styles to cognitive load. Computers in Human Behavior, 30, 286-298.

Shafto, P., & Goodman, N. (2008). Teaching games: Statistical sampling assumptions for learning in pedagogical situations. In Proceedings of the 30th annual conference of the Cognitive Science Society (pp. 1632-1637). Austin, TX: Cognitive Science Society.

Mead, J., Gray, S., Hamer, J., James, R., Sorva, J., Clair, C. S., & Thomas, L. (2006). A cognitive approach to identifying measurable milestones for programming skill acquisition. ACM SIGCSE Bulletin, 38(4), 182-194.

Atkinson, R. K., Derry, S. J., Renkl, A., & Wortham, D. (2000). Learning from examples: Instructional principles from the worked examples research. Review of educational research, 70(2), 181-214.

Gulikers, J. T., Bastiaens, T. J., & Kirschner, P. A. (2004). A five-dimensional framework for authentic assessment. Educational technology research and development, 52(3), 67.

Castro, F. E. V., & Fisler, K. (2017, November). Designing a multi-faceted SOLO taxonomy to track program design skills through an entire course. In Proceedings of the 17th Koli Calling International Conference on Computing Education Research (pp. 10-19).

Sheard, J., Carbone, A., Lister, R., Simon, B., Thompson, E., & Whalley, J. L. (2008, June). Going SOLO to assess novice programmers. In Proceedings of the 13th annual conference on Innovation and technology in computer science education (pp. 209-213).

Krone, J., Hollingsworth, J. E., Sitaraman, M., & Hallstrom, J. O. (2010). A reasoning concept inventory for computer science. Clemson University.

Goldman, K., Gross, P., Heeren, C., Herman, G., Kaczmarczyk, L., Loui, M. C., & Zilles, C. (2008, March). Identifying important and difficult concepts in introductory computing courses using a delphi process. In Proceedings of the 39th SIGCSE technical symposium on Computer science education (pp. 256-260).

Zeng, L., Kuang, S., Yang, L., Zhu, T., & Ding, X. (2010, May). Construction of Threshold Concept-Based Programming Courses Ontology. In 2010 International Conference on E-Business and E-Government (pp. 3849-3851). IEEE.

Santos, Á., Gomes, A., & Mendes, A. (2013, October). A taxonomy of exercises to support individual learning paths in initial programming learning. In 2013 IEEE Frontiers in Education Conference (FIE) (pp. 87-93). IEEE.

Whalley, J. L., Clear, T., Robbins, P., & Thompson, E. (2011). Salient elements in novice solutions to code writing problems.

Shih, Y. F., & Alessi, S. M. (1993). Mental models and transfer of learning in computer programming. Journal of Research on Computing in Education, 26(2), 154-175.

Ramalingam, V., LaBelle, D., & Wiedenbeck, S. (2004, June). Self-efficacy and mental models in learning to program. In Proceedings of the 9th annual SIGCSE conference on Innovation and technology in computer science education (pp. 171-175).

Bitzer, L. F. (1992). The rhetorical situation. Philosophy & rhetoric, 1-14.

Vatz, R. E. (1973). The myth of the rhetorical situation. Philosophy & rhetoric, 154-161.

Proulx, V. K. (2000). Programming patterns and design patterns in the introductory computer science course. ACM Sigcse Bulletin, 32(1), 80-84.

Guibert, Nicolas & Guittet, Laurent. (2005). A study of the efficiency of an alternative programming paradigm to teach the basics of programming. 

Reinfelds, J. (1995). A three paradigm first course for CS majors. ACM SIGCSE Bulletin, 27(1), 223-227.

Paas, F., Renkl, A., & Sweller, J. (2004). Cognitive load theory: Instructional implications of the interaction between information structures and cognitive architecture. Instructional science, 32(1/2), 1-8.

Davies, S. (2008, October). The effects of emphasizing computational thinking in an introductory programming course. In 2008 38th Annual Frontiers in Education Conference (pp. T2C-3). IEEE.

Zhu, H., & Zhou, M. (2003, October). Methodology first and language second: A way to teach object-oriented programming. In Companion of the 18th annual ACM SIGPLAN conference on Object-oriented programming, systems, languages, and applications (pp. 140-147).

Du Boulay, B., O'SHEA, T. I. M., & Monk, J. (1999). The black box inside the glass box: Presenting computing concepts to novices. International Journal of Human-Computer Studies, 51(2), 265-277.

Faux, R. (2006). Impact of preprogramming course curriculum on learning in the first programming course. IEEE Transactions on education, 49(1), 11-15.

Kelleher, C., & Pausch, R. (2005). Lowering the barriers to programming: A taxonomy of programming environments and languages for novice programmers. ACM Computing Surveys (CSUR), 37(2), 83-137.

Guzdial, M. (2004). Programming environments for novices. Computer science education research, 2004, 127-154.

Hevner, A., & Chatterjee, S. (2010). Design science research in information systems. In Design research in information systems (pp. 9-22). Springer, Boston, MA.

[TOP](#title)
