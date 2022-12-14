```{slide} Integrating Ethics into Data Science Courses
:class: title



```


```{slide} Goal for today


I want you to leave with:

* something you plan to do this semester

* ideas to implement in your next offerings

* strategies so that you can more deeply embed ethics over time


```



`````{slide} How can we support students in becoming ethical data science practitioners?
:class: section

```{note}
I want to begin with motivation to make it clear what my approach is.

The goal we have will shape how we get there


Focusing on practitioners makes clear what aspects are and are not important we can focus only on teaching how and when to employ ethical decision making, and how to gather information and engage in the conversations.  We do not necessarily need to teach broad ethical frameworks, but how to identify when to do things.


Sources of competence
```

`````



````{slide} How we will do that?

- About me & my ethics training
- Goals & Examples for now
- Call to Action
- Deeper changes

```{note}
In order to take a practitioner focused approach; I'll start with  how I developed ethical thinking skills.

How I learned.

Then I'll go through some

```

````

```{slide}   *My* ethical training
:class: section
```

```{slide} I am an engineer

- engineering is professionalized
- ABET accreditation standardizes somewhat


```



````{note}

```{slide} Engineering Design process
In my program our first engineering in major requirement is/was engineering design: a whole semester on this process (slide). We go through these phases in broad, minimally technical cases and we reviewed engineering failures and studies how and why they went wrong. We did this BEFORE, we took any other engineering classes; in parallel to calculus, and physics or chemistry prereqs.
<!-- diagram -->
```
````

````{slide} Correctness for Safety

- Learning Design through disasters
- Importance Building intuition
- Different types of Correct

```{note}
hey constantly preached at us to both check our work throughly using the skills from our math classes for checking solutions, but also, to, more importantly, before getting into any algebra, do some napkin math. To have a few constants, a few settings of things memorized, or really to do problems until you had the intuition to look at an answer and know if it was off by an order of magnitude or not.


Context
```

````
<!-- no calculator exam -->



````{slide} Experiential Education


- Human subject research at MGH Breast Imaging Research
- BAE Systems Target Development Lab
- Human subject research at C.S. Draper Laboratory

```{note}
Note: this slide serves two purposes, it fits here, in the narrative of my development and some core examples.

Also, I'll pause to acknowledge that two of these are defense contractors and that often causes people to take pause.

moral vs ethical

2nd: context again; of these choices my coops were in 2008,9,10; recession & war


Hostpitals and military all have strict ethical guidelines and a culture of adhereing to that. Even if you don't agree that war is ever necessary or appropriate; the military is an example of ethics which is a set of agreed upon terms. Note that this is differnt from morals, but we will come back to that. Time in these environments exposed me to the ways that ethical expectations are promulgated in these environments and on at least the small teams that I was on this was taken very seriously and led to actual conversations about what the right way to do something was and when tasks were in gray areas, that is things that were deemed acceptable, but easily mistaken for something that would not be acceptable, or unpopular very long conversatiosn about what we did and did not do or say.



**CONTEXT**
```
````


````{slide} Interdisciplinary ML work

- ML Lab with many collaborators: psychologists, civil engineers, physician scientists
- AFOG @ Berkeley
- Race & Medicine Working Group at Brown

```{note}
In my lab, every student had a collaborator with domain expertise: I worked with pyschologists, a lab mate worked with civil engineers studying infrastructure health; other worked with physician scientists studying long time scale COPD; other with p-s at memorial sloan kettering treating skin cancer, looking for better diagnostic tools.
This experience again led me to see exactly how the ethics of machine learning application needs to work in practice and form the core position that makes a workshop like this so hard.

AFOG-- role of profesionaliation


medicine again; practioners interacting with ...
```

````

```{slide} Ethics requires *context* and is concerned with *impact*
:class: section
```


````{slide}
> Missing context is endemic in ML/DS/AI -- even in AI ethics work


```{note}
This is my experience

and it was the conclusion of a meta-analysis of over 500 papers from the AIES and FAccT. Work was primarily abstract.
```
````

<!--
```{slide} FAccT



```



````{slide}


> Data science ethics is not, and cannot be, a thing the way that biomedical ethics or legal ethics, or even engineering ethics are.


