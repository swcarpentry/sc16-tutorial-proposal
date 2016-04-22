# Detailed outline of the tutorial

The workshop will be divided into morning (AM) and afternoon (PM) sessions:

## AM

The morning session will focus on introducing learners to the command line
and how to interact with the cluster via the command line.
It will also help learners develop a mental model of the cluster structure,
and understand queues, scheduling and batch submission.

The following sections will be covered:

### Introduction to HPC and HTC

### Remote computers and SSH

In this section, learners will learn about command shells,
run simple commands on a shell running on their own machines,
and how they are able to obtain a shell on a remote computer via a secure shell client.
At the end of the section, they will log in to the cluster.

### Navigating the filesystem

This section will introduce learners to the unix filesystem,
basic commands to navigate the filesystem,
and to create, copy, delete and move files and directories.
Along the way, they will learn the anatomy of unix commands,
i.e., switches, parameters and inputs.

### Pipes and filters

This section will introduce learners to the ideas of
standard input and standard output,
how to redirect standard output to a file,
and how to chain (pipe) simple commands together
to accomplish complex tasks.

### Shell scripts

This section will get learners to write a simple bash script.

### Cluster structure and scheduling

Now we will shift gears and discuss the structure of the cluster
(compute nodes, storage, service nodes, etc.,) and importantly,
talk about the scheduler.

* available resources
* requesting resources
* scheduling and policies

### Submitting and tracking a batch job

## PM

The afternoon session will walk learners through a *workflow* on the cluster.


### Overview of the problem (20 minutes)

### Getting code and data into the cluster (20 minutes)

In this section, we will demonstrate

### Downloading, installing and setting up the required software (40 minutes)

### Running a simulation on the cluster (50 minutes)

### Performing data analysis (30 minutes)

The HPCCarpentry workshop will be a full day (6-hour) workshop,
divided in four 90 minute sections.
Within each section,
there will be alternate 10-15 minute
live-coding demonstrations of a certain concept/procedure,
and 10-15 minute exercise/challenge sections.
Participants will be encouraged to work in teams
for the challenge sections.

The first half (3-hours) will focus on helping learners develo
a strong, but flexible mental model of the cluster structure,
and to understand
    * How to move data and programs to and from the cluster,
    * How to submit jobs to the cluster,
    * How to configure their environment,
    * Use existing software and set up their own software.

For the second half, learners will be presented with the following
scenarious:

> Jun is a researcher working on tracking the spread of disease by surveying newspaper
articles as far back as 1900. He has acquired the text of all of these newspapers and has
read the literature on natural language processing approaches for mining this data
and has a Python script from a colleague where he can look for particular words.
He knows he wants to apply these techniques to the newspaper corpus,
but doesn’t know how to run the program and his local computer doesn’t
have the required computational power, even if he could run the program.
He’s heard that he should be able to run the analysis on his university’s
HPC, but he doesn’t know where to start. He needs to understand what remote
computing is, how to log on to the HPC, how to get his data on the HPC,
run analyses there and get his analysis results back on to his own computer. 

> Nelle is a Ph.D. student working on studying [something].
As part of this work, she has to run several simulations of [something].
Her program takes several hours to run.
She has proflied her program and found out that a tight inner loop
takes 95% of the time, etc.

> Lola was just hired by a company/institute to help prepare the purchase of a multi-million experiment. She is tasked to research what temperatures may occur in the lab room, where the device will be installed, as the experiment will produce wrong results if overheating and all budget was invested invain. For this, she has a 2D steady-state heat transport simulation setup that will give her predictions through the year, i.e. what temperatures to expect at a given hour of the day. After she analyses the data at hand, a collaborator from a neighboring instute comes around and proposes a "better" algorithm for this kind of simulation. Lola now has to analyse both datasets and compare the predictions to the actual measuremets she has. On top, she needs to update her knowledge about the highest temperature that can be produced in the lab.
