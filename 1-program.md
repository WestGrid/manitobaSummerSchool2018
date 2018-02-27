---
layout: default
title: Program
nav: true
---

# Program

Time estimates below are maximum, can be reduced if necessary.

Alex Razoumov
- *Introduction to HPC* (full-day)
- *Chapel* (full-day)
- *Scientific visualization with ParaView* (full-day)

Grigory Shamov (**please put in time estimates for these sessions**)
- Singularity
- Torque-to-Slurm migration (say as part of a larger Intro to CC HPC session)
  - Alex: could be a simple set of slides / cheat sheet for Torque-to-Slurm command translations
- perhaps some other things

Ali Kerrache (**please put in time estimates for these sessions**)
- general intro to Molecular Dynamics
- OpenMP
- perhaps some other things

"One senior and important CS professor"
- intro to parallel programming in general? **need to find the specific topic**

MATLAB
- Many Matlab users on grex. A popular support topic here is how to compile Matlab into MCR’s to run on
  clusters. There is a campus-wide license (not TAH, some of the toolkits and tools are limited: a single
  seat of the mcc compiler). For a course might need temporary licenses.

bioinformatics
- Jamie: in general GenAP / Galaxy on Cedar/Graham would make a great workshop; first contact someone
  from the GenAP team (David Morais from USherbrook); also ask GSC/BNT people
- Grigory: We had users asking for SMRT Link. Galaxy and GenAP portal are also good. Is Galaxy supported
  on Cedar? Is GenAP supported on Cedar/Graham? Last time only worked with MP2, and CalculQebec will
  likely to move it it GP4.
- Jamie: SMRT Link is commercial software, comes with the PacBio sequencers. not sure if/how it works on
  HPC systems, but you could check the docs http://bit.ly/2EXJLAc also not sure if we could find somebody
  with that specific experience to teach it. they do have lots of online training videos.  perhaps all
  this group needs is some support on how to run on CC systems? I still like the idea of a genap
  workshop, but this will be very much different than learning SMRT link. As for where genap is
  available, I’m not really sure so you’d have to ping the genap folks.
- Grigory: If SMRT Link or GenAP is not something that Bioinformatics can help with, how about Galaxy?
  Ata was saying any user can have Galaxy on Cedar? Can we teach it?
- Jamie: Well, perhaps we can start by inquiring about GenAP/Galaxy… (galaxy is a central feature to the
  genap platform, so they go hand in hand). I’ve cc’d David Morais who is co-lead on the bioinformatics
  team and is on the genap team as well. David, can you please answer some of Grigory’s questions?
  i.e. on which CC systems is genap available? and would someone from the genap team be interested in
  teaching a genap/galaxy workshop at the UofM summer school?
- david morais: Can you tell me a bit about your need? Galaxy is not currently on Cedar or Graham, but we
  are able to create galaxy instances for users without CC credentials. Those instances are suitable for
  course and small workshops. Right now Galaxy runs from Mp2 (through GenAP) and from a standalone server
  (the one I mention above). Let me know what you need and we can provide support to your workshop.







Other possible topics
- genomics
  - GenAP portal? is it a better fit for CC audience? Carol Gauthier is GenAP sysadmin
  - GSC?
  - using Galaxy on Cedar?
  - in an "intro to HPC" session last year, about 15 microbiologists attended and asked a lot of
    questions about "Web-based genomics computing"
  - **consult with Jamie Rosner**
- HPC Python
- other high-level programming languages (MATLAB, Julia)
- hybrid programming with MPI+OpenMP
- GPU programming with CUDA and OpenACC
- Jupyter notebooks and scientific computing in Python
- CC cloud
- Hadoop, Spark, data science
- MPI (probably not since we'll have Chapel)
