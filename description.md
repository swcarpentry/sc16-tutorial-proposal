# Detailed description of the proposed tutorial

<<<<<<< HEAD
In the pursuit of scientific research
that is more correct,
more widely applicable,
or simply needs to be done faster,
many researchers will run into
=======
Many researchers in scientific computing will eventually run into:
>>>>>>> e88686b2e13bdb5f301436e01de74caad103f1ff

  * data that is too big to fit on their personal machines or lab workstations,
  * code that takes too long to run

From here, their next step is usually to get access to a campus HPC resource.
Ideally, software they are using can be configured to take advantage of
parallel/distributed hardware with little effort.
Many of them will need to develop some background in parallel computing;
and learn to apply those concepts via OpenMP, MPI, CUDA or some other platform.
Yet another class of researchers will still run their code exactly as on their own machines but
will leverage HPC resources to run it on several pieces of data concurrently.
For many of the above users, this will be a transition in more than just size and scale.
It's also the point at which they are introduced to several new, unfamiliar ideas:

  * remote v/s local computers
  * command line v/s GUI
  * interactive v/s batch processing
  * decoupled preprocessing, computation and analysis stages

Thus, before they are ready to write and run parallel software,
researchers need to develop a somewhat orthogonal set of skills to do so *effectively*, such as
task automation using the UNIX shell and scripting,
interacting with remote resources,
understanding queues and scheduling,
and managing parallel workflows.
For many researchers, especially those from non-computing fields,
this training is missing from graduate-level coursework.
It is however,
offered by various groups on different sites,
including HPC center staff, system administrators, and
research computing facilitators,
and is generally offered as an "orientation" to the site's HPC resource.

HPC Carpentry is an effort to bring together these groups to collaboratively develop
lesson materials and workshop practices to effectively teach
"basic lab skills for high performance computing".
The target audience for a HPC Carpentry workshop would be
"novice" HPC users, that have:

  * little to no experience with the unix shell
  * some experience with programming
  * domain expertise (know what they want to use the HPC resource for, but not *how* to use it)

Thus, an offering of HPC Carpentry at Supercomputing '16 is relevant to two
audiences:

  1. Novice HPC users as defined above
  2. HPC *trainers* that are interested
  in the "Software Carpentry" approach to delivering workshops

The workshop will be delivered by certified Software Carpentry instructors
who - as part of SWC's instructor training - have demonstrated an understanding of
ideas in educational psychology, and evidences-based instructional design.
As volunteers, instructors are passionate about teaching - and enthusiastic to share with learners
the tools and practices they apply successfully in their own domains.
Instructors teach frequently in teams, and have experience in providing a cohesive workshop experience
and creating a comfortable environment for novice learners.