```{note}
Data science is a set of techniques that can be applied anywhere-- this is part of what makes it so exciting and engaging and fun, but those other domains: biomedicine, law, engineering, are domains of both skills and practices AND of knowledge in how the world works. Those domains interface with the world in a fundamentally different way than data science.

Each of these is about a part of the world; DS is set of tools
```

````
-->

```{slide} So what *can* we do?
:class: section
```

````{slide} Start Small


- refresh presentation
- small additions to assignments
- model what you know

```{note}
This also gives you time to learn more; start by modeling what you know.
```


````


````{slide}

> Effective, inclusive teaching is important to me

```{note}
Ethics as Good Pedagogy

In addition to my own ethical development, I am going to pause to note in particular my training in evidence based teaching practices.
```
````

<!--
````{slide} Start small, then go bigger

```{panels}
Small

^^^
- refresh presentation
- small additions to assignments
---

Moderate

^^^
- reorder
- replacements

---

Long time scales

^^^
- change topics
- rework assignments completely

```

````


```{slide} A way to change
:class: strategy
```

```{slide} A thing that's been done
:class: example
```

 -->

`````{slide} Things you can do this *semester*
:class: section

... and the next few

```{note}
- Emphasize Evaluation
- Highlight Context
- Consider downstream effects
```

`````

````{slide} Really, this semester

These require:
- no major re-ordering
- no changing of datasets
- no added modules

```{note}
All of these are based in pedagogy
```

````



`````{slide} Emphasize Evaluation
:class: strategy

```{panels}
in Instruction
^^^
- Frame evaluation as competing goals
---
in Assignments
^^^
- Always require more than one metric
- Disaggregate by group in social data

```

```{note}

Evaluation allows students to think about problems more deeply.

Fairness issues "discovered" in ML through eval

It helps monitor, considering broader impact
```

`````

````{slide} Optimal is relative
:class: example


```{panels}
in Instruction
^^^
- Simple repeated saying
---
in Assignments
^^^
- require justification on the word "best"

```

```{note}
Simple, easy to remember reminders can help students start thinking and questioning what they do.
```


````


````{slide} Talk about where data comes from
:class: strategy

```{panels}
in Instruction
^^^
- Discuss before loading data
- Distribute Datasheets for Datasets
---
in Assignments
^^^
- Have students write data sheets
- Ask about limits of a dataset
```

`````

```{slide} Robots.txt
:class: example

In Webscraping, we take a moment and look at the robots.txt and talk about why it is there.
```


```{slide} Data descriptions
:class: example


- all assignments starting from loading data to modeling require a description of the data and what it is useful for
- (new) they will do peer review on 2-3 of the data descriptions

```


````{slide} Consider Deployment
:class: strategy

```{panels}
in Instruction
^^^
- Discuss before loading data
- Examine Model Cards
Case studies of retracted models
---
in Assignments
^^^
- add reflection questions
- write model cards

```

`````

```{slide} Deployable? Reflection
:class: example


1. Would you feel safe if your doctor used this model?
1. Based on the exploration of the data, can you anticipate when the model that you trained might fail?

```

```{slide} What will you try?
:class: section

Make a note for one thing you will try

```



```{slide} Looking Forward
:class: title
```



````{slide} Evaluation First
:class: example

(changing the order)

```{admonition} My Syllabus
...
1. What is a machine learning
1. How do we evaluate them
1. Assignment on evaluation
1. How do we train classifiers
1. Assignment on classification
...
```

````


```{slide} Embed activities in Ethical Challenges
:class: strategy

Choose completely datasets that present ethical challenges for demonstration or assignments



```

`````{slide} General Strategies for Integrating Ethics
:class: section

- Emphasize Evaluation
- Highlight Context
- Consider downstream effects

```{note}
No modules
```

`````


````{slide} Questions?
:class: section

brownsarahm@uri.edu
````




```{ifnotslides}

For data science ethics education to change the course of data science practice outside of the academy, ethics must be integrated throughout a student's education and deeply connected to practical computational choices. This session will equip each attendee with small changes that can be made in the current semester and a framework for broader course revisions to deeply integrate ethical thinking into their data science courses.  

```
