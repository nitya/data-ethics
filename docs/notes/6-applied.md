## 6. Applied Ethics

[Back to TOC](/?id=table-of-contents)

We've talked about the various challenges, consequences and case studies related to ethical concepts. But how do we put these ideas into practice for real-world application?

### 6.1 Ethics Questions

The first step is to get into the habit of asking the right questions about every stage in your big data or AI development process. These [6 questions about data science ethics](https://halpert3.medium.com/six-questions-about-data-science-ethics-252b5ae31fec) are a good start for any discussion:

 * Is the data you're collecting _fair and unbiased_?
 * Is the data _being used_ ethically and fairly? 
 * Is _user privacy_ being protected?
 * To whom does _data belong_ - the company or the user?
 * What _effects_ do the data and algorithms have on society (individual and collective)?
 * Is the data _manipulated or deceptive_?

For larger teams or processes, you can expand on questions to reflect the _stage_ of development. For instance [this article](https://medium.com/the-organization/22-questions-for-ethics-in-data-and-ai-efb68fd19429) identifies 22 questions organized into 3 categories: _design_, _implementation & management_, _systens & organization_ - allowing  teams to dive deeper into issues relevant to their stage. 


`Assignment:` Think about a use case you want to explore for a data ethics case study. Can you answer the above questions? Revisit the [Ethical Challenges](3-challenges.md) section - does it give you ideas for more questions?

### 6.2 Ethics Checklists

Once you've identified questions (and decided what's right or wrong), the next step is ensure that these ethical principles are _implemented_ in the development workflow. 

Oaths and professional codes of conduct have been advocated for this purpose, putting the responsibility on the _practitioners_ (data scientists and developers) to follow ethical practices. While these have value, they [also have limitations](https://resources.oreilly.com/examples/0636920203964/blob/master/of_oaths_and_checklists.md) particularly in large-scale deployments and organizations. Instead, practitioners (see [Ethics and Data Science](https://resources.oreilly.com/examples/0636920203964/blob/master/of_oaths_and_checklists.md)) advocate for _checklists_ that **connect the principle to practice** in actionable ways. 

Checklists convert questions into "yes/no" tasks that can be tracked and validated before product release. Tools like [deon](https://deon.drivendata.org/) make this frictionless, creating default checklists aligned to [industry recommendations](https://deon.drivendata.org/#checklist-citations) and enabling users to customize and integrate them into workflows using a command-line tool. Deon also provides [real-world examples](ttps://deon.drivendata.org/examples/) of ethical challenges to provide context for these decisions.

`Assignment:` Explore the [Deon Data Science Ethics Checklist](https://deon.drivendata.org/#data-science-ethics-checklist). Which items apply to your use case?


### 6.3 Responsible AI

Checklists help with data science projects at individual and team levels. But as AI becomes democratized, organizations need to define and adopt _governance frameworks_ to ensure that it's used responsibly. Today, many organizations have defined such initiatives including  [*Microsoft*](https://www.microsoft.com/en-us/ai/responsible-ai), [IBM](https://www.ibm.com/cloud/learn/ai-ethics), [Google](https://ai.google/principles) and [Facebook](https://ai.facebook.com/blog/facebooks-five-pillars-of-responsible-ai/). These initiatives typically define _principles_ for responsible AI and provide _resources_ to make adoption easier.

`Example:` [Microsoft: Responsible AI](https://www.microsoft.com/en-us/ai/responsible-ai)
 * Defines [6 principles](https://docs.microsoft.com/en-us/learn/paths/responsible-ai-business-principles/) 
    * Accountability - develop accountability norms and review boards for oversight.
    * Transparency - explain decisions, intelligibility (understand how and why it works a specific way)
    * Fairness - ensure similiarly situated groups are treated equivalently.
    * Reliability and Safety - build trust with rigorous testing and maintenance.
    * Privacy and Security - secure access to data, transparency on collection/storage and usage.
    * Inclusiveness - recognize exclusion, learn from diversity, solve for one - and extend to many.
 * Provides [Resources](https://www.microsoft.com/en-us/ai/responsible-ai-resources) for these into practice including:
   * [AI Fairness Checklist](https://www.microsoft.com/en-us/research/publication/co-designing-checklists-to-understand-organizational-challenges-and-opportunities-around-fairness-in-ai/)
   * [Fairlearn](https://fairlearn.org/) open-sourced, community-driven Python project to improve AI fairness
   * [InterpretML](https://github.com/interpretml/interpret) - open-sourced package with ML interpretability techniques
   * [Counterfit](https://github.com/Azure/counterfit/) - command-line tool to assess security of ML systems
   * [Error Analysis](https://erroranalysis.ai/) - toolkit to get deeper understanding of ML errors, evaluate different cohorts


`Assignment:` Explore the learning path: [Identify Principles and Practices for Responsible AI](https://docs.microsoft.com/en-us/learn/paths/responsible-ai-business-principles/)

### 6.4 Codes of Conduct

A professional **code of conduct** provides a _prescriptive_ set of rules and responsibilities that an individual or group must follow, if they wish to remain a member of that organization. A professional **code of ethics** is more [_aspirational_](https://keydifferences.com/difference-between-code-of-ethics-and-code-of-conduct.html) defining the shared values and ideals of that organization. The terms are sometimes used interchangeably in certain articles. 

Professional codes are _moral guidelines_ for professional behavior, helping employees or organization members _make decisions that align with company principles_. The downside is that they are not always enforceable legally - making them only as strong as the willingness of members to comply. In that context, codes have similar limitations to other oaths of ethics. See: [Oaths vs. Checklists](https://resources.oreilly.com/examples/0636920203964/blob/master/of_oaths_and_checklists.md). 

Examples of professional codes of conduct:
 * [Oxford Munich](http://www.code-of-ethics.org/code-of-conduct/) Code of Ethics
 * [Data Science Association](http://datascienceassn.org/code-of-conduct.html) Code of Conduct (created 2013)
 * [ACM Code of Ethics and Professional Conduct](https://www.acm.org/code-of-ethics) (since 1993)


`Assignment:` Look at organizations that work with big data and AI. Do they have a code of ethics? What does it cover and who are the target members? How is the code enforced?

### 6.5 Ethics & Compliance

**Ethics** is about doing the right thing, even if there are no laws to enforce it. **Compliance** is about following the law, when defined and where applicable.
**Governance** is the broader umbrella that covers all the ways in which an organization (company or government) operates to enforce ethical principles and comply with laws, including mechanisms to ensure accountability by its members.

We've already discussed data ethics. And the previous section explored corporate governance for _algorithms_ with responsible AI. Now let's look at regulatory compliance with focus on _personal data and user privacy_. Rapid adoption of digital transformation and big data has pushed more state and national governments to enact legislation to protect the personal data rights of citizens.

Here are a few landmark data privacy regulations:
 * `1974`, [US Privacy Act](https://www.justice.gov/opcl/privacy-act-1974) - regulates _federal govt._ collection, use and disclosure of personal information.
 * `1996`, [US Health Insurance Portability & Accountability Act (HIPAA)](https://www.cdc.gov/phlp/publications/topic/hipaa.html) - protects personal health data.
 * `1998`, [US Children's Online Privacy Protection Act (COPPA)](https://www.ftc.gov/enforcement/rules/rulemaking-regulatory-reform-proceedings/childrens-online-privacy-protection-rule) - protects data privacy of children under 13.
 * `2018`, [General Data Protection Regulation (GDPR)](https://gdpr-info.eu/) - provides user rights, data protection and privacy.
 * `2018`, [California Consumer Privacy Act (CCPA)](https://www.oag.ca.gov/privacy/ccpa) gives consumers more _rights_ over their personal data.


`Assignment:` Explore the GDPR or CCPA. How do these laws impact the data privacy issues discussed in our ethics concepts section. What is one example of how these laws impacted a product you use daily? (_Hint:_ Do you browse the web?)

### 6.6 User Rights & Privacy

The CCPA was in part inspired by GDPR and the knowledge that existing US privacy laws did not provide sufficient protections for individual data rights and privacy. The core GDPR concepts [explained simply](https://termly.io/resources/articles/gdpr-for-dummies) are 
 * _privacy by design_ (minimizing data collection and maximizing data security in products) 
 * _consent_ (asking users permission to process their data). 

GDPR also granted individuals [8 data subject rights](https://dataprivacymanager.net/what-are-data-subject-rights-according-to-the-gdpr/) - the right to be informed, right of access, right to rectification, right to object to processing, rights in relation to automated decision making and profiling, right to be forgotten, right to data portability, and right to restrict processing.

The CCPA [defines 4 rights](https://www.oag.ca.gov/privacy/ccpa): right to know, right to delete, right to opt-out, and right to non-discrimination. 

These individual rights and related protections allow users more control over _what_ data is collected by businesses (about them), how it is used or shared, and how to have their personal data deleted (or _forgotten_). The article (and image below) from [Fusion Alliance](https://fusionalliance.com/ccpa-data-privacy-checklist-and-plan) compares GDPR and CCPA approaches to data protection and privacy, also giving a sense of penalties (for ethical lapses or non-compliance) that make businesses more accountable.

![](https://fusionalliance.com/wp-content/uploads/2020/11/ccpa-v-gdpr.svg)



