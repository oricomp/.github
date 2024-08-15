# OriComp

An Original Computing experiment.

**OriComp** is an experiment/project about creating an entire computer system
(from hardware to software) entirely from scratch. Everything that can be 
designed from scratch has been designed myself. All standards, specifications,
protocols, etc. (within reason) were created from scratch.

Many designs take inspiration from already existing architectures, standards, 
etc. This project does not propose to be better than current technology, but
rather a test as to whether a complete computer ecosystem can be created from
scratch by one person. For the most part, hardware and software is not
guaranteed to be compatible with anything else. What is compatible is mainly
for ease of development. For example, the majority of software is written in a
language specific to **OriComp**, but Verilog is still used as the HDL because
it would be too large a project to create a new HDL.

## Getting Started

It is recommended that potential users clone 
[the oricomp repository](https://github.com/oricomp/oricomp). This repo
submodules all relevant repositories in **OriComp**, and is meant to organize 
the entire project into one repo. The tip of `main` will have the latest tested
version of the project.

## Documentation

For documentation, check out [docs](https://github.com/oricomp/docs). 
Documentation for every piece of hardware, software, etc. can be found in the
linked repo. The documentation is generated and stored there with every tested
change to [oricomp](https://github.com/oricomp/oricomp). If more up-to-date
documentation is needed for whatever reason, check the `docs` folder in the
repo corresponding to the hardware, software, etc.
