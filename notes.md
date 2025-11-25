# Notes – NHS Wales Hackathon (Challenge 3: Vaccine Activity)

These notes summarise the work discussed during the NHS Wales Modelling Collaborative Hackathon (November 2025). Our group explored vaccination uptake patterns across Wales and experimented with a simple SPC-style approach to understand how weekly uptake compared to expected behaviour.

We worked with Autumn 2024 and Spring 2025 datasets and reorganised them into a cleaner structure by converting week numbers, removing unused fields and bringing everything into a long Region–Week–Uptake format. From there, we built a baseline using historical data by calculating each week’s mean uptake and the natural variation (sigma). These values were linked to the corresponding regions and priority groups to give us an expected range that new campaigns could be compared against.

To explore SPC ideas, we looked at z-scores, 3σ control limits and a few basic run rules such as sequences of points below expectation, 2 of 3 points beyond −2σ and simple 6-week trends. These helped us think about where behaviour might look unusual without overcomplicating the model.

We also revisited some logistic parameters (L, k and t0) that were fitted for visual exploration, mainly to see how different regions approached saturation during different campaigns. Comparing Autumn and Spring made it easy to notice different uptake trajectories and how priority groups varied across Wales. We produced some early plots and small tables to illustrate these ideas and to support discussions with the team.

These notes represent the early work and discussions from the hackathon and are not a final product, just a summary of what we explored during the sessions.
