# Description of hands-on demos/exercises

## Approach

The pedagogical approach of this workshop will be modeled on that of 
the Software and Data Carpentry communities and will utilize the 
following interactive components: 

### Live Coding

The content will be presented through a combination of speaking 
and live coding in front of tutorial participants.  Presenters will 
both talk about HPC concepts as described in the outline, and 
demonstrate them in front of participants, with the expectation that 
participants follow along and run the same commands as the presenter.  

> **Example: Logging onto a large-scale computing system**
> 
> Presenter draws a diagram of a user's local computer and the 
> login node of a remote computing system, and describes what is 
> happening when users log in.  She then demonstrates 
> logging into the provided cluster using the "ssh" command; all participants
> use the same command to log in to the same cluster.  

### Exercises

In addition to the content presentation, the tutorial will contain 
regular exercises where participants are expected to work individually 
or in groups on a set of challenges.  There will be an exercise or 
independent activity for about every 15-20 minutes of instruction.  

> **Example Exercise: Submitting jobs to a batch scheduler**
> 
> `submit-job.pbs` submits a request to run our 
> script on the test file `test.csv`:
> 
> `python analyze.py test.csv`
>
> Modify the script `submit-job.pbs` to instead submit a job to run the 
> analysis on our actual input data, `temperatures.csv`. This job will need 
> more than 1 GB, so you will also need to change the amount of memory 
> that `submit-job.pbs` is requesting.

### Support

Throughout the workshop, participants will be provided with two 
colors of sticky 
notes to serve as a visual indicator of progress: one color to 
indicate success or understanding, the other to indicate confusion 
or a question.  This allows the lead presenter to respond to the 
audience at a glance.  In addition, 
when presenters are not leading a session, they will circulate 
among participants to answer questions or address immediate issues.  Finally, 
an online note-taking page (etherpad) will 
be set up for participants to take collaborative notes and chat 
with each other.  
 
Exercises and demonstrations will be fully tested on the planned resources 
before the workshop. 

### Lesson Materials

The materials developed for this workshop will be similar in format to those 
developed by [Software Carpentry](http://software-carpentry.org/lessons/).  For 
an example of what the final materials will look like see: 
* Software Carpentry lesson on the Unix Shell: 
[http://swcarpentry.github.io/shell-novice/](http://swcarpentry.github.io/shell-novice/)

To see an example of how lessons will incorporate live commands, diagrams, and 
follow-on exercises, see: 
* [http://swcarpentry.github.io/shell-novice/03-pipefilter.html](http://swcarpentry.github.io/shell-novice/03-pipefilter.html)


## Computing Resources

This tutorial requires access to a large scale computing system that 
supports remote login and uses a batch scheduler.  We will have temporary 
accounts created for all partipants on the Oklahoma State University
computing cluster for this purpose.  We are also applying for an 
education allocation on XSEDE which, if granted, will complement the resources 
available through Oklahoma State.  

Participants will need to bring their own laptop or portable computing 
device that can use WiFi.  The tutorial will require using 
a bash shell (or similar tool); installation instructions will be part of 
the workshop materials.  

