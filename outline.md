# Detailed outline of the tutorial

## Content

The workshop is divided into the following three sections:

### The Unix Shell

The aim of this section is not to teach learners basic unix commands,
or syntax for bash scripting,
but rather to motivate them
to **automate tasks and develop pipelines**.
Topics covered will include filesystem navigation and manipulation,
redirection and piping of standard input and output,
file permissions, and shell scripts.

### Cluster structure and scheduling

This section will help learners develop a strong mental model of the cluster,
and how tasks get assigned and executed on the cluster.
Learners will understand how nodes, CPUs, memory, etc., are organized,
and "how it looks like one remote computer when it has a bazillion CPUs and several Terabytes?".
At the end of the section, they will
submit a number of batch jobs for serial, parallel and task array workloads , trace their execution, and examine their results.
Throughout, it will be stressed that different HPC sites
have different setups, schedulers, policies and resources,
and how learners can translate the concepts accordingly.

### Parallel workflows

This section will guide learners through the process of
performing a large HPC simulation,
and a high-throughput analysis of the resulting data.
For this, they will develop the workflow for a specific research scenario,
for example:

> Lola was hired by a research lab to help prepare the purchase of a multi-million dollar experiment.
The experiment is known to fail at temperatures that are too low or too high.
She knows that the temperature changes follow a daily pattern,
and she's written some code to simulate these temperature changes.
After running this code and generating the temperature predictions,
she determines how closely her predictions match the actual temperature readings
she has for every day in the last year.
The simuation would take too long to run
and generate too much data for her lab workstation,
so she will use the local University's HPC facility for this work.

## Schedule

| AM                                                    |               | PM                                                        |               |
|-------------------------------------------------------|---------------|-----------------------------------------------------------|---------------|
| Introduction to HPC and HTC                           |   10 min      | Overview of the research problem                          |   15 min      |
| Remote computers and SSH                              |   10 min      | Importing code and data                                   |   15 min      |
| Introduction to the Unix shell                        |   70 min      | Modules and installing required software                  |   40 min      |
| Break                                                 |   10 min      | Break                                                     |   10 min      |
| Shell scripts and automation                          |   30 min      | Generating data: parallel numerical simulation            |   40 min      |
| Cluster structure, scheduling and resource requests   |   20 min      | Analyzing data: high throughput analysis                  |   40 min      | 
| Submitting and tracking a batch job                   |   30 min      | Wrap-up and discussion                                    |   20 min      |
| **Total time**                                        |   **180 min** | **Total time**                                            | **180 min**   |
