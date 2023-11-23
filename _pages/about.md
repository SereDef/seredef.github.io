---
title: "About me"
permalink: /
excerpt: About me
author_profile: yes
redirect_from:
- /about/
- /about.html
---

Hi! This is a little personal website that collects some of the projects I have been working on as part of my PhD (or just
for the fun of it).

If you nose around here, you can find academic publications, little software and web applications, talks, tutorials and 
loads of interactive notebooks and other (big and small) analyses that I have been playing around with.

If you have any questions, notes, suggestions or just want to have a chat, please contact me on LinkedIn or just drop me 
an email. 

Latest projects
======

- **Longitudinal modeling of the co-development of depression and cardio-metabolic risk** \|
  [Web app](https://longit-comorbidity.onrender.com) \| 
  [Repository](https://github.com/SereDef/comorb-longit-project) \\
  <mark style="padding:1px 5px; background-color:white; color:grey"> Tags: </mark> 
  <mark style="padding:1px 5px; background-color:#fdedec; color:grey"> Cross-lag panel model</mark> 
  <mark style="padding:1px 5px; background-color:#fdedec; color:grey"> G-estimation</mark> 
  <mark style="padding:1px 5px; background-color:#fdedec; color:grey"> Network analysis</mark> 
  <mark style="padding:1px 5px; background-color:#fdedec; color:grey"> Dashboard development</mark> 

- **Is [Company name] _bad_? Sentiment analysis of Reddit posts** \| 
  [Repository]() \
  <mark style="padding:1px 5px; background-color:white; color:grey"> Tags: </mark> 
  <mark style="padding:1px 5px; background-color:#fdedec; color:grey"> Web scraping</mark> 
  <mark style="padding:1px 5px; background-color:#fdedec; color:grey"> Natural language processing</mark> 
  <mark style="padding:1px 5px; background-color:#fdedec; color:grey"> Sentiment analysis</mark> 

- **_GuRu_: a smart-search data dictionary web app for the Generation R study** \| 
  [Web app]() \| [Repository]() \
  <mark style="padding:1px 5px; background-color:white; color:grey"> Tags: </mark> 
  <mark style="padding:1px 5px; background-color:#fdedec; color:grey"> UX-design</mark>, 
  <mark style="padding:1px 5px; background-color:#fdedec; color:grey"> PostgreSQL</mark>,
  <mark style="padding:1px 5px; background-color:#fdedec; color:grey"> SNOMED</mark>,
  <mark style="padding:1px 5px; background-color:#fdedec; color:grey"> Knowledge graph</mark>.

- **WORKSHOP: Multiple imputation in R: why and how** | [Slides]()

  Tags: `Multiple imputation`, `Data simualtion`, `Parallel processing` 

- **WORKSHOP: Gentle introduction to Git and GitHub for bio-medical researchers** | [Slides]()

  Tags: `Git`, `GitHub`, `version control`
  
- **TALK: Differential effects of prenatal and postnatal stress on depression symptoms, adiposity and their comorbidity**

  Tags: `Copenhagen` | [Slides]() | [Publication]() | [Repository]()

- **POSTER: arterial thickness, stiffness and blood pressure influence brain morphology in early adolescence **

  Tags: `OHBM 2023` | [pdf]() | [Publication]() | [Repository]()
  
- **TALK: Early-life stress score: multi-cohort data harmonization and integration**

  Tags: `Online EC` | [Slides]() | [Publication]() | [Repository]()

- **TALK: "from data to causes" analyzing panel data**

  Tags: `Bath` | [Slides]() | [Publication]() | [Repository]()

- **TALK: cardio-vascular determinants child health heart and arteries**

  Tags: `Milan` | [Slides]()

- **R PACKAGE: genRate: data handling tool for Generation R data**

  Tags: `Sample selection`, `data cleaning`, `preprocessing` | [Repository]()
  
- **Attentional modulation of neural dynamics in tactile perception of complex regional pain syndrome (CRPS) patients**

  Tags: `EEG`, `Support vector machine`, `experimental design`, `Matlab`| [Publication]() | [Repository]()
  
  
- **Spotify data playground**

  Tags: `Music`, `Spotify API`, `Interactive dashboards` | [Web app]() | [Repository]()


About this website
------

Note: this lil' website is hosted on [GitHub pages](https://pages.github.com). The Jekyll-based template I used was forked from [this repository](https://github.com/academicpages/academicpages.github.io), which extended the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose.

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
[Editing a markdown file for a talk] # /images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
