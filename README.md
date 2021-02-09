# Movie Script Coreference Annotation

This repository contains the annotation guidelines for coreference annotation in movie scripts. 
We use Nils Reiter's [CorefAnnotator](https://github.com/nilsreiter/CorefAnnotator) annotation tool to label character mentions.

## Setup

The annotation tool requires Java, and has been tested with OpenJDK 11.

Download [CorefAnnotator](https://github.com/nilsreiter/CorefAnnotator/releases/tag/v1.14.3) with `wget https://github.com/nilsreiter/CorefAnnotator/releases/download/v1.14.4/CorefAnnotator-1.14.4-full.jar CorefAnnotator.jar`

Run the coreference annotation tool from the terminal with the command `java -jar CorefAnnotator.jar`

## Instructions

Please read the annotation and tool-usage instructions from [Guideline.pdf](Guideline.pdf).
The repo includes a sample XMI file that you can open to view the already-annotated coreference chains.
We encourage you to play around with it and get a feel of the annotation task!

## References

Nils Reiter. CorefAnnotator - A New Annotation Tool for Entity References. In Abstracts of EADH: Data in the Digital Humanities, December 2018. DOI: 10.18419/opus-10144