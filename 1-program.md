---
layout: default
title: Program
nav: true
---

- Monday June-25 to Thursday June-28
- website http://bit.ly/manwg18
- repo https://github.com/WestGrid/manitobaSummerSchool2018
- announcement and registration opening around May-01
- rooms: EITC E2-320 and EITC E2-330 (Engineering and Information Technologies Centre); these are side by
  side, 80 people each, no desk power sockets; also have Westgrid room E2-528 (10 people max) two floors
  above these

## Program

| date and time | lecture theatre | smaller classroom |
| ------------- | --------------- | ----------------- |
| Mon **25th** morning | *Introduction to HPC* by Alex Razoumov | |
| Mon **25th** afternoon | *Introduction to HPC* by Alex Razoumov (cont.) | |
| Tue **26th** morning | *Parallel programming in Chapel* by Alex Razoumov | *Singularity* by Grigory Shamov |
| Tue **26th** afternoon | *Parallel programming in Chapel* by Alex Razoumov (cont.) | |
| Wed **27th** morning | *Intro to Molecular Dynamics* by Ali Kerrache | MATLAB by Mathworks |
| Wed **27th** afternoon | *Intro to Molecular Dynamics* by Ali Kerrache (cont.) | MATLAB cont.? |
| Thu **28th** morning | *Basics of scientific visualization with ParaView* by Alex Razoumov | |
| Thu **28th** afternoon | *Large-scale remote visualization with ParaView* by Alex Razoumov | |
{:.mbtablestyle}

&nbsp;

## Action items

**Alex:**
- talk to Jana about coffee breaks

**Grigory:**
- confirm that the U allows us to charge fees
- talk to "the CS professor"

## Other possible courses

Grigory Shamov
- Torque-to-Slurm migration (say as part of a larger Intro to CC HPC session)
  - Alex: could be a simple set of slides / cheat sheet for Torque-to-Slurm command translations
- perhaps some other things

Ali Kerrache
- OpenMP
- perhaps some other things

"One senior and important CS professor"
- intro to parallel programming in general? **need to find the specific topic**

MATLAB
- Many Matlab users on grex. A popular support topic here is how to compile Matlab into MCR's to run on
  clusters. There is a campus-wide license (not TAH, some of the toolkits and tools are limited: a single
  seat of the mcc compiler). For a course might need temporary licenses.

bioinformatics
- in an "intro to HPC" session last year, about 15 microbiologists attended and asked a lot of questions
  about "Web-based genomics computing"
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
- David Morais: Can you tell me a bit about your need? Galaxy is not currently on Cedar or Graham, but we
  are able to create galaxy instances for users without CC credentials. Those instances are suitable for
  course and small workshops. Right now Galaxy runs from Mp2 (through GenAP) and from a standalone server
  (the one I mention above). Let me know what you need and we can provide support to your workshop.

Miscellaneous

- HPC Python
- other high-level programming languages (MATLAB, Julia)
- hybrid programming with MPI+OpenMP
- GPU programming with CUDA and OpenACC
- Jupyter notebooks and scientific computing in Python
- CC cloud
- Hadoop, Spark, data science
- MPI (probably not since we'll have Chapel)
