# LightBudget project
LightBudget is a collaborative project funded by Nouvelle politique régionale (NPR) and five leading industrial partners active in the Swiss construction sector. The LightBudget seeks design and construction techniques to balance daylight autonomy and whole-life carbon emissions, aligning with net-zero goals. 

# Description
My Rhino-Grasshopper codes generate the 3D energy/daylight simulation model of a vast range of design alternatives for typical Swiss single- and multi-family houses and enable fast and accurate daylight and energy simulations as well as LCA. This repository contains the source code as well as the complementary documents to replicate the results of my prospect article which is under review at the moment.

# Software requirements
The file format is ".gh", which indicates a code developed in Grasshopper. To open the file the user needs to install Rhino3D.
• for Windows: - Rhino 6 or later, in which the Grasshopper is included. 
	             - Rhino 5 and Grasshopper (download Grasshopper for Rhino 5 here: https://www.rhino3d.com/download/Grasshopper/1.0/wip/rc/)
		           - Rhino 4 and Grasshopper (download Grasshopper for Rhino 4 here: https://files.mcneel.com/grasshopper/1.0/2012-09-28/wip/grasshopper_wip_20120928.exe)
• for iOS: - Rhino 5 and later, in which the Grasshopper is included.
The daylight and energy simulations were performed using ClimateStudio v1.8: https://www.solemma.com/climatestudio

# Hardware requirements
To ensure high fidelity within a reasonable timeframe, a core i7-8550U CPU@1.80 GHz processor is required. Running the code on GPU, of course, reduces the simulation time significantly.

# Complementary data
"Samples.xlsx" is a dataset of 9,000 design alternatives generated using Sobol sampling technique ensuring a uniform distribution of discrete values. This file must be loaded on the Grasshopper code to run the simulations.

# How to run the code?
This repository provides two essential codes: "LightBudget_Co-simulation platform_Single-family houses.gh" and "LightBudget_Co-simulation platform_Multi-family houses.gh". To begin, ensure that all necessary software is installed on your system. Then, depending on your focus - whether it's single-family or multi-family houses - open the respective Grasshopper code. Instructions for navigating and using the code are conveniently located on the Grasshopper canvas, guiding you step by step through the process. 

# References
If you utilize this code in your research or project, please cite as follow:
- N Rezaei Oghazi, T Jusselme, M Andersen (2021) Evaluation of daylighting strategies based on their embodied carbon emissions: a first methodological framework and case study, Proceedings of the 17th IBPSA Conference, 1-3 September 2021, Bruges, Belgium.
