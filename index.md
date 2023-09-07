
Barnard PL (Programming Languages) Labs is run by [Prof. Mark Santolucito](http://www.marksantolucito.com/) at [Barnard College, Columbia University](https://cs.barnard.edu/).

# Current Projects

## TSL

Temporal Stream Logic allows users to give specifications about how a program should behave over time, and then automatically synthesize a program that is guaranteed to meet that specification.

The current goal of this work is build a TSL to Arduino pipeline.

We introduced a [TSL API](https://barnard-pl-labs.github.io/tsl-api/), which puts TSL synthesis on a serverless cloud infrastructure.
This allows easy experimentation with TSL (no local installs) while also not costing us a fortune in server costs.

We built a TSL playground focused on interactive animations called [TSL Move Cube](https://barnard-pl-labs.github.io/moveCube/), which uses the above mentioned TSL API.

We are exploring a [Block-based Editor for Temporal Logic Program Synthesis](https://barnard-pl-labs.github.io/tslBlocks/).
The goal is to lower the barrier-to-entry for users to get started writing TSL specifications for those that are new to the syntax of TSL and temporal logics in general.

We [Interactive Reactive Synthesis for Music Synthesizers with TSL](http://tslsynthesissynthesizer.com/)

We build a synthesis engine for [TSL-MT](https://github.com/Barnard-PL-Labs/temos) (TSL-Modulo theories), which has now been integrated into our mainline [tsltools repo](https://github.com/Barnard-PL-Labs/tsltools), which is used in the serverless TSL deployment.


## Spiral Analysis

The goal of this project is to migrate legacy medical software to a new computing infrastructure, while maintaining some guarentees about its clincally-relevant behvaior.
We are focused on the Spiral Analysis tool from Dr. Seth Pullman's lab, which quantifies upper limb tremor disorders.

(no public link at the moment)

## Static Analysis for IaC

The goal of this project is to build static analysis tools for cost analysis of  Infrastructure as Code (Iac).
In particular, in order to statically predict the costs of a IaC deployment, usage estimates are often provided by users.
This is useful in the case where users want to run a what-if analysis, e.g. what if my website traffic increase 3-fold, what if my website processes half as much data - how will this impact my costs.

(no public link at the moment)

# Publications and archived projects

[Paper list](http://www.marksantolucito.com/research.html)

[Synthesis-enabled Live Coding](http://161.35.14.211/)
