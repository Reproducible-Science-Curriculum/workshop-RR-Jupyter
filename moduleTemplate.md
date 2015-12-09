This document describes the content and format for a module. Each #rrhack module is a separate git repository.

The [rr-intro](https://github.com/Reproducible-Science-Curriculum/rr-intro) repository is a good example module.

All repositories should contain the following content (details below):

* LICENSE.md
* README.md
* instructor notes
* slides
* code
* images/
* data/

## Submodules
If appropriate, each lesson can be split into submodules. Submodules can help with timing; allows instructors to shorten / lengthen a lesson by including only some submodules; or helps to separate generic, language-agnostic material from R or python material. If you are splitting a lesson into submodules, each submodule should have slides, instructor notes, code, etc.

## File naming
* file naming: `moduleshortname-submodule-slug.extension` where:
  * `moduleshortname` is a unique short name that identifies the module (e.g. intro, organization, etc). Helpful, for example, when we copy the slides from each module into the workshop website repo so that everything isn't just called "slides"
  * `submodule` is the submodule number (01, 02, etc) for lessons divided into submodules (a submodule might be slides + exercise + discussion)
  * `slug` is the description of that file (e.g. instr-notes, slides, etc)

## Content details
### License
All #rrhack content is licensed [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

### Readme
The README file is plain markdown (`.md`). The README should give an overview of the lesson and the contents of the repository. It contains:
* a list of collaborators
* a synopsis of the lesson
* a syllabus / list of goals ("after this lesson, students should be able to...")
* setup instructions
* list and description of submodules
* summary of other files in the repo
* description and attribution of data or other resources used in the module

### Instructor notes
Instructor notes are plain markdown (`.md`). The nodes should contain a detailed description of the lesson, including goals, timing, exercises, gotchas, presenter notes, etc.

### Slides
Slides are in `.Rmd` format, rendered to `.html` using ioslides (not `.Rpres`). Put both the Rmd and the html in the repo. Put images used in slides in a `img` subdirectory to keep things tidy

### Code
As of fall 2015, all examples and code are in R. File should be provided in `.Rmd` format. Depending on the lesson, you may want to have a version that you provide to students at the start of the lesson, and a completed version for the instructor.

### Data
This directory contains any data used in the lesson. Even if a lesson uses the same data sets as a different lesson, it is helpful to repeat the files here. If the data can be easily downloaded from another location and used without further processing, then no need to include data here.

## Exercises
All modules should contain specific hands-on exercises for learners. Make sure the lessons are written down and can be provided to students, either in the slides or in the instructors notes for pasting into the etherpad. Don't simply give exercises verbally, or give non-specific exercises ('go play with the code now and do something different').
