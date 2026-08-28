# Research Software Engineer I \- Technical Challenge

Imagine we are developing an AI-enabled literacy platform that uses educational data to better understand word-reading difficulty and inform future learning experiences.

Create a small **Jupyter Notebook, Google Colab notebook, Marimo notebook or Python research prototype** that explores the Developmental English Lexicon Project (d-ELP) dataset and demonstrates how you would analyze patterns in word-reading difficulty. You will have approximately **one week to submit**, but please limit development to approximately **2 to 4 hours**. This is an exploratory prototype, not a production-ready system. 

You may use AI-assisted development tools such as ChatGPT, Claude, Copilot, Cursor, Gemini, or similar tools. **AI use is permitted and will not negatively affect your evaluation.** Technology used must comply with UF's [Responsible Use of Artificial Intelligence Policy](https://policy.ufl.edu/policy/responsible-use-of-artificial-intelligence/) and [Prohibited Technologies requirements](https://it.ufl.edu/security/security-guidance/prohibited-technologies/).

We are interested in your **Python and data skills, technical decisions, research reasoning, and understanding of the work you produce**, not how much code you can generate. In addition, we will be evaluating your ability to present the information to non-technical stakeholders (you may create a powerpoint presentation or equivalent deliverable to present at the 2nd interview.)

## Provided Dataset

You will work with the **Developmental English Lexicon Project (d-ELP)**, a research dataset containing continuous word-reading difficulty estimates for **9,961 frequently printed English words**, along with lexical and linguistic characteristics that may help explain differences in difficulty. Please use the uploaded CSV (**full\_item\_level\_database.csv**) in the provided github. You may reference the full [dataset](https://qmi-fcrr.shinyapps.io/delp/) from the study such as demographics or trial-level response, but it is not required to analyze beyond the provided CSV in the repo.

**Related Research Paper:**  
Compton, D. L., Rueckl, J. G., Steacy, L. M., Siegelman, N., Edwards, A. A., Petscher, Y., Patton-Terry, N., Cooper Borkenhagen, M. J., & Starke, C. (2025). *The Developmental English Lexicon Project (d-ELP): Continuous Word Reading Difficulty Estimates of the 9,961 Most Frequently Printed English Words for US Children.* [https://osf.io/preprints/psyarxiv/zak2b\_v1](https://osf.io/preprints/psyarxiv/zak2b_v1)

The d-ELP database is distributed under the **CC BY-NC-ND 4.0 license**. Use the dataset only for this noncommercial technical challenge and do not publicly redistribute modified versions of the data. Include the above citation in your notebook or README.

## 

## Your Task

Create a notebook and presentation that investigates:

**What characteristics of words appear to be associated with word-reading difficulty for developing readers?**

There is no single correct solution. Choose questions you believe are meaningful and determine an appropriate technical approach.

Your project should demonstrate:

### **Data preparation**

Inspect, clean, filter, transform, or otherwise prepare the available data as appropriate. Select the variables you believe are useful for your analysis.

You are not expected to use every variable.

### **Exploration and visualization**

Identify at least **two meaningful findings or patterns** and create at least **two visualizations** that help communicate them.

Possible areas to explore include word length or frequency, spelling or sound characteristics, relationships between multiple word features, groups of relatively easy or difficult words, or unusual observations. These are examples only.

### **Analytical or predictive modeling**

Build at least **one analytical or predictive model** that adds insight into word-reading difficulty. This may be a simple statistical or machine-learning approach.

Possible approaches might include estimating difficulty, identifying influential features, comparing groups of words, clustering words with similar characteristics, or another reasonable method.

### **Interpretation**

Explain what you found, what your model or analysis can reasonably tell us, at least one important limitation, and what you would investigate next.

Also briefly describe **one way your findings could potentially inform an educational software system**, such as selecting or sequencing words, identifying words that may need additional support, grouping words into activities, informing dashboards, or identifying useful features for a future student or content model.

You do not need to implement this feature.

## Technical Approach

You may choose the technologies, libraries, models, and methods you believe are appropriate.

We want to understand **what you chose and why**. Your solution should be practical, understandable, and appropriate for the problem rather than unnecessarily complex.

The goal is to demonstrate how you turn unfamiliar research data into a **usable and technically sound analysis that can be understood by other developers and researchers**.

Your project should demonstrate the overall workflow:

**provided data → preparation → exploration → visualization → analysis/model → findings**

## Submission

Commit and push your completed project to the private GitHub repository provided to you.

Use Git during development and make reasonable commits reflecting meaningful stages of your work.

Your repository should include your notebook or source code and a short README containing:

* How to run the project  
* Technologies, libraries, and models used, and why you selected them  
* Brief summary of your approach and findings  
* Known limitations or what you would investigate next  
* **Two important research or engineering decisions**, including an alternative considered for at least one  
* Brief description of any AI tools used  
* One AI-generated suggestion, assumption, analysis, or implementation you changed, rejected, questioned, or independently verified

Do not submit AI transcripts, prompt histories, or IDE telemetry. 

Be prepared to give a presentation of your findings and visualizations.

There is no expected model or technical stack. We are interested in whether you can work independently with unfamiliar research data, make appropriate technical decisions, build a functional analysis, communicate findings clearly, and explain your work to a broader technical team.

During the second interview, you will briefly demonstrate your project, explain your technical choices and findings, navigate your notebook, and respond to a **small follow-up question or change to the analysis**.

**Please limit take-home development time to approximately 2 to 4 hours.**