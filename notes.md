* configuration
* code
* experimental data
* plots
* documentation


Talk heavily based on Philip Stark's talk and work from Lorena Barba's group


How do we verify a scientific claim?

Either:
- we need to be able to *reproduce* the experiment
- we need to be able to *replicate* the experiment

What's the difference between reproduction and replication?

“The replication of scientific findings using independent investigators, methods, data, equipment, and protocols has long been, and will continue to be, the standard by which scientific claims are evaluated.

However, in many fields of study there are examples of scientific investigations that cannot be fully replicated because of a lack of time or resources. In such a situation, there is a need for a minimum standard that can fill the void between full replication and nothing.

One candidate for this minimum standard is “reproducible research”, which requires that data sets and computer code be made available to others for verifying published results and conducting alternative analyses.

Source: dx.doi.org/10.1093/biostatistics/kxp014

So we have: replication > reproduction > nothing

What happens if we do nothing?
- http://retractionwatch.com/2016/09/26/error-in-one-line-of-code-sinks-2016-seer-cancer-study/
- rampant sofware errors  dx.doi.org/10.12688/f1000research.5930.2
- TODO: more examples of problems

Reproducibility
---------------

If we attempt the experiment and get different results, why did that happen?
- the result is intermittent or it was a statistical fluke
- we did something differently compared to the original experiment (that is, the experiment is sensitive to some undocumented/undiscovered parameter)

What could go wrong?

Talk about Lorena Barba's flying snakes
- explain flying snakes: angle of inclination generates lift and creates von Karman vortex streets



Talk about my own experience reproducing Schaer's horizontal advection test
- show Schaer's original plot
- show plots of before/after


Replicability
-------------

In order to replicate a computational experiment we must control those parameters to which the experiment is sensitive.  These might include:
* model configuration parameters
* model version
* post processing steps
* visualisation (e.g. contouring)

Too much atmospheric science is "trust me" instead of "show me" (borrowed from Philip Stark)
We have access to:
- textual documentation
- "supplementary" material
- maybe the model
- maybe the data
- maybe the processing and plotting scripts


Open up for discussion
----------------------

- Have people encountered problems trying to reproduce or replicate existing results?
- Could someone reproduce or replicate your own work?  How easily?


What can we do about it?
------------------------

- reviewers should ask that code, configuration and data be made available
- automate more:
  - git/github, zotero
  - automated testing 
  - automate your processing workflows
  - wholetale
  - Lorena Barba's "reproducible packages"
- an incentive to make code replicable
  - journals that accept code and data, e.g. Geoscience Data Journal
  - ReScience
  - depsy

