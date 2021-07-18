# Articles: Review Notes

🔴 = Linked (relevance checked, no notes yet) <br/>
🟠 = Outlined (broad topics identified) <br/>
🟢 = Reviewed (deep dive provided) <br/>

> **RELATED REFERENCES**

* 🔴 2021, [What is Data Ethics](https://www.dataversity.net/what-are-data-ethics/), _DataVersity_ 
* 🟢 2021, [The Third Pillar Of Trusted AI: Ethics](https://www.dataversity.net/the-third-pillar-of-trusted-ai-ethics/), _DataVersity_ (4 components) | [**Notes**](_5-the-third-pillar-of-trusted-ai-ethics)
* 🔴 2021, [Google, Facebook And Microsoft Are Working On AI Ethics—Here’s What..](https://www.forbes.com/sites/glenngow/2021/07/11/google-facebook-and-microsoft-are-working-on-ai-ethics-heres-what-your-company-should-be-doing/?sh=23d4d5a9aa64), _Forbes_
* 🔴 2021, [Ethics in Data Science - How I learned to..](https://towardsdatascience.com/ethics-in-data-science-or-how-i-learned-to-start-worrying-and-question-the-process-947efd8260e9), _Towards Data Science_
* 🟢 2021, [The 12 Ethical Pillars of Data](https://dataethics4all.org/) - _DataEthics4All.org_ | [**Notes**](#_1-nbsp-the-12-ethical-pillars-of-data)
* 🔴 2021, [Data Science Ethics: Case Studies](https://samiwurm.medium.com/data-science-ethics-case-studies-988cbbc6af84) - _Sami Wurm, Medium_
* 🟢 2021, [Six Questions About Data Science Ethics](https://halpert3.medium.com/six-questions-about-data-science-ethics-252b5ae31fec) - _Henri Alpert, Medium_ | [**Notes**](#_2-nbsp-six-questions-about-data-science-ethics)
* 🔴 2021, [Ethical use of data. A Data Scientist's Code Of Conduct](https://www.becker.com/blog/cpe/ethical-use-of-data-a-data-scientists-code-of-conduct) - _Marsha Parker_
*  🟢 2021, [The Hathaway Effect](https://stuffilearnedyt.wordpress.com/2021/01/25/the-hathaway-effect-strange-correlation-between-anne-hathaway-and-warren-buffet/#), _Stuff I learned_ | [**Notes**](#_3-nbsp-the-hathaway-effect)
* 🔴 2021, [Team Data Science Lifecyle](https://docs.microsoft.com/en-us/azure/architecture/data-science-process/lifecycle)*, _Microsoft Docs_ 
* 🟢  2020, [How AI Can Go Terrible Wrong: 5 Biases that Create Failure](https://www.forbes.com/sites/glenngow/2020/11/09/how-ai-can-go-terribly-wrong-5-biases-that-create-failure/?sh=4622e6e75b87), _Forbes_ | [**Notes**](#_4-nbsp-how-ai-can-go-terrible-wrong-5-biases-that-create-failure)
* 🔴 2020, [A Beginners Guide to Data Ethics](https://medium.com/big-data-at-berkeley/things-you-need-to-know-before-you-become-a-data-scientist-a-beginners-guide-to-data-ethics-8f9aa21af742) - _Big Data Berkeley, Medium_
* 🔴 2020, [What would an Ethics Of Data Science Look Like](https://towardsdatascience.com/what-would-an-ethics-of-data-science-look-like-e9d4e9ddc2b3), _Towards Data Science_
* 🔴 2020, [The Ethics of Data Science](https://towardsdatascience.com/the-ethics-of-data-science-e3b1828affa2 ), _Towards Data Science_
 * 🔴 2016, [What is Data Ethics](https://royalsocietypublishing.org/doi/10.1098/rsta.2016.0360#), _UK Royal Society_
---

> **REVIEW NOTES**


### 1. &nbsp; [The 12 Ethical Pillars Of Data](https://dataethics4all.org/)

The [DataEthics4All](https://dataethics4all.org/) raises awareness of ethical use of data with `a Framework 2.0` that has three goals:
 * Build responsible tech with _ethics by design_
 * Promote _end-to-end data governance_ for ethical data use across org
 * _Cognitive diversity and inclusion_ in human oversight for building next-gen AI

The `12 ethical pillars` for this framework are:
 1. Preserve Data **Privacy**
 2. Process Data **Fairly**
 3. Prevent Data **Misuse**
 4. Clear Data **Ownership**
 5. Explicit Data **Consent**
 6. Personal Data **Control**
 7. Personal Data **Transparency**
 8. Audit Data **Quality**
 9. Audit **Algorithms** Inter-disiplinarily
 10. Combat Deliberative **Disinformation**
 11. Prevent Ad **Weaponization**
 12. Understand **Evolution** of Ethics (under crisis)

### 2. &nbsp; [Six Questions About Data Science Ethics](https://halpert3.medium.com/six-questions-about-data-science-ethics-252b5ae31fec)

The six questions that data scientists need to explore for ethics:

 1. `Is the data fair and unbiased?` How was the data gathered? Was there any inherent bias in the source or community or origin?
 2. `Is the data being used fairly and ethically?` Was data used to manipulate user decisions or misrepresent outcomes? Was it used with relevant consent?
 3. `Is privacy being protected?` How secure is the data collection process? If data is shared, how effectively is it anonymized?
 4. `To whom does data belong? Company or user?` If company owns data, what rights or controls does user have if they are the subject? If user owns data but creates it in bad faith (e.g., reviews company) what rights or controls does company have to get it taken down?
 5. `What effects do the data and the algorithms have on society?` Recommendation systems can manipulate or influence user decisions and behaviors. What if those decisions cause harm (e.g. radicalization through video recommendations, bias in credit scoring can lead to social discrimination)
 6. `Is the data manipulated or deceiving?` Even when data is accurate, the visualization can be manipulated to misrepresent the insights e.g., COVID-19 graphs on some networks downplayed rate of growth by manipulating axes.

### 3. &nbsp; [The Hathaway Effect](https://stuffilearnedyt.wordpress.com/2021/01/25/the-hathaway-effect-strange-correlation-between-anne-hathaway-and-warren-buffet/#)

_The Hathaway Effect is a phenomenon that happens when actress Anne Hathaway is trending on social media or makes headlines, stocks in Berkshire Hathaway company rise_

It is an anecdote that shows the possible flaws in algorithm design, that can potentially introduce bias in the decisions it takes because it mistakes correlation for causation. In a different context, such algorithmic flaws or bias can cause harm.

### 4. &nbsp; [How AI Can Go Terrible Wrong: 5 Biases that Create Failure](https://www.forbes.com/sites/glenngow/2020/11/09/how-ai-can-go-terribly-wrong-5-biases-that-create-failure/?sh=4622e6e75b87)

AI biases can deliver poor results that can impair organizational reputation or cause individual harm. There are five types of bias:

 * `Human Bias`: AI is trained on data generted by humans. And humans have biases that leak into the data - and get amplified by AI algorithms. _What tools and frameworks can help us discover and mitigate or remove these biases?_
 * `Hidden Bias`: Are unintentional biases that are hard to uncover because they occur in very niche contexts, or because their logic is unclear. _What tools help us build explainability into our data models so we can understand the decision process?_
 * `Data Sampling Bias`: AI is trained on data sets that are often sampled from a larger volume of data. _Is your training set representative of the problem space and user groups targeted?_
 * `Long-tail Bias`: Long-tail bias happens when certain categories are missing from the training data because they don't occur in sufficient volume to be captured. _Is your training set representative of the problem space and user groups targeted?_
 * `Intentional Bias`: The most dangerous of all - this is bias that is introduced by human actors with malicious intent (e.g., cyberattack). Because it is intentional, it is likely to be disguised well and harder to detect.


 ### 5. [The Third Pillar Of Trusted AI: Ethics](https://www.dataversity.net/the-third-pillar-of-trusted-ai-ethics/)

 Authors identify 3 components to trusted AI -- [performance](http://www.dataversity.net/the-three-pillars-of-trusted-ai/), [operations](https://www.dataversity.net/the-second-pillar-of-trusted-ai-operations/), and [ethics](https://www.dataversity.net/the-third-pillar-of-trusted-ai-ethics/).
  * Performance = _How well can my model use data to make predictions?_ 
  * Operations = _How reliable is the system that my model is deployed on?_ 
  * Ethics = _How well does my model align with my organization’s ethics and values?_ 

Performance focuses on model accuracy, operations focuses on monitoring & governance, and ethics focuses on 4 components namely:

   * Privacy
   * Bias & Fairness
   * Explainability & Transparency
   * Impact on the organization

Bias refers to situations in which, **mathematically**, the model performed differently (better or worse) for distinct groups in the data. Fairness, on the other hand, is **a social construct** and subjective based on stakeholders, legal regulations, or values. The intersection between the two lies in context and the interpretation of test results. Measuring bias has 2 categories:
 * Fairness by representation = measure fairness by **model's predictions** amongst all groups
 * Fairness by error = measure fairness by model's **error rate** among all groups.

Once bias is identified, you can mitigate it by analyzing data and identifying data curation or feature engineering step corrections. In general, mitigation techniques vary based on stage:
 * Pre-processing = mitigate bias before modeling happens
 * In-processing = mitigate bias during training process
 * Post-processing = mitigate bias in predictions


Trust in ethics also means being able to interpret, or explain, the model and its results as well as possible. Explainability should be a part of the conversation when selecting which model to put into production. Choosing a more explainable model is a great way to build rapport between the model and all stakeholders.
