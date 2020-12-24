---
layout: page
title: TOSEC scripts
description: "<b>A set of small simple Ruby scripts used to manage TOSEC datfiles</b> | The Old School Emulation Center | 2018" 
img: /assets/img/tosec_scripts.jpg
github: https://github.com/renatopanda/tosec-scripts
categories: personal
importance: 4
---

Some of the Ruby scripts are:
* datcheck.rb - checks a folder for outdated TOSEC datfiles based on version in filename or dats nested in others
* diffgenerator.rb - generates a list of differences (new/updated/removed) between two folders with TOSEC datfiles. Used to create the descriptions at the end of README.txt of each release
* tosecstatistics.rb - extracts global statistics from a folder containing the 3 TOSEC branches (1 per folder)
* cuechecker.rb - check if something (cue files) is missing
* cueonlyfixdats.rb - strips all files except cues from existing fixdats
* cueunzipper.rb - unzips all cues to folders (since they have always been distributed that way)
