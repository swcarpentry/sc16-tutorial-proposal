# Detailed outline of the tutorial

## Content

As described in the "tutorial description" section,
an HPC Carpentry workshop is aimed at novice HPC users with domain expertise,
but little to no experience with the command line or batch computing.
The content of this workshop is designed to help them become productive
in this new environment as quickly as possible.

Accordingly, the workshop is divided in three sections:

1. Introduction to the unix shell and shell scripting
2. Cluster structure and scheduling
3. Parallel workflows

### The Unix Shell

The aim of this section is not to teach learners basic unix commands,
or the syntax of bash scripting,
but rather to motivate them
to **automate tasks and develop pipelines**.
Accordingly, this section will begin by making learners feel
comfortable in a shell environment by having them perform basic tasks
like navigating the filesystem and manipulating its contents.
But the latter half of the section will be focused on concepts
like redirection, piping, shell scripts and file permissions
which are key to effectively using the unix shell and to understanding the "unix philosophy".

### Cluster structure and scheduling

This section will help learners develop a strong mental model of the cluster,
and how tasks get assigned and executed on the cluster.
Learners will understand how nodes, CPUs, memory, etc., are organized,
and "how it looks like one remote computer when it has a bazillion CPUs and several Terabytes?".
At the end of the section, they will
submit a number of batch jobs for serial, parallel and task array workloads , trace their execution, and examine their results.
Throughout, it will be stressed that different HPC sites
have different setups, schedulers, policies and resources,
and how learners can translate the concepts accordingly. The conepts we present will allow learners to quickly apply the techniques to their local clusters.

### Parallel workflows

In this section, learners will be presented with a specific research scenario,
for example:

> Lola was hired by a research lab to help prepare the purchase of a multi-million dollar experiment.
The experiment is known to fail at temperatures that are too low or too high.
So Lola's task is to research the temperatures in a certain section of the lab where the device will be placed.
She knows that the temperature changes follow a daily pattern,
and she's written some code to simulate these temperature changes.
After running this code and generating the temperature predictions,
she determines how closely her predictions match the actual temperature readings
she has for every day in the last year.
The simuation would take too long to run
and generate too much data for her lab workstation,
so she will use the local University's HPC facility for this work.

They will then guide learners through the different steps involved, including
  * data transfer,
  * software and library installation and
  * developing batch scripts to submit jobs for performing the simulation and analyzing the results.

## Schedule

### AM

| AM                                                    |               | PM                                                        |               |
|-------------------------------------------------------|---------------|-----------------------------------------------------------|---------------|
| Introduction to HPC and HTC                           |   10 min      | Overview of the research problem                          |   15 min      |
| Remote computers and SSH                              |   10 min      | Importing code and data                                   |   15 min      |
| Introduction to the Unix shell                        |   70 min      | Modules and installing required software                  |   40 min      |
| Break                                                 |   10 min      | Break                                                     |   10 min      |
| Shell scripts and automation                          |   30 min      | Generating data: parallel numerical simulation            |   40 min      |
| Cluster structure, scheduling and resource requests   |   20 min      | Analyzing data: high throughput analysis                  |   40 min      | 
| Submitting and tracking a batch job                   |   30 min      | Wrap-up and discussion                                    |   20 min      |
| **Total time**                                        |   **180 min** | **Total time**                                            | **180 min     |
