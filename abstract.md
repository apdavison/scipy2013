# Using Sumatra to Manage Numerical Simulations

Andrew Davidson (original developer) and Daniel Wheeler (speaker)

[Sumatra][1] is a lightweight system for recording the history and
provenance data for numerical simulations. It works particularly well
for scientists that are in the intermediate stage between developing a
code base and using that code base for active research. This is a
common scenario and often results in a mode of development that mixes
branching for both code development and production simulations.  Using
Sumatra avoids this unintended use of the versioning system by
providing a lightweight design for recording the provenance data
independently from the versioning system used for the code
development. The lightweight design of Sumatra fits well with existing
ad-hoc patterns of simulation management contrasting with more
pervasive workflow tools, which can require a wholesale alteration of
work patterns. Sumatra uses a straightforward Django-based data model
enabling persistent data storage independently from the Sumatra
installation. Sumatra is a command line utility with a rudimentary web
interface, but has the potential to become a full web-based simulation
management solution. During the talk, the speaker will provide an
introduction to Sumatra as well as demonstrate some typical usage
patterns and discuss achievable future goals.

[1]: http://neuralensemble.org/sumatra/

## Daniel Wheeler profile

Daniel Wheeler's expertise lies in the development and deployment of
software for applied scientific applications. He has a strong
knowledge of numerical algorithms for solving partial differential
equations as well as good skills in using and developing more general
scientific computing tools. He has an extensive background (8 years)
working with python, python/C interfaces and general numerical tool
kits in high performance computing environments. He is one of the lead
developers of the FiPy open-source PDE solver. He has over 40 refereed
journal publications and an h-index of 19.

