# power-grid-stability-modelling

## abstract

The power grid is a critical infrastructure that provides electricity to homes, businesses, and industries. Despite its design for reliability, power grid failures are still common due to various factors such as natural disasters, equipment malfunctions, solarweather, and cyberattacks. Power grid failures have significant economic and social impacts, including financial loss, public safety concerns, and critical service disruptions. This report explores power grids’ functions and failures, identifies key challenges and opportunities for improving their reliability and resilience, and models power grids to investigate possible failures. Ensuring the stability of the power grid is critical for maintaining reliable power delivery and avoiding negative consequences such as power outages. This report proposes an agent-based power grid simulation that models power capacity, demand, and power sharing between neighbouring nodes to better understand the power grid’s behaviour and prevent or mitigate power outages. The simulation uses NetworkX graphs, where node appearance, edge colour, and labels are crucial in conveying useful and easy-to-interpret information. The simulation considers multiple cities connected to the power grid, where each city’s power demands are represented by a sine wave with given parameters that fluctuate throughout the range of testing. A blackout is classified as a situation where a city receives less than 40% of its desired power, while a brownout occurs when a city receives between 40% to 85% of its desired power. The simulation results show that the ratio between a power grid’s capacity and demand is crucial in determining the stability and reliability of the grid. When the demand for electricity exceeds the power grid’s capacity, the system becomes strained, and the risk of blackouts and brownouts increases significantly. Therefore, ensuring that the grid’s capacity is sufficiently higher than the demand to maintain system stability during peak usage is essential.


You can find the full report about this model in the report in this repo.

This was a team project. Credit to Alex Semenov, Liam Dietrich, Benjamin Rockman and myself Andy Nguyen

You can run the demo file yourself and follow the instruction to learn more about the results of the project
