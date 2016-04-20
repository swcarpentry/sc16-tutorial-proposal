
# Detailed description of the proposed tutorial

Researchers come in contact with HPC resources when they have:

  * data that is too big to fit on their personal machines or lab workstations,
  * code that takes too long to run

From there, the next step for most researchers is usually to get access to a campus HPC resource.
Ideally, software they are using can be configured to take advantage of
parallel/distributed hardware with little effort.
Many users will need to develop some background in parallel computing;
and learn to apply those concepts via OpenMP, MPI, CUDA or some platform.
Yet another class of users will still run their code serially,
but will leverage HPC resources to run it on several datasets concurrently.
For all the above users, this is a transition in more than just size and scale.
It's also the point at which they are introduced to several new ideas:

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
including research support staff, system administrators, and
research computing facilitators,
and is generally offered as an "orientation" to the site's HPC resource.

HPC Carpentry is an effort to bring together these groups to collaboratively develop
lesson materials and workshop practices to effectively teach researchers
basic lab skills for high performance computing.
Our target audience are researchers (generally graduate students)
that have domain expertise/are developing domain expertise,
but are new to HPC. Prerequesites for the HPC Carpentry workshop are few:
    - some experience with the unix shell
    - some experience with programming
    - domain expertise (they know what they want to use the HPC resource for, but not *how* to use it)

The workshop will be delivered by certified Software Carpentry instructors
who - as part of SWC's instructor training - have demonstrated an understanding of
ideas in educational psychology and instructional design.
As volunteers, instructors are passionate about teaching - and enthusiastic to share with learners
the tools and practices they apply in their own domains.
Instructors teach frequently in teams, and have experience in providing a cohesive workshop experience
and creating a comfortable environment for novice learners.
