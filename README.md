# Open Computing Education: making the best practices the common practices

* Evan Cole
* Advisors: Benoît Vanderose & Bruno Dumas
* March 29, 2020

---

### Contents

1. [Research Statement](#research-statement)
1. [Context](#context)
1. [Objectives](#objectives)
1. [Research Methodology](#research-methodology)
1. [Possible Artifacts](#possible-artifacts)
1. [Doctoral Formation](#doctoral-formation)
1. [Bibliography](#bibliography)

---

## Research Statement

Much is already known about effective pedagogy for novice programmers, and many great resources, curricula, tools & learning environments have been developed to implement best practices.   However there are practical limitations to applying these interventions in many contexts outside of formal learning institutions, by non-specialized educators, or by learners themselves. 

The aim of this thesis is to explore whether the same understanding of effective pedagogy can be used to develop a suite of methodologies and supporting tools that enable learners to self-direct, non-specialized educators to teach computing, and experienced programmers to transfer their knowledge.

To this end it will be necessary to define a target context and understand in more detail what is preventing educators and learners from implementing existing artifacts or best practices.  Besides assessing student outcomes, this will require developing a viable measure of adopt/adapt-ability. Achieving this will expand our understanding of computing education from what is theoretically effective when applied correctly to a grounded understanding of how the theory can be practically applied in all settings.  

[TOP](#title)

---

## Context

Much is already known about effective pedagogy for novice programmers, and many great artifacts have been developed to implement known best practices. 

* _Curricula_: bootstrap, runestone academy, how to design programs, ...
* _Programming languages_: pyret, racket, configurable & language-leveled languages, ...
* _Teacher guides & resources_: teachtogether.tech, software carpentry, ...
* _Teaching & Study tools_: pythontutor.com, js-parsons library, ...
* _Programming environments_: thonny, alice, blockpy, pyret, blueJ, ...
* _Non-textual languages_: general purpose blocks, Scratch, BlockPy lego mindstorms, ...

These strategies/tools/techniques have led to improved learning outcomes in the settings and with the technologies studied.   However there are very practical limitations to applying these interventions in many contexts outside of formal learning institutions, by non-specialized educators, or by learners themselves.  Some of these constraints are related to the skills and experience of the individuals involved, while others are placed by the duration, objectives or available resources.  These include:

* entire curriculums are impractical to adapt to different needs
* a competent and experienced educator is often required for them to be applied correctly
* however informative a general guide may be, it is unrealistic for educators to apply learned practices because of constraints in time, technical, or competency
* many of these interventions are anticipated as the very beginning of (or part of) a full degree program
* they are often aimed at educators, but do not provide as much support for learners to guide their own learning
* they are not directly transferable to applied/professional contexts (custom environments/languages, ...)
* are generally limited to "learnable" programming languages (which are not necessarily the most current ones)

These limitations leave many of the best practices out of reach for (arguably) the majority of educational settings where challenging programming languages & environments are the learning goal, trainings must take place in under 1 year, and there is often much more professional than pedagogical competence available.

So, can a combination of pedagogical methodology and technical solutions be found that allow learners and peers/developers/educators to apply the same understanding of effective programing education in their contexts, within their existing means? And if so, can the learning outcomes be comparable to the more controlled settings envisioned by most research-driven interventions?

### Target Settings

Many of the settings where theoretically sound interventions are impractical have severe time, resource and expertise constraints as well as far more narrow learning objectives than a standard degree program.  The settings of interest for this thesis are trainings outside of standard degree programs, aimed at learners aged 17/18+ with or without strong english language skills, of short duration (12 months or less), and geared towards applied computing skills. This type of learning is typically the domain of private professional courses, online video tutorials, on or off-line mentorship programs, on-the-job training, public schooling, self or peer-guided learning, or government provided trainings (among others).  

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
1. Which of these are most important for the context of this thesis?
1. How can mastery of these objectives be assessed and quantified?
1. What are effective and ineffective ways to reach these objectives?

The main difference in messaging for the four roles will be which actions to take at each point.  But as it is often the same individuals playing multiple roles, it should be more effective to provide a shared resource with the same core messaging and more specific actionable advice for each role - equally available to all individuals.

### Quantify Adopt/Adapt-ability

To validate any such intervention it is necessary to quantify not only student learning outcomes, but also how easily the intervention can be adopted & adapted by existing educational programs. (Keeping in mind that many roadblocks exist not at the teacher/student/classroom level, but at the institutional/administration/policy level.)

To this end it will be necessary to understand in more detail what is preventing educators from using existing artifacts (is it exposure? educational philosophy? time and resources? incompatibility between required & ideal curricula?).  After understanding the blocks, it will be necessary to find an objective measure of adopt/adapt-ability that can be used to determine which types of interventions are most practical for educators/learners to introduce into their classroom incrementally rather than as a whole-sale transformation.  

---

## Objectives

### Specify and understand the target context in general

* What types of educational settings are currently not well-served by existing research-based methodologies and artifacts? Why are existing solutions not applicable? What do they have in common?
* Answering questions like these will make it possible to narrow focus of the thesis and identify research subjects.  Ideally this would result in a questionnaire that could be used by the researchers to find subjects, and later could be used by organizations themselves to understand if the results of this thesis are applicable for them.

### Identify specific participating organizations

* Using the profile determined above, find several organizations and institutions that would be willing to participate.  Candidates include government-sponsored formations, non-profit coding schools, isolated programming courses offered outside of Computer Science Departments, self-study meetup groups, internal training departments, ...
* Partner organizations will be randomly separated throughout the research and design process.  Some will play the role of active design partners, while others will serve as "control" to test the generality of designed artifacts.  This will take place in smaller cycles at the scale of individual artifacts, and at the scale of the entire research project to test the validity of the final group

### Determine partner organizations' educational needs

* _What is the target student profile? What are the final learning objectives?_  What background knowledge and experience can be expected from incoming students?  What competencies should an outgoing student have?  To over simplify matters, the rest of thesis is just finding the most efficient path from A to B.
* _What are key threshold concepts encountered by their students?_ Existing research has identified many learning objectives that predictably cause trouble for students and are tricky to teach.  However, some of these will be more or less relevant depending on the backgrounds of incoming students, the languages/paradigms/environments taught, and the ultimate objectives of the course.
* _What can and cannot be controlled?_  By design, this thesis is addressing educational settings with different constraints than are often addressed by computing education. The goal is to find low-barrier optimizations that do not fundamentally change the objectives of a training. ie. A first line of attack to improve student outcomes might be to switch to a more amenable language or programming environment, however this is not an option for short-duration trainings looking to quickly re-skill adult learners.  Other existing interventions are off the table because they are forseen as the first introduction to a full diploma in computer science, rather than being integrated into a crash-course in applied software development.

### Determine metrics of success in partnership with partner organizations

* _How can mastery of identified learning objectives be assessed and quantified?_  The open question in relation to this thesis is not how can a perfect assessment of programming skills be acquired in a controlled environment, but how can adequate and authentic assessment be achieved in an authentic setting.  This step will require a lot of field work and iteration, validating what is already known about assessment (appropriate taxonomies, automated code assessment/feedback, which competencies to assess for at what stages in learning, and how to design authentic assessments, ...) against the realities of each setting.  An interesting and relevant contribution to the literature on assessment in computing education would be to identify methods of evaluation are easily adapted by educators or even administrable by learners themselves.
* _What traits make an artifact easily accessed and adaptable?_  It is not enough for something to work in the exact setting it is designed for.  If the best practices are to become the common practices, it needs to be within the practical constraints of educators and students to adapt an artifact to changing needs and contexts.  To validate the adopt/adaptability of any research artifacts, it will be necessary to work with teachers and students to determine their constraints (technical skills, resources, time, effort/reward thresholds, ...).

### Design effective tools & methodologies matched to each organizations' needs

* _What are effective and ineffective methods for reaching these objectives?_  Working in partnership with the students, teachers and administrators, design custom methodologies and tools that allow them to apply known best practices within their existing constraints.  All tested artifacts will be informed by known best practices and traits of previously successful artifacts, and validated against the pre-defined assessment metrics for student learning outcomes and adopt/adaptability. It is likely that some of the lowest hanging fruit will be finding ways to intentionally configure or restrict certain pieces of a languages or environment to make them more similar to specialized learning environments.

### Generalize & validate findings

* _How can the specific solutions found with partner organizations be generalized?_   What combination of guidelines, methodologies, tools and/or educational resources will enable other educational programming matching the target profile (described at the out start of this thesis) to make the best practices their common practices?
* To have confidence in generality, a validation phase will be carried out with partner organizations that were initially assigned to the "control group".  They will be asked to adopt/adapt the new artifacts into their existing trainings. The ease with this transition is achieved and any changes in student learning outcomes will be measured.

### Theoretical Contribution

* The results of this thesis will be analyzed and integrated into the existing body of knowledge pertaining to novice computing education.

---

## Research Methodology

Design Research is the most appropriate methodology, it is best suited to research that extends an existing knowledge base through application and validation in novel settings.  The goal of this thesis is to apply what is known about effective computing education to finding a generalized method for adapting industry-standard languages & environments for educational purposes. 

Design research is made up of cycles. These steps will be carried out repeatedly both at a small scale to develop individual artifacts, and a the scale of the thesis in an attempt to find a generalized methodology: 

1. Relevance: Requirements & Field Testing
2. Design Cycle: Build & Evaluate
3. Rigor Cycle: Grounding & Knowledge Base Contributions

Furthermore, the stages of research described in __Objectives__ are in direct alignment with the 7 established Design Science Research Guidelines as laid out by _Hevner, A., & Chatterjee, S. (2010)_.

---

## Possible Artifacts

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

The proposed courses were selected to develop a deeper understanding of education, the design of computing systems, and data science (with the intent of designing educational resources for the domain).  Selected conferences are focused on computing education, this list will expand and become more specialized as the thesis becomes more clearly defined.

### Informatics Courses

* Ingénierie du logiciel et laboratoire (INFOM114): _10 ECTS_
* Visualisation de l'information (IDASM103): _4 ECTS_
* Machine learning et data mining (IDASM102): _6 ECTS_
* Graph mining (SDASM101): _5 ECTS_
* Calculabilité et complexité (INFOM113): _5 ECTS_
* Projet interdisciplinaire (IDASM104): _5 ECTS_

### Cross-Disciplinary Courses

* Psychopédagogie I (FAGRM402): _4 ECTS_
* Psychopédagogie II (FAGRM406): _3 ECTS_

### Scientific Activities

* Domain conferences (ICER, ITiCSE, SIGCSE, FIE, Koli Calling, etc.): _15 ECT_
* Confirmation: _5 ECTS_
* Private Defense: _5 ECTS_
* Public Defense: _5 ECTS_

---

## Bibliography

1. Abdul-Rahman, S. S., & Du Boulay, B. (2014). Learning programming via worked-examples: Relation of learning styles to cognitive load. Computers in Human Behavior, 30, 286-298.
1. Atkinson, R. K., Derry, S. J., Renkl, A., & Wortham, D. (2000). Learning from examples: Instructional principles from the worked examples research. Review of educational research, 70(2), 181-214.
1. Bitzer, L. F. (1992). The rhetorical situation. Philosophy & rhetoric, 1-14.
1. Castro, F. E. V., & Fisler, K. (2017, November). Designing a multi-faceted SOLO taxonomy to track program design skills through an entire course. In Proceedings of the 17th Koli Calling International Conference on Computing Education Research (pp. 10-19).
1. Cummings, R. E. (2006). Coding with power: Toward a rhetoric of computer coding and composition. Computers and Composition, 23(4), 430-443.
1. Du Boulay, B., O'SHEA, T. I. M., & Monk, J. (1999). The black box inside the glass box: Presenting computing concepts to novices. International Journal of Human-Computer Studies, 51(2), 265-277.
1. Davies, S. (2008, October). The effects of emphasizing computational thinking in an introductory programming course. In 2008 38th Annual Frontiers in Education Conference (pp. T2C-3). IEEE.
1. Faux, R. (2006). Impact of preprogramming course curriculum on learning in the first programming course. IEEE Transactions on education, 49(1), 11-15.
1. Finavaro Aniche, M., Hermans, F. F. J., & van Deursen, A. (2019). Pragmatic software testing education. In SIGCSE 2019-Proceedings of the 50th ACM Technical Symposium on Computer Science Education. Association for Computing Machinery (ACM).
1. Gulikers, J. T., Bastiaens, T. J., & Kirschner, P. A. (2004). A five-dimensional framework for authentic assessment. Educational technology research and development, 52(3), 67.
1. Goldman, K., Gross, P., Heeren, C., Herman, G., Kaczmarczyk, L., Loui, M. C., & Zilles, C. (2008, March). Identifying important and difficult concepts in introductory computing courses using a delphi process. In Proceedings of the 39th SIGCSE technical symposium on Computer science education (pp. 256-260).
1. Guibert, Nicolas & Guittet, Laurent. (2005). A study of the efficiency of an alternative programming paradigm to teach the basics of programming. 
1. Guzdial, M. (2004). Programming environments for novices. Computer science education research, 2004, 127-154.
1. Hevner, A., & Chatterjee, S. (2010). Design science research in information systems. In Design research in information systems (pp. 9-22). Springer, Boston, MA.
1. Krone, J., Hollingsworth, J. E., Sitaraman, M., & Hallstrom, J. O. (2010). A reasoning concept inventory for computer science. Clemson University.
1. Kelleher, C., & Pausch, R. (2005). Lowering the barriers to programming: A taxonomy of programming environments and languages for novice programmers. ACM Computing Surveys (CSUR), 37(2), 83-137.
1. Mead, J., Gray, S., Hamer, J., James, R., Sorva, J., Clair, C. S., & Thomas, L. (2006). A cognitive approach to identifying measurable milestones for programming skill acquisition. ACM SIGCSE Bulletin, 38(4), 182-194.
1. Proulx, V. K. (2000). Programming patterns and design patterns in the introductory computer science course. ACM Sigcse Bulletin, 32(1), 80-84.
1. Paas, F., Renkl, A., & Sweller, J. (2004). Cognitive load theory: Instructional implications of the interaction between information structures and cognitive architecture. Instructional science, 32(1/2), 1-8.
1. Robins, A., Rountree, J., & Rountree, N. (2003). Learning and teaching programming: A review and discussion. Computer science education, 13(2), 137-172.
1. Ramalingam, V., LaBelle, D., & Wiedenbeck, S. (2004, June). Self-efficacy and mental models in learning to program. In Proceedings of the 9th annual SIGCSE conference on Innovation and technology in computer science education (pp. 171-175).
1. Reinfelds, J. (1995). A three paradigm first course for CS majors. ACM SIGCSE Bulletin, 27(1), 223-227.
1. Sorva, J. (2012). Visual program simulation in introductory programming education. Aalto University.
1. Sorva, J. (2010, October). Reflections on threshold concepts in computer programming and beyond. In Proceedings of the 10th Koli calling international conference on computing education research (pp. 21-30).
1. Sorva, J., & Seppälä, O. (2014, November). Research-based design of the first weeks of CS1. In Proceedings of the 14th Koli Calling International Conference on Computing Education Research (pp. 71-80).
1. Sajaniemi, J. (2002, September). An empirical analysis of roles of variables in novice-level procedural programs. In Proceedings IEEE 2002 Symposia on Human Centric Computing Languages and Environments (pp. 37-39). IEEE.
1. Shafto, P., & Goodman, N. (2008). Teaching games: Statistical sampling assumptions for learning in pedagogical situations. In Proceedings of the 30th annual conference of the Cognitive Science Society (pp. 1632-1637). Austin, TX: Cognitive Science Society.
1. Sheard, J., Carbone, A., Lister, R., Simon, B., Thompson, E., & Whalley, J. L. (2008, June). Going SOLO to assess novice programmers. In Proceedings of the 13th annual conference on Innovation and technology in computer science education (pp. 209-213).
1. Santos, Á., Gomes, A., & Mendes, A. (2013, October). A taxonomy of exercises to support individual learning paths in initial programming learning. In 2013 IEEE Frontiers in Education Conference (FIE) (pp. 87-93). IEEE.
1. Shih, Y. F., & Alessi, S. M. (1993). Mental models and transfer of learning in computer programming. Journal of Research on Computing in Education, 26(2), 154-175.
1. Sorva, Juha. (2013). Notional Machines and Introductory Programming Education. ACM Transactions on Computing Education. 13. 8:1-8:31. 10.1145/2483710.2483713. 
1. Swidan, A., & Hermans, F. (2019, May). The Effect of Reading Code Aloud on Comprehension: An Empirical Study with School Students. In Proceedings of the ACM Conference on Global Computing Education (pp. 178-184).
1. Tondeur, J., Van Braak, J., & Valcke, M. (2007). Curricula and the use of ICT in education: Two worlds apart?. British Journal of Educational Technology, 38(6), 962-976.
1. Vatz, R. E. (1973). The myth of the rhetorical situation. Philosophy & rhetoric, 154-161.
1. Van Merriënboer, J. J., Clark, R. E., & De Croock, M. B. (2002). Blueprints for complex learning: The 4C/ID-model. Educational technology research and development, 50(2), 39-61.
1. Whalley, J. L., Clear, T., Robbins, P., & Thompson, E. (2011). Salient elements in novice solutions to code writing problems.
1. Zeng, L., Kuang, S., Yang, L., Zhu, T., & Ding, X. (2010, May). Construction of Threshold Concept-Based Programming Courses Ontology. In 2010 International Conference on E-Business and E-Government (pp. 3849-3851). IEEE.
1. Zhu, H., & Zhou, M. (2003, October). Methodology first and language second: A way to teach object-oriented programming. In Companion of the 18th annual ACM SIGPLAN conference on Object-oriented programming, systems, languages, and applications (pp. 140-147).
