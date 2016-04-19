

# Detailed outline of the tutorial

The HPC Carpentry workshop will be a full day (6-hour) workshop,
divided in four 90 minute sections.
Within each section,
there will be alternate 10-15 minute
live-coding demonstrations of a certain concept/procedure,
and 10-15 minute exercise/challenge sections.
Participants will be encouraged to work in teams
for the challenge sections.

## Part 1: Basics of interacting with the cluster

1. Introduction to HPC and accessing the cluster (30-45 min)

  - Discussion of computer components (CPU, storage, memory)

  - Explanation of terminology (nodes, cores, threads, cluster,
    serial/parallel processes)

  - Structure of the cluster (login nodes, job scheduler, etc.)

  - Accessing the cluster with ssh and discussion of cluster
    filesystem set-up

  - **Activity:** practice navigating the filesystem using Unix
    commands – navigate between /home and /groups

2. Transferring files to/from the cluster (20-30 min)

  - Filezilla and scp (macs only)

  - Creating directories, editing and moving files

  - **Activity:** transferring files to/from cluster

3. Queues and partitions/allocations (30 min)

  - Discussion of batch job scheduler, queuing and scheduling (example
    of waiting to be seated at a restaurant)

  - Queue structure and priority

  - Job scheduler commands

  - **Activity:** Start an interactive session, specifying specific
    options (number of cores, notification when job finishes,
    sending output to file, runlimit, etc.)

4. Accessing tools in the cluster by exporting PATH and using modules
  (30-45 min)

  - Explain the PATH variable (15-20 min)

  - Explain modules, discuss module commands (15-20 min)

  - **Activity:** perform blastn or other exercise by exporting to
    the PATH variable

  - **Activity:** perform blastn (or other exercise) by loading the
    blastn module (or other tool)

5. Submission scripts and batch job submission (30 min)

  - Explain required components of a submission script

  - Display how to write a submission script for the blastn exercise
    previously performed

  - Discuss batch job submission

  - **Activity:** Change the submission script to perform batch
    submission of blastn on multiple files and monitor progress of
    job in queue.

  - **Activity:** Submit the same job to a different queue and see
    differences in time to job completion

## Part 2: Workflow and parallel computing practices

6. MPI and multithreading (30 min)

  - Types of parallelism and MPI concepts

  - **Activity:** Submit a script that depends on MPI

7.
