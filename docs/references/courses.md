# Ethics Courses: Review Notes

🔴 = Linked (relevance checked, no notes yet) <br/>
🟠 = Outlined (broad topics identified) <br/>
🟢 = Reviewed (deep dive provided) <br/>

> **REFERENCES: COURSES**

* 🟠 2021, [Data Science and Ethics](https://www.online.umich.edu/courses/data-science-ethics/) - _University of Michigan_, 4-week course, [`NOTES`](#❶-nbsp-data-science-and-ethics-2021) 
* 🟢 2021, [Data Science Ethics](https://datasciencebox.org/ethics.html) - _Github / DataScienceInABox_, OSS curriculum, [`NOTES`](#❷-nbsp-data-science-ethics-2021)
* 🟢 2021, [Fairness In Machine Learning](https://github.com/microsoft/ML-For-Beginners/blob/main/1-Introduction/3-fairness/README.md) - _GitHub / MLForBeginners_, OSS curriculum, [`NOTES`](#❸-nbsp-fairness-in-machine-learning-2021) 
* 🟠 2020, [Principles and Practices for Responsible AI](https://docs.microsoft.com/en-us/learn/paths/responsible-ai-business-principles/) - _Microsoft Learn_, training, [`NOTES`](#❻-nbsp-principles-and-practices-for-responsible-ai-2020)
* 🟠 2020, [Data Privacy and Ethics](https://web.stanford.edu/group/msande234/cgi-bin/wordpress/), _Stanford University_, syllabus+readings, [`NOTES`](#❹-nbsp-data-privacy-and-ethics-2020) 
* 🟠 2020, [Human Contexts & Ethics of Data](https://docs.google.com/document/d/1aRSkK0FmyaWCIsFq4MCbTrP2yGmP_rTPQ9MJLzdwWnc/edit), _UC Berkeley_, syllabus+readings, [`NOTES`](#❺-nbsp-human-contexts-amp-ethics-of-data-2020)

> **REFERENCES: BOOKS**

* 🟠 2020, [97 Things About Ethics everyone in DS Should Know](https://www.oreilly.com/library/view/97-things-about/9781492072652/) - _O'Reilly_, ebook, [`NOTES`](#❼-nbsp-97-things-about-ethics-everyone-should-know-2020) 
* 🟢 2019, [Ethics and Data Science](https://resources.oreilly.com/examples/0636920203964/)  _O'Reilly_, ebook, [`NOTES`](#❽-nbsp-ethics-and-data-science-2018) 


> **REVIEW NOTES**

### ❶ | &nbsp; [Data Science and Ethics](https://www.online.umich.edu/courses/data-science-ethics/) - 2021
_University of Michigan_, 4 weeks course

Also offered via [Coursera](https://www.coursera.org/learn/data-science-ethics/home/welcome) with the following lessons:
 * What are Ethics
 * History, Informed Consent
 * Data Ownership
 * Privacy
 * Anonymity
 * Data Validity
 * Algorithmic Fairness
 * Societal Consequences
 * Code of Ethics
 * References for Reading


---

### ❷ | &nbsp; [Data Science Ethics](https://datasciencebox.org/ethics.html) - 2021
_Github / DataScienceInABox_, OSS Curriculum

The curriculum has a [76-video playlist](https://www.youtube.com/user/bleue894) introduction to data science. The ethics section is covered in Week 7 with units 02, 03, and 04 respectively. Notes below.


**[`MISREPRESENTATION`](https://rstudio-education.github.io/datascience-box/course-materials/slides/u3-d01-misrepresentation/u3-d01-misrepresentation.html#1)** | [Video](https://www.youtube.com/watch?v=C_-rTKfswUI)

 * The way we present data influences perception
 * Causality - can we infer causality (if I do X, then Y happens)
 * Is that inferred causality _valid_ representation of the data?
 * Example: "exercises can lower risk of cancers by 20%"
    - nothing in the study showed control-vs-test group to validate
    - is there harm in making this causal connection? (Health)
    - correlation is NOT causation (don't over-reach)
 * Axes and Scale: Misrepresenting data by playing visualization games. _Presentation influences perception_. What story are you telling?
 * [15 Examples of Misleading Visualizations](https://rigorousthemes.com/blog/misleading-data-visualization-examples/)


**[`DATA PRIVACY`](https://rstudio-education.github.io/datascience-box/course-materials/slides/u3-d02-privacy/u3-d02-privacy.html#1)** | [Video](https://youtu.be/c4fvdoNbcSw)


**[`ALGORITHMIC BIAS`](https://rstudio-education.github.io/datascience-box/course-materials/slides/u3-d03-algorithmic-bias/u3-d03-algorithmic-bias.html#1)** | [Video](https://youtu.be/E2eD72pwtps)


**[`CASE STUDIES`](https://datasciencebox.org/ethics.html#slides-videos-and-application-exercises-2)** | On Misrepresentation, Privacy, Algorithmic Bias

- Misrpresentation: [How charts lie](https://youtu.be/Low28hx4wyk), _Alberto Cairo_
- Data Privacy: [Cambridge Analytica whistleblower](https://youtu.be/FXdYSQ6nu-M), _The Guardian_
- Algorithm Bias: [I'm fighting bias in algorithms](https://youtu.be/UG_X_7g63rY), _Joy Buolamwini_
- Algorithm Bias: [Weapons of Math Destruction](https://youtu.be/TQHs8SA1qpk), _Cathy O'Neil_
- Algorithm Bias: [Imagine a future free from algorithms of oppression](https://youtu.be/tNi_U1Bb1S0), _Safiya Umoja Noble_
- Algorithm Bias: [What's an Algorithm got to do with it?](https://youtu.be/5zxDwA99soA), _Kristian Lum_



---

### ❸ | &nbsp; [Fairness In Machine Learning](https://github.com/microsoft/ML-For-Beginners/blob/main/1-Introduction/3-fairness/README.md) - 2021
_GitHub / MLForBeginners_, OSS Curriculum

 * What happens when data models use non-representative data?
 * **Unfairness in data and algorithms**. Data can be manipulated to support any conclusion. Fairness is a complex socio-technical challenge. Unfairness encompasses negative impacts for a group (e.g., defined by age, race, gender, disability, etc.) or "harms" - main classifications of harm are:
    - `Allocation` = systematically allocating one group more resources than another (e.g., jobs, loans etc.)
    - `Quality of Service` = classifiers with higher error rates for specific groups (e.g., gender shades study, soap dispenser product)
    - `Stereotyping` = classifiers that have a higher bias towards a specific group (e.g., gender bias in turkish language translations)
    - `Denigration` = classifiers that mislabel specific groups in ways that end up reinforcing derogatory labels historically used for them
    - `Over or under representation` = algorithm results that over (or under) index results from a specific group (e.g., search engines with gender bias for leadership keywords)
    - **Takeaways:** Types of harm are not mutually exclusive. They can also have varying severity of consequences based on application context.
* **Detecting Unfairness.** Why does a system behave unfairly?
    - `Representation` = inadequate data for a given group
    - `Social Bias` = exacerbated by over-reliance on historical data
    - `Human Error` = wrong assumptions made during development
* **Understanding your models and build**. It's difficult to eliminate all bias (_guarantee_ fairness) but you are _responsible_ for taking actions to detect & mitigate unfairness. Different assessment methods are possible:
    - `Identify harms & benefits` - how do decisions impact org, users?
    - `Identify affected groups`- who is affected? what defines group?
    - `Define fairness metrics` - something to measure progress against
* **Mitigating Unfairness**
    - `Compare mitigated models` - compare tradeoffs, select best fit.
    - `Use relevant tools` - e.g, Fairlearn Python package from MSR.
* 🚀 Challenge: To prevent bias we should:
    - Have diversity of backgrounds
    - Invest in datasets that reflect diversity
    - Develop better anti-bias methodology
* Self-Study
* Assessment
 * **CTA** - [Principles of Responsible AI](https://docs.microsoft.com/learn/modules/responsible-ai-principles/) learning path


| | 
|--|
| _Sketchnote from Tomomi Imura summarizing this lesson._ |
| ![Sketchnote from Tomomi Imura summarizing the lesson](https://github.com/microsoft/ML-For-Beginners/raw/main/sketchnotes/ml-fairness.png) | 
| | 

---

### ❹ | &nbsp; [Data Privacy and Ethics](https://web.stanford.edu/group/msande234/cgi-bin/wordpress/) - 2020
_Stanford University_, syllabus and readings

A 10-week course (9 for lectures, 1 for presentations). While lectures were not available online, each section has a rich set of readings for understanding that topic, including references for case studies or research experiments. 

These are the topics covered each week:

 * 1 | Introduction 
 * 2 | Digital Exhaust & Privacy
 * 3 | Differential Privacy
 * 4 | Data Transparency
 * 5 | A/B Testing
 * 6 | Search Engines & Recommendation Systems
 * 7 | Personalization & Fingerprinting
 * 8 | Social Networks & Social Data
 * 9 | Privacy Regulation


---

### ❺ | &nbsp;  [Human Contexts & Ethics of Data](https://docs.google.com/document/d/1aRSkK0FmyaWCIsFq4MCbTrP2yGmP_rTPQ9MJLzdwWnc/edit) - 2020
_UC Berkeley_, syllabus & readings

 * 14 weeks, 8 units, 40 topics - _topics listed below for convenience_
 * Visit link above to get relevant readings for each unit/topic.
 * Unit 1: `Our datafied world`
    - 01: Welcome and overview: University education in a world of data
    - 02: Getting oriented in the datafied world -- Thinking in time 
    - 03: How the world was datafied -- historical overview and timeline
    - 04: Getting oriented in the datafied world -- STS analytical lenses 
    - 05: Data futures -- perspectives from past and present
    - 06: Who and What is data science?
    - 07: What makes data?
 * Unit 2: `Responsible data`
    - 08: Ethics and professional practice
    - 09: Responsible institutions and challenges
    - 10: Data ethics today -- what it is and how we got here
    - 11: Aiming for the 'good life' with data
    - 12: Co-producing technical and social order 
    - 13: What is Critique? Contradictions in Ethics Education
 * Unit 3: `When data is personal`
    - 14: Selfhood in the age of data and social media
    - 15: Personal origins of data
    - 16: Privacy 
    - 17: Analytics of human data
 * Unit 4: `Collective Life`
    - 18: Populations and states 
    - 19: Surveillance and security
    - 20: Predictive policing
    - 21: Making arguments with data
    - 22: Choice, influence, manipulation, and governance
    - 23: Algorithmic sentencing
 * Unit 5: `Data and democracy`
    - 24: Commercial content moderation
    - 25: Elections
    - 26: The Public Sphere in the Datafied World
    - 27: Expertise and democracy
    - 28: Data, algorithms, and the law
    - 29: Public witnessing and measuring
 * Unit 6: `Scientific Research `
    - 30: Transformations in the disciplines
    - 31: Transformations in the foundations of science
    - 32: Open Science/Open Software
 * Unit 7: `Machines and industry`
    - 33: Making Silicon Valley
    - 34: Industrial revolutions
    - 35: Environmental Contexts and Consequences of Data
    - 36: Transformations of labor
 * Unit 8: `The ethos of making`
    - 37: The tech workplace
    - 38: COVID in the Datafied world
    - 39: Making worlds together
    - 40: Recap: STS analytical lenses and thinking in time
---

### ❻ | &nbsp;  [Principles and Practices for Responsible AI](https://docs.microsoft.com/en-us/learn/paths/responsible-ai-business-principles/) - 2020
_Microsoft Learn_, training

 * [Learning Path](https://docs.microsoft.com/en-us/learn/paths/responsible-ai-business-principles/) = 3 modules, ~3 hours
 * Module 1: [Identify guiding principles for responsible AI](https://docs.microsoft.com/en-us/learn/modules/responsible-ai-principles/)
 * Module 2: [Identify governing practices for responsible AI](https://docs.microsoft.com/en-us/learn/modules/responsible-ai-governing-practices/)
 * Module 3: [Discuss practices for responsiblre AI at Microsoft](https://docs.microsoft.com/en-us/learn/modules/microsoft-responsible-ai-practices/)


---

### ❼ | &nbsp; [97 Things About Ethics everyone ... Should Know](https://www.oreilly.com/library/view/97-things-about/9781492072652/) - 2020
_O'Reilly_, e-book

**TABLE OF CONTENTS** (replicated from [online TOC](https://www.oreilly.com/library/view/97-things-about/9781492072652/) for convenience)

`I. Foundational Ethical Principles`

1. The Truth About AI Bias - Cassie Kozyrkov
2. Introducing Ethicize™, the fully AI-driven cloud-based ethics solution! - Brian T. O’Neill
3. “Ethical” Is Not a Binary Concept - Tim Wilson
4. Cautionary Ethics Tales: Phrenology, Eugenics,​...and Data Science?
Sherrill Hayes
5. Leadership for the Future: How to Approach Ethical Transparency - Rado Kotorov
6. Rules and Rationality - Christof Wolf Brenner
7. Understanding Passive Versus Proactive Ethics - Bill Schmarzo
8. Be Careful with “Decisions of the Heart” - Hugh Watson
9. Fairness in the Age of Algorithms - Anna Jacobson
10. Understand Who Your Leaders Serve - Hassan Masum

`II. Data Science and Society`

12. Unbiased ≠ Fair: For Data Science, It Cannot Be Just About the Math - Doug Hague
13. Trust, Data Science, and Stephen Covey - James Taylor
14. Ethics Must Be a Cornerstone of the Data Science Curriculum - Linda Burtch
15. Data Storytelling: The Tipping Point Between Fact and Fiction - Brent Dykes
16. Informed Consent and Data Literacy Education Are Crucial to Ethics - Sherrill Hayes
17. First, Do No Harm - Eric Schmidt
18. Why Research Should Be Reproducible - Stuart Buck
19. Build Multiperspective AI - Hassan Masum and Sébastien Paquet
20. Ethics as a Competitive Advantage - Dave Mathias
21. Algorithmic Bias: Are You a Bystander or an Upstander? - Jitendra Mudhol and  Heidi L. Eisips
22. Data Science and Deliberative Justice: The Ethics of the Voice of “the Other” - Robert J. McGrath
23. Spam. Are You Going to Miss It? - John Thuma
24. Is It Wrong to Be Right? - Marty Ellingsworth
25. We’re Not Yet Ready for a Trustmark for Technology - Hannah Kitcher and Laura James

`III. The Ethics of Data`

26. How to Ask for Customers’ Data with Transparency and Trust - Rasmus Wegener
27. Data Ethics and the Lemming Effect - Bob Gladden
28. Perceptions of Personal Data - Irina Raicu
29. Should Data Have Rights? - Jennifer Lewis Priestley
30. Anonymizing Data Is Really, Really Hard - Damian Gordon
31. Just Because You Could, Should You? Ethically Selecting Data for Analytics - Steve Stone
32. Limit the Viewing of Customer Information by Use Case and Result Sets - Robert J. Abate
33. Rethinking the “Get the Data” Step - Phil Bangayan
34. How to Determine What Data Can Be Used Ethically - Leandre Adifon
35. Ethics Is the Antidote to Data Breaches - Damian Gordon
36. Ethical Issues Are Front and Center in Today’s Data Landscape - Kenneth Viciana
37. Silos Create Problems—Perhaps More Than You Think - Bonnie Holub
38. Securing Your Data Against Breaches Will Help Us Improve Health Care - Fred Nugen

`IV. Defining Appropriate Targets & Appropriate Usage`

39. Algorithms Are Used Differently than Human Decision Makers - Rachel Thomas
40. Pay Off Your Fairness Debt, the Shadow Twin of Technical Debt - Arnobio Morelix
41. AI Ethics - Cassie Kozyrkov
42. The Ethical Data Storyteller - Brent Dykes
43. Imbalance of Factors Affecting Societal Use of Data Science - Nenad Jukić
44. Probability—the Law That Governs Analytical Ethics - Thomas Casey
45. Don’t Generalize Until Your Model Does - Michael Hind
46. Toward Value-Based Machine Learning - Ron Bodkin
47. The Importance of Building Knowledge in Democratized Data Science Realms - Justin Cochran
48. The Ethics of Communicating Machine Learning Predictions - Rado Kotorov
49. Avoid the Wrong Part of the Creepiness Scale - Hugh Watson
50. Triage and Artificial Intelligence - Peter Bruce
51. Algorithmic Misclassification—the (Pretty) Good, the Bad, and the Ugly - Arnobio Morelix
52. The Golden Rule of Data Science - Kris Hunt
53. Causality and Fairness—Awareness in Machine Learning - Scott Radcliffe
54. Facial Recognition on the Street and in Shopping Malls - Brendan Tierney

`V. Ensuring Proper Transparency & Monitoring`

55. Responsible Design and Use of AI: Managing Safety, Risk, and Transparency - Pamela Passman
56. Blatantly Discriminatory Algorithms - Eric Siegel
57. Ethics and Figs: Why Data Scientists Cannot Take Shortcuts - Jennifer Lewis Priestley
58. What Decisions Are You Making? - James Taylor
59. Ethics, Trading, and Artificial Intelligence - John Power
60. The Before, Now, and After of Ethical Systems - Evan Stubbs
61. Business Realities Will Defeat Your Analytics - Richard Hackathorn
62. How Can I Know You’re Right? - Majken Sander
63. A Framework for Managing Ethics in Data Science: Model Risk Management - Doug Hague
64. The Ethical Dilemma of Model Interpretability - Grant Fleming
65. Use Model-Agnostic Explanations for Finding Bias in Black-Box Models - Yiannis Kanellopoulos and Andreas Messalas
66. Automatically Checking for Ethics Violations - Jesse Anderson
67. Should Chatbots Be Held to a Higher Ethical Standard than Humans? - Naomi Arcadia Kaduwela
68. “All Models Are Wrong.” What Do We Do About It? - Miroslava Walekova
69. Data Transparency: What You Don’t Know Can Hurt You - Janella Thomas
70. Toward Algorithmic Humility - Marc Faddoul

`VI. Policy Guidelines`

71. Equally Distributing Ethical Outcomes in a Digital Age - Keyur Desai
72. Data Ethics—Three Key Actions for the Analytics Leader - John F. Carter
73. Ethics: The Next Big Wave for Data Science Careers? - Linda Burtch
74. Framework for Designing Ethics into Enterprise Data - Keri McConnell
75. Data Science Does Not Need a Code of Ethics - Dave Cherry
76. How to Innovate Responsibly - Carole Piovesan
77. Implementing AI Ethics Governance and Control - Steve Stone
78. Artificial Intelligence: Legal Liabilities amid Emerging Ethics - Pamela Passman
79. Make Accountability a Priority - Yiannis Kanellopoulos
80. Ethical Data Science: Both Art and Science - Polly Mitchell-Guthrie
81. Algorithmic Impact Assessments - Randy Guse
82. Ethics and Reflection at the Core of Successful Data Science - Mike McGuirk
83. Using Social Feedback Loops to Navigate Ethical Questions - Nick Hamlin
84. Ethical CRISP-DM: A Framework for Ethical Data Science Development - Collin Cunningham
85. Ethics Rules in Applied Econometrics and Data Science - Steven C. Myers
86. Are Ethics Nothing More than Constraints and Guidelines for Proper Societal Behavior? - Bill Schmarzo
87. Five Core Virtues for Data Science and Artificial Intelligence - Aaron Burciaga

`VII. Case Studies`

88. Auto Insurance: When Data Science and the Business Model Intersect - Edward Vandenberg
89. To Fight Bias in Predictive Policing, Justice Can’t Be Color-Blind - Eric Siegel
90. When to Say No to Data - Robert J. Abate
91. The Paradox of an Ethical Paradox - Bob Gladden
92. Foundation for the Inevitable Laws for LAWS - Stephanie Seward
93. A Lifetime Marketing Analyst’s Perspective on Consumer Data Privacy - Mike McGuirk
94. 100% Conversion: Utopia or Dystopia? - Dave Cherry
95. Random Selection at Harvard? - Peter Bruce
96. To Prepare or Not to Prepare for the Storm - Kris Hunt
97. Ethics, AI, and the Audit Function in Financial Reporting - Steven Mintz
98. The Gray Line - Phil Broadbent


---

### ❽ | &nbsp;  [Ethics and Data Science](https://resources.oreilly.com/examples/0636920203964/) -2018  
_O'Reilly_, ebook (free, 40 pages)

`TOPICS COVERED:`

  1. [Doing Good Data Science](_81-nbsp-doing-good-data-science) - what is ethics, why it matters
  2. [Of Oaths And Checklists](_82-nbsp-of-oaths-and-checklists) - oaths are abstract, checklists are concrete!
  3. [The 5C's Framework](_83-nbsp-the-five-cs) - consent, clarity, consistency, control, consequences!
  4. [Data's Day Of Reckoning](#_84-nbsp-data39s-day-of-reckoning) - ethics abuse, ethical principles & data-driven cultures!
  5. [Case Studies](#_85-nbsp-case-studies)


Setting the stage:

 * The Data-fied world = data integrated into all aspects of life
 * We gained some advantages but also seen damage from data misuse
 * Missing = methodology for putting ethics into practice
 * Ethics is not about agreeing on a set of principles. **It's about changing our behaviors and actions.** e.g. "agree to get permission from users" does not mean users understand consent, or how it works at web scale.
 * Ethics is not about fixed dos and don'ts. **It's about having discussions on doing harm vs. acceptable effects**

#### 8.1 &nbsp; [Doing Good Data Science](https://resources.oreilly.com/examples/0636920203964/blob/master/doing_good_data_science.md)

* Ethical data science is about `junction of ideas and practice.`
* [Defining fairness is difficult](https://www.oreilly.com/radar/the-problem-with-building-a-fair-system/) because it is subjective,aspirational, and multi-dimensional. De-biasing inputs may be a better approach than tweaking outputs (e.g., to compensate for historical biases). _What does fairness mean?_ - don't `mathwash` decisions.
* How do we design the user experience so that our concern for fairness
and ethics doesn't make an application unuseable
* To put ethical principles into practice, we need space to be ethical.  This involves the following facets:
    - Corporate Cultures where fairness discussions are considered
    - Thinking about unintended consequences of our use of data
    - Power to stop production line when something goes wrong (Toyota's Kanban)


#### 8.2 &nbsp; [Of Oaths and Checklists](https://resources.oreilly.com/examples/0636920203964/blob/master/of_oaths_and_checklists.md)

 * Analogy to Hippocratic Oath: Do No Harm
 * Analogy to "Code of Conduct": Useless unless clearly defined/enforced.
 * Oaths don't have problems
    - One-shots. Take them once and that's it. Nothing to reinforce or remind you regularly.
    - Generic. Tend to provide broad principles open to misinterpretation.
    - Cloaking. Provide people an illusion of compliance with no proof.
    - Disconnected. Nothing on how oath converts to real world practices.
 * Oaths can be dangerous. A tool we use to convince ourselves of good intent without looking too closely at what we do.
 * Value of oaths is the discovery process and discussion you go through when formulating the oath. 
 * Mistakes will happen. Oaths can't prevent that _but checklists can_.

🚨 **What does an ethics checklist look like?**

Examples: [UK Gov Ethics Framework ](https://www.gov.uk/government/publications/data-ethics-framework) identifies 7 principles and provides a workbook for data scientists to:

  * ✅ Ask open ended questions
  * ✅ Probe compliance against principles
  * ❌ Downside is execssive overheads (46 questions)
 

📋 **Proposal: 13-step checklist (goals: simple, effective)**

 * _DEFENSIBLE_: Can this technology  be attacked or abused?
 * _TESTED_: Is our data fair and representative?
 * _BIAS_: Have we studied & understood possible sources of bias?
 * _TEAM_: Does team reflect diversity of opinions, thought, backgrounds?
 * _CONSENT_: What kind of consent do we need, to collect & use data?
    - _PROCESS_: Do we have a mechanism for gathering user consent?
    - _CLARITY_: Have we clearly explained what user is consenting to?
 * _REDRESS_: Do we have mechanism for redress if people are harmed?
 * _KILL SWITCH_: Can we shut down production process if misbehaving?
 * _FAIRNESS_: Have we tested for fairness with different user groups?
 * _QOS_: Did we test for disparate error rates among different groups?
 * _MONITORING_: Do we test model for drift (over time) to ensure fairness?
 * _SECURE`: Do we have a plan to protect and secure user data?


#### 8.3 &nbsp;  The Five Cs
* What does it take to build a product or service RESPONSIBLY?
* Data is the new oil. But it's based on a MODEL OF TRUST.
* Once that's broken, how do we repair and regain user trust?
* We need guidelines: Ergo, the 5C's framework. Find and analyze examples of each in case studies.
    - CONSENT = was appropriate and necessary consent obtained?
    - CLARITY = did user really understand implications of consent?
    - CONSISTENCY = does org behavior build or break user trust?
    - CONTROL = is data usage transparent? does user have a say in it?
    - CONSEQUENCES = can data do harm? do we protect against it? ex: COPPA
* Even philanthropic intent can cause harm
    - Strava released anonymized activity data - reveal military info
    - AOL released anonymized search data - de-anonymization was easy
    - _Combining data sets_ may create opportunities for harm that individual dataset owners may not have considered (e.g., runner data combined with smart locks data = home unguarded, breakin easy)
    - _Public data sets_ have huge research value. What works = tighly controlled curation with analysis & mitigation of possible harm.
* Implementing the 5 Cs
    - Make 5Cs a cornerstone of product user experience design.
    - But responsibility extends to entire team to ask "What if?"
    - 5Cs need to be part of _organizational culture_ to be effective

#### 8.4 &nbsp; Data's Day of Reckoning

 * Products we create get ["weaponized"](https://en.wikipedia.org/wiki/Weapons_of_Math_Destruction#) against us
 * Tradeoffs in individual privacy, public good, corporate profit
 * Day of Reckoning. _What does it mean to take responsibility for our data collection-processing-usage creations?_
 * Case Studies in Abuse of Consent:
    - [Tuskegee Syphillis Experiment](https://en.wikipedia.org/wiki/Tuskegee_Syphilis_Study)
    - [Henrietta Lacks Cancer Cells](https://en.wikipedia.org/wiki/Henrietta_Lacks)
 * Result: Professional societies formed to define and enforce codes of conduct, government regulatory processes to govern data science work.

🏋🏽‍♀️ **Ethics and Security Training**

 * **Problem**: Ethics courses exist, but not tied to courses or projects.
 * **Result**: Theoretical knowledge, limited practical experience
 * **Needed**: Make ethics a _core_ part of any data science curriculum.
 * **Duality**: Ethics & security work in tandem (principles, practices)
 * **Quote**: from [2016 White House Report](https://obamawhitehouse.archives.gov/sites/default/files/whitehouse_files/microsites/ostp/NSTC/preparing_for_the_future_of_ai.pdf): _Ethical training for AI practitioners and students is a necessary part of the solution. Ideally, every student learning AI, computer science, or data science would be exposed to curriculum and discussion on related ethics and security topics. However, ethics alone is not sufficient. Ethics can help practitioners understand their
responsibilities to all stakeholders, but ethical training should be
augmented with technical tools and methods for putting good intentions
into practice by doing the technical work needed to prevent
unacceptable outcomes._

📋 **Developing Guiding Principles**

 * Ethics become an afterthought (bolted-on vs. built-in)
 * Checklists can solve this problem.
 * The [FAT/ML](https://www.fatml.org/) community identified [Principles for Accountable Algorithms & Social Impact Statement for Algorithms](https://www.fatml.org/resources/principles-for-accountable-algorithms)
    - Principles for Accountable Algorithms
        - Responsibility = pathways & owner for redress
        - Explainability = describe decisions in non-tech terms
        - Accuracy = identify, log & articulate errors (for mitigation)
        - Auditability = disclosure of information for reactive analysis
        - Fairness = reduce or mitigate unfairness across user groups
    - Social Impact Statement For Algorithms 
        - During design, pre-launch, and post-launch, stages of product development.
        - Define guiding questions for each principle (see [examples](https://www.fatml.org/resources/principles-for-accountable-algorithms))
        - Define initial steps to take, to address guiding questions
        - Example: RESPONSIBILITY
            - Guiding Questions: Who is responsible if users are harmed? What is the reporting/redress process? Who has the authority to make changes to algorithms at each stage?

💜 **Building Ethics into Data-Driven Cultures**

 * Individual responsibility is insufficient. Ethics needs to be ingrained in organizational culture.
 * Integrating security into corporate culture is easier - ex: bug bounty programs
 * Integrating ethics is harder - ask: who has power & control to make change at scale?
 * Ethical culture starts with empowering individuals - ex: Toyota [Andon](https://en.wikipedia.org/wiki/Andon_(manufacturing)) process
 * Enable issue escalation for remediation _without retaliation_ - ex: State Dept. Dissent channel 
 * Make an _ethical challenge_ part of hiring process (foster discussion)
 * Make product reviews ask questions about _product ethical impact_ (checklists)
 * Make _teams reflect diversity_ of thought, experiences, race, background (representation)
 * Make _corporate principles on ethics_ clear (guidelines & training)

👮🏽 **Regulation**

 * Ex: [Nuremberg Code](https://www.brandeis.edu/ora/hrpp/policies/nuremberg-code.html) - individual consent to participation in experiments.
 * Ex: [National Research Act](https://en.wikipedia.org/wiki/National_Research_Act) - regulate human experiences, response to [Tuskegee Syphillis Study](https://en.wikipedia.org/wiki/Tuskegee_Study_of_Untreated_Syphilis_in_the_Negro_Male)
 * Ex: [Common Rule - 1981](https://en.wikipedia.org/wiki/Common_Rule) - governs biomedical and behavioral human research, IRB formed
 * Ex: [GDPR - European Union](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation) - governs data use, protection and privacy.

🔮 **Building Our Future**

Summary: `We need to`
 * incorporate ethics into all aspects of technical education and corporate culture; 
 * give people the freedom to stop production if necessary, <br/>
 and to escalate concerns if they're not addressed; 
* incorporate diversity and ethics into hiring decisions; 
* consider regulation to protect the interests of individual users, and society as a whole.
* have difficult conversations on individual and collective responsiblity for data ethics

#### 8.5 &nbsp; Case Studies

**`PRINCETON DIALOGIES ON AI AND ETHICS`** released [6 case studies](https://aiethics.princeton.edu/case-studies/case-study-pdfs/)

Created a set of fictional case studies meant to spur discussion about issues at the intersection of AI and ethics: 

1. [Automated HealthCare App](https://aiethics.princeton.edu/wp-content/uploads/sites/587/2018/10/Princeton-AI-Ethics-Case-Study-1.pdf) = _smartphone app for diabetes_ </br> 
explore issues in paternalism, transparency, censorship, inequality.
2. [Dynamic Sound Identification](https://aiethics.princeton.edu/wp-content/uploads/sites/587/2018/10/Princeton-AI-Ethics-Case-Study-2.pdf) = _app recognizing voices_ </br> 
explore issues in rights, representation, harms, neutrality, downstream responsibility
3. [Optimizing Schools](https://aiethics.princeton.edu/wp-content/uploads/sites/587/2018/10/Princeton-AI-Ethics-Case-Study-3.pdf) = _finding at-risk children in school systems_ <br/>
explore issues in privacy, autonomy, consequentialism, rhetoric
4. [Law Enforcement Chatbots](https://aiethics.princeton.edu/wp-content/uploads/sites/587/2018/10/Princeton-AI-Ethics-Case-Study-4.pdf) = _tradeoffs in liberty, security, compliance with intl. laws_ <br/>
explore issues in automation, research ethics, sovereignty
5. [Hiring By Machine](https://aiethics.princeton.edu/wp-content/uploads/sites/587/2018/12/Princeton-AI-Ethics-Case-Study-5.pdf) = veterans-created open source social platform <br/>
_explore issues in fairness, diversity, irreconcilability, contextual integrity_
6. [Public Sector Data Analytics](https://aiethics.princeton.edu/wp-content/uploads/sites/587/2018/10/Princeton-AI-Ethics-Case-Study-6.pdf) = private consulting builds free public sector analytics solution <br/>
_issues in democracy, secrecy, inequality, fallibility, determinism_

There are no right and wrong answers - only understanding the boundaries and tradeoffs between what is acceptable and not.