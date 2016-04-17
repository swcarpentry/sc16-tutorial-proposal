
# Detailed description of the proposed tutorial

Here are some points to develop the detailed description.

* Researchers enter HPC for primarily two reasons:
their data is too big to fit on their personal machines or lab workstations,
and/or their code takes too long to run.

* The next step is usually to get access to a campus HPC resource
(or cloud resource?).

* Either their software is parallel enabled, or they need to
implement parallel functionality. Coursework and online materials cover
MPI, OpenMP, CUDA, Hadoop whatever.

* In between, they must learn how to access the facility, how to get their data in and out,
and how to access software available there. This training is generally provided by the site HPC providers.
sysadmins, research support staff or HPC "facilitators".

* But we cannot ignore the fact that for many users,
this is also the first point of contact with a command-line interface.
They are generally going from a tightly-coupled workflow environment,
to one in which preprocessing, computation and analysis of results are de-coupled.
(They may not see the value in this, and we must bring it out)
Task automation - which may not have been a part of their workflow so far - is now
*key* to effective cluster use.

* So before users are ready to take advantage of HPC resources successfully,
they need exposure to concepts like: 
    - command line v/s gui (task automation)
    - profiling instead of guessing?
    - testing and ensuring correctness?
    - interacting with HPC resources (logging in, data transfer)
    - understanding cluster structure (hardware, schedulers, policies)
    - configuring environment and software
    - queues and batch scheduling: submit-and-forget

* That's the role that HPC Carpentry will play.
The targeted audience are researchers and students that are entering
HPC. Very few prerequestites, namely:

    - some experience with the unix shell
    - some experience with programming
    - domain expertise (they know what they want to use the HPC resource for, but not *how* to use it)

* (For SC '16, another audience that may be interested are HPC trainers themselves)

* This course will be delivered by SWC instructors, who

    - have some exposure to ideas of educational psychology and instructional design
    - are enthusiastic about teaching computing
    - in touch with best practices in respective fields
    - frequently teach together in teams
    - have lots of experience teaching novices, and creating a comfortable environment for novice learners
