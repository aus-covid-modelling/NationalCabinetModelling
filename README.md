# Modelling for National Cabinet
The Peter Doherty Institute for Infection and Immunity has produced modelling to advise on the National Plan to transition Australia's National COVID response. The technical report associated with this work can be viewed [here](https://www.doherty.edu.au/news-events/news/doherty-institute-modelling-report-for-national-cabinet). This repository contains submodules for each of the parts of the code used to generate the reports.

There are four submodules: TransmissionPotential, AgentBasedModel, ClinicalPathwaysModel and NationalModelPlotting.

## Transmission Potential
The transmission potential code is stored as part of a much larger collection of work relating to situational awareness in Australia, maintained by Prof. Nick Golding, Curtin University. The relevant piece of code for this work is in R/reopening.R.

## Dynamic model outputs
Outputs from the agent based model are fed into the clinical pathways model, and outputs from the clinical pathways model are fed into the national model plotting. Please see the readme in each of these three submodules for more specifics on running these code blocks.
