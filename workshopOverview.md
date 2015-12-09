<h1>Reproducible science workshop overview</h1>

This document provides basic information about Reproducible Science workshops for instructors:

* general outline of a Reproducible Science workshop; 
* location of materials;
* learning goals for each module;
* instructor skills needed for each module; 
* examples of previous workshops. 

All of our material is on GitHub with a [CC0](https://creativecommons.org/publicdomain/zero/1.0/) copyright waiver: [Reproducible Science Curriculum on GitHub](https://github.com/Reproducible-Science-Curriculum)

<h2>Workshop outline</h2>

As of September 2015, a ReprSci workshop has five modules: 

1. [Introduction](#intro);
2. [Organization](#organization); 
3. [Version Control](#version_control); 
4. [Automation](#automation); 
5. [Publication](#publication). 

<h3><a name="intro">I. Introduction</a></h3>
**Goals**: Recognize problems that reproducible research helps address; Identify pain points in getting analyses to be reproducible; Understand role of documentation, sharing, automation, and organization in making research more reproducible; Introduce some tools to solve these problems, specifically R/RStudio/RMarkdown.

**Instructor's skills:** Good understanding of the concept of reproducibility. Ability to list common problems emerging if research cannot be reproduced. Knowledge of, at least selected, tools, processes and approaches to making research reproducible. 

**Materials**

*Repository*: [https://github.com/Reproducible-Science-Curriculum/rr-intro](https://github.com/Reproducible-Science-Curriculum/rr-intro) <br/>
*Sample slides*: [deck 1 from Duke workshop](http://reproducible-science-curriculum.github.io/2015-05-14-reproducible-science-duke/intro-slides/intro-01-slides.html) and [deck 2 from Duke workshop](http://reproducible-science-curriculum.github.io/2015-05-14-reproducible-science-duke/intro-slides/intro-02-slides.html)  

<h3><a name="organization">II. Organization</a></h3>
**Goals**: Students will learn the benefits of project and folder organization, and how these enable reproducibility and reusability. They will then complete an activity highlighting the structure of data files, emphasizing the importance of documenting any changes made. Finally, they will bring these two activities together in the context of a reproducible project workflow centered around using `knitr` in RStudio.

**Instructor's skills**: Good understanding of file organisation in research projects. understanding of file structure on major operating systems (Windows, Linux/Unix, Mac OS) and the interface/commands for managing files and folders. Understanding of basic file types (binary vs. text). At least a basic overview of how files are stored (and deleted) in different operating systems. Understanding of file and folder naming conventions (names, extensions etc.).  

**Materials**

*Repository*: [https://github.com/Reproducible-Science-Curriculum/rr-organization1](https://github.com/Reproducible-Science-Curriculum/rr-organization1) <br/>
*Sample slides*: [file organization](http://reproducible-science-curriculum.github.io/2015-05-14-reproducible-science-duke/organization-slides/), [file naming](http://reproducible-science-curriculum.github.io/2015-05-14-reproducible-science-duke/naming-slides/) and [literate programming](http://reproducible-science-curriculum.github.io/2015-05-14-reproducible-science-duke/lit-prog-slides/)

<h3><a name="version_control">III. Version Control</a></h3>
The initial version of the workshop didn't include version control, but there were many requests for this module during the first workshop at Duke, so we added it for the iDigBio workshop. 

**Goals**: Initiate Git in a local project directory; Evaluate repository History; Know the difference between directory and repository; Commit changes to files; Push local repository to remote repository on Github; Clone a remote repository; Create a pull request to someone else's remote repository; Differentiate between a local and remote repository.

**Instructor's skills**: Very good understanding of the concept of version control. Solid practical knowledge of Git and GitHub. Recommended: knowledge of other version control (SVN, Mercurial); ability to highlight the advantages of version control over tools such as Dropbox or tracking changes in binary documents (MS Word).

**Materials**<br/>
*Repository*: [https://github.com/Reproducible-Science-Curriculum/rr-version-control](https://github.com/Reproducible-Science-Curriculum/rr-version-control) <br/>
*Sample slides*: [slides!](http://reproducible-science-curriculum.github.io/2015-06-01-reproducible-science-idigbio/vcs-slides/01-motivation-slides.html)

<h3><a name="automation">IV. Automation</a></h3>
**Goals**: Transforming scripts into functions; Make files as a concept; Utilizing free continuous integration tools;   Recreate figures automatically

**Instructor's skills:** Good understanding of programming concepts, in particular code modularisation, writing and using functions, code reusability and so on. Good understanding of selected software engineering concepts such as project build and automation, code testing, continuuous integration and  so on. Solid knowledge of R, RStudio and relevant packages (consult the materials for details). Understanding of basic statistical concepts (consult the materials for details).  

**Materials**: <br/>
*Repository*: [https://github.com/Reproducible-Science-Curriculum/rr-automation](https://github.com/Reproducible-Science-Curriculum/rr-automation) <br/>
*Sample slides*: none (all hands-on in R)

<h3><a name="publication">V.Publication</a></h3>
**Goals**: Why, what and how to publish research materials; Choosing a data repository; Choosing licenses for software + data

**Instructor's skills:** Understanding of requirements for reproducible publication.

**Materials**:<br/>
*Repository*: [https://github.com/Reproducible-Science-Curriculum/rr-publication](https://github.com/Reproducible-Science-Curriculum/rr-publication)<br/>
*Sample slides*: [slides!](http://reproducible-science-curriculum.github.io/2015-06-01-reproducible-science-idigbio/slides/01-publication-slides.html)


<h2>Examples of previous workshops</h2>  

* Duke University: [public website](http://reproducible-science-curriculum.github.io/2015-05-14-reproducible-science-duke/) and [repository](https://github.com/Reproducible-Science-Curriculum/2015-05-14-reproducible-science-duke)
* iDigBio: [public website](http://reproducible-science-curriculum.github.io/2015-06-01-reproducible-science-idigbio/) and [repository](https://github.com/Reproducible-Science-Curriculum/2015-06-01-reproducible-science-idigbio)
* Duke Marine Lab: [public website](http://reproducible-science-curriculum.github.io/2015-09-24-reproducible-science-duml/) and [repository](https://github.com/Reproducible-Science-Curriculum/2015-09-24-reproducible-science-duml)

<h2>Ongoing work</h2>
These materials are being revised as we get more feedback from participants and instructors. The list of [GitHub issues for the Reproducible-Science-Curriculum](https://github.com/issues?user=Reproducible-Science-Curriculum) gives a pretty good idea of what is happening and what needs to be done. 



