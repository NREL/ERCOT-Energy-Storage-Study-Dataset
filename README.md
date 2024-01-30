# ERCOT-Energy-Storage-Study-Dataset
Welcome to the ERCOT Energy Storage Study Dataset repository. This dataset is crafted for the exploration and analysis of both long and short-duration energy storage optimization within a forward-looking ERCOT system. Our dataset originates from the NREL's ReEDS capacity expansion model, projecting the 2035 ERCOT power grid landscape. This future grid anticipates the retirement of aging thermal fuel-based generators and the introduction of new renewable energy sources, including solar and wind, alongside energy storage solutions.

The essence of this dataset lies in its application to study the operational dynamics of long-duration energy storage within a conventional production cost modeling framework. We've distilled the ERCOT system into 7 distinct zones or balancing areas, each with interface limits informed by transmission expansion decisions from ReEDS. To streamline the complexity inherent in modeling, short-duration and long-duration energy storage units are aggregated into a single representative device per balancing area. Table 1 within the repository offers a comprehensive overview of the system's generation mix, providing valuable insights into the future energy landscape of ERCOT.

Data Format and Availability:
The dataset is made available in two formats for user convenience and computational efficiency:

CSV: Detailed generator characteristics, cost parameters, and forecast time series for renewables and load.
PowerSystems.jl: Leveraging NREL's open-source Julia framework, this format is optimized for those utilizing PowerSystems.jl for their analytical work.
This repository is designed to serve as a foundational tool for researchers, analysts, and industry professionals delving into energy storage optimization and grid reliability studies. By providing a realistic yet simplified representation of a future ERCOT grid, we aim to facilitate in-depth analyses and foster innovative solutions in energy storage and grid management.

![image](https://github.com/NREL/ERCOT-Energy-Storage-Study-Dataset/assets/18898869/a48d685f-55be-481a-8ca0-19fbf18cb845)
