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
1. [Deliverables](#deliverables)
1. [Doctoral Formation](#doctoral-formation)
1. [Bibliography](#bibliography)

---

## Research Question

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

```
// comments from Bruno: methodology can be inherited eg from Design Science
// check http://content.schweitzer-online.de/static/catalog_manager/live/media_files/representation/zd_std_orig__zd_schw_orig/014/341/402/9781441956521_content_pdf_1.pdf p. 16 bottom
// -> assess environment, elicit problems (relevance cycle), build design artefacts and evaluate them (design cycle), ground the whole think (rigor cycle). 
```

[TOP](#title)

---

## Deliverables

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

1. sorva dissertation 
  http://lib.tkk.fi/Diss/2012/isbn9789526046266/isbn9789526046266.pdf
2. sub-dissertation: 
  https://www.researchgate.net/publication/259998496_Notional_Machines_and_Introductory_Programming_Education?enrichId=rgreq-ba5f8eda195ab50b8438b8c1e9089f9e-XXX&enrichSource=Y292ZXJQYWdlOzI1OTk5ODQ5NjtBUzoyNDI3NzEwMTM0MDI2MjVAMTQzNDg5MjUyODU2MA%3D%3D&el=1_x_3&_esc=publicationCoverPdf
3. 4C/ID - Kirschner &  Van Merriënboer
  https://www.4cid.org/about-4cid
4. Learning and Teaching Programming: A Review and Discussion - Robins
  http://www.science.smith.edu/classwiki/images/1/14/RobinsRev.pdf
5. reflecitons on threshold concepts
  https://dl.acm.org/citation.cfm?id=1930467
6. research based design of the first weeks of cs1
  https://www.researchgate.net/profile/Juha_Sorva/publication/271214535_Research-based_Design_of_the_First_Weeks_of_CS1/links/5586b7f008aeb0cdaddfffcb.pdf
7. roles of variables
  http://jite.org/documents/Vol6/JITEv6p407-423Sorva280.pdf
8. Learning programming via worked-examples: Relation of learning styles to cognitive load    
  https://pdfs.semanticscholar.org/2f8d/ec5882c086cf83886369b580e20e8a140ad8.pdf
9. pedagogical samplings
  https://web.stanford.edu/~ngoodman/papers/pedagogicalSampling.pdf
10. A Cognitive Approach to Identifying Measurable Milestones for Programming Skill Acquisition
  https://www.researchgate.net/profile/John_Hamer/publication/220612781_A_cognitive_approach_to_identifying_measurable_milestones_for_programming_skill_acquisition/links/0912f50752474a84a1000000.pdf
11. a great lit-review on teaching intro programming
	http://130.216.33.163/courses/compsci747s2c/lectures/robins-learning-cse-03.pdf
12. worked examples
  http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.115.1348&rep=rep1&type=pdf
13. kirschner, 5 dimensional authentic assessment
  https://link.springer.com/article/10.1007/BF02504676
14. Designing a Multi-Faceted SOLO Taxonomy to Track ProgramDesign Skills Through an Entire Course
15. Going SOLO to assess novice programmers
16. concept inventory 1
  https://www.cs.clemson.edu/resolve/research/reports/RSRG-10-01.pdf
17. concept inventory 2
  http://zilles.cs.illinois.edu/papers/delphi.sigcse2008.pdf
18. Construction of Threshold Concept-Based Programming Courses Ontology
19. A taxonomy of exercises to support individual learning paths in initial programming learning
20. Salient elements in novice solutions to code writing problems
21. Mental models and transfer of learning in computer programming
  https://www.tandfonline.com/doi/abs/10.1080/08886504.1993.10782084
22. Self-Efficacy & mental models in computer programming
  https://dl.acm.org/citation.cfm?id=1008042
23. The rhetorical situation
  http://sites.psu.edu/fa2014vicarocas201/wp-content/uploads/sites/15238/2014/08/40236733.pdf
24. myth of rhetorical situation
  https://www.jstor.org/stable/40236848?seq=1
25. Programming Patterns and Design Patterns in the Introductory Computer Science Course (oop)
  http://www.ccs.neu.edu/home/vkp/Papers/Patterns-sigcse2000.pdf
26. visual paradigms: alternative for learning
  https://www.researchgate.net/profile/Laurent_Guittet/publication/242271658_A_study_of_the_efficiency_of_an_alternative_programming_paradigm_to_teach_the_basics_of_programming/links/55f5327d08ae7a10cf8901da.pdf
27. 3-paradigm cs intro course
  https://dl.acm.org/doi/abs/10.1145/199691.199792
28. Cognitive Load Theory: Instructional Implications of the Interaction between Information Structures and Cognitive Architecture
  https://pdfs.semanticscholar.org/bdb4/8e811cdedf40307bc3c84017bc3484153a8b.pdf
29. The effects of emphasizing computational thinking in an introductory programming course
  http://archive.fie-conference.org/fie2008/papers/1220.pdf
30. paradigm before language: c++
  https://dl.acm.org/doi/10.1145/949344.949389
31. the black box inside the glass box
  The black box inside the glass box: presenting computing concepts to novices
32. Impact of preprogramming course curriculum on learning in the first programming course
  https://ieeexplore.ieee.org/abstract/document/1593866
33. Lowering the Barriers to Programming: a survey of programming environments and languages for novice programmers 
  https://www.cs.cmu.edu/~caitlin/papers/NoviceProgSurvey.pdf
34. Programming Environments for Novices
  http://coweb.cc.gatech.edu/mediaComp-plan/uploads/37/novice-envs2.pdf


[TOP](#title)
