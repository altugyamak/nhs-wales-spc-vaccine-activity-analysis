# NHS Wales Hackathon – Challenge 3: Vaccine Activity (SPC Analysis)

This repo contains the notes and documentation from my work during the NHS Wales Modelling Collaborative Hackathon (Nov 2025). Our group worked on **Challenge 3: Vaccine Activity**, where we explored how vaccination uptake changes across Wales and tried a simple SPC-style approach to spot unusual weekly behaviour.

## Overview
We used data from previous campaigns (Autumn 2024 and Spring 2025) to build a baseline and compared new campaign data against it. The idea was to check when weekly uptake was within normal variation or falling outside what would typically be expected. In short, we focused on calculating weekly uptake for each region/group, building a baseline (mean + sigma), applying z-scores and 3σ control limits, flagging Green / Yellow / Red points, using SPC run rules to detect trends or unusual patterns, and summarising results using simple tables and example charts. This was a quick proof-of-concept developed during the hackathon sessions.

## Files
[NHS_SPC_Details.pdf](NHS_SPC_Details.pdf) – Full explanation of the SPC workflow, baseline logic, sigma/variation calculation, control limits, run rules, and example output.

## What I Learned
During this challenge, I had the chance to work with real vaccination uptake data and apply an SPC-style approach for the first time. Some of the key things I learned include cleaning and preparing weekly uptake data across multiple regions/groups, building a simple baseline using historical campaign data (mean + sigma), calculating z-scores and understanding how 3σ control limits work, applying basic SPC run rules to spot unusual behaviour, comparing Autumn vs Spring vaccination patterns, communicating findings clearly during quick group discussions, and working in a mixed team with students and NHS Wales analysts. Overall, this challenge helped me understand how statistical monitoring can support real public-health decision-making.

## Future Improvements
If I continue this project, I would like to:
- Automate charts for each region/group  
- Experiment with different baseline windows  
- Add clearer visualisations for deviations  
- Compare additional campaigns if more data becomes available  

## Team
This challenge involved participants from King’s College London, Cardiff University, NHS Wales Modelling Collaborative, and Digital Health and Care Wales (DHCW).

## Notes
This repo is simply a collection of the work completed during the hackathon. It is not a polished product — just early ideas, quick modelling attempts, and documentation from the sessions.

## Contact
altug.yamak@kcl.ac.uk
