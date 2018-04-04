---
layout: default
title: Program
nav: true
---

- Monday June-25 to Thursday June-28
- website http://bit.ly/manwg18
- repository https://github.com/WestGrid/manitobaSummerSchool2018
- announcement and registration opening around May-01
- rooms: EITC E2-320 and EITC E2-330 (Engineering and Information Technologies Centre); these are side by
  side, 80 people each, no desk power sockets; also have Westgrid room E2-528 (10 people max) two floors
  above these

## Courses (tentative program)

- <sup>fixed</sup> means the instructor is available only on this date/time (cannot be moved)

| date and time | EITC E2-320 | EITC E2-330 |
| ------------- | --------------- | ----------------- |
| Mon **25th** morning | [*Introduction to HPC*]({{ site.baseurl }}/alex0.html) by Alex Razoumov | [*Intro to Molecular Dynamics*]({{ site.baseurl }}/ali1.html) by Ali Kerrache |
| Mon **25th** afternoon | [*Introduction to HPC*]({{ site.baseurl }}/alex0.html) by Alex Razoumov (cont.) | [*Intro to Molecular Dynamics*]({{ site.baseurl }}/ali1.html) by Ali Kerrache (cont.) |
| Tue **26th** morning | [*Parallel programming in Chapel*]({{ site.baseurl }}/alex1.html) by Alex Razoumov | [*Singularity*]({{ site.baseurl }}/grigory.html) by Grigory Shamov |
| Tue **26th** afternoon | [*Parallel programming in Chapel*]({{ site.baseurl }}/alex1.html) by Alex Razoumov (cont.) | [*OpenMP*]({{ site.baseurl }}/ali2.html) by Ali Kerrache |
| Wed **27th** morning | [*Scientific computing with PETSc*]({{ site.baseurl }}/kevin.html) by Kevin Green | [*MATLAB*]({{ site.baseurl }}/mathworks.html) by Mathworks <sup>fixed</sup> |
| Wed **27th** afternoon | [*Scientific computing with PETSc*]({{ site.baseurl }}/kevin.html) by Kevin Green (cont.) | [*MATLAB*]({{ site.baseurl }}/mathworks.html) by Mathworks (cont.) <sup>fixed</sup> |
| Thu **28th** morning | [*Basics of scientific visualization with ParaView*]({{ site.baseurl }}/alex2.html) by Alex Razoumov | *Intro to Python* by Grigory or Ali |
| Thu **28th** afternoon | [*Large-scale remote visualization with ParaView*]({{ site.baseurl }}/alex3.html) by Alex Razoumov | *Cloud* course |
{:.mbtablestyle}

&nbsp;

**Notes**:
- the University is Ok with charging a nominal registration fee, but need to remove references to
  "external" attendees: just make it $35 to all
- Torque-to-Slurm translation slides/printout will be included into *Introduction to HPC* (up to 30 mins
  for Grigory or Ali)

## Action items

**Alex:**
- email Carol Gauthier about GenAP/Galaxy
- talk to Jana about coffee breaks

**Grigory:**
- talk to Peter Graham (CS faculty): **need to find a specific topic**
- talk to other local faculty
- prepare Torque-to-Slurm translation slides or printout

## Miscellaneous

### MATLAB
- Many Matlab users on grex. A popular support topic here is how to compile Matlab into MCR's to run on
  clusters. There is a campus-wide license (not TAH, some of the toolkits and tools are limited: a single
  seat of the mcc compiler). For a course might need temporary licenses.

### Bioinformatics

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

### Other topics

- HPC Python
- Julia programming language
- hybrid programming with MPI+OpenMP
- GPU programming with CUDA and OpenACC
- Jupyter notebooks and scientific computing in Python
- Hadoop, Spark, data science
- MPI (probably not since we'll have Chapel)
