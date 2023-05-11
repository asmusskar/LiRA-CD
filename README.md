# LiRA-CD
Live Road Assessment Custom Dataset (LiRA-CD) is an open-source dataset for road condition modeling and research. The aim of this dataset is to provide researchers and pavement engineers with a vehicle dataset that is open-source and suitable for developing large-scale road condition monitoring methods. Specifically, this dataset focuses on linking in-vehicle sensor data collected by regular cars to standard road condition parameters utilized by public road agencies (i.e., parameters used as input for planning and management of road networks). 

The LiRA-CD contains 1796 kilometer of road data from highway and urban roads in the Copenhagen area collected during the LiRA project (see e.g., [Pettinari et al. (2020)](https://lira-project.dk/) and [Levenberg et al. (2021)](https://doi.org/10.1177/03611981211016852). It includes more than 50 in-vehicle sensors signals from Renault Zoe electric cars operated by GreenMobility (GM) and 92 road condition parameters collected with standard vehicles operated by the Danish Road Directorate (DRD).

<div>
<img src="images/dataset_overview.jpg" width="60%">
</div>
<p>
 <b>Figure 1:</b> Graphical outline of the data collection and data infrastructure in the LiRA project. 
</p>

## Data description

| Software    |   R1    |     R2   |    R3   |    R4   |  R5   |     R6   |  R7     |    R8  |
|-------------|---------|----------|---------|---------|-------|----------|---------|--------|
| BISAR       |   0.7   |    -120  |    1    |   217   | 0.4    |   -78   |  -10    |  205 |
| KENLAYER    |   0.7   |    -120  |    1    |   216   |   0    |   -78   |  -10    |  205 |
| GAMES       |   0.7   |    -119  |   11    |   217   |   0    |   -77   |   -1    |  205 |
| ALVA ('Slip') |   0.7   |  -119.5  |  0.7    | 216.5   | 0.3    | -77.8   | -9.7    |204.7 |
<p>
<b>Table 5</b>: Reference pavement system subjeceted to a single wheel load - unbonded interface between layer 1 and 2, bonded interface between layer 2 and 3.
</p>


## Installation
* Download the package on your PC.
* Open file explorer or similar
* Go to the directory 'LiRA-CD'

## How to contribute
*	If you find a bug in the code: open an 'issue' to notify contributors and create an official record.

# References
Alstrøm et al. (2023). LiRA -- Live Road Assessment. Technical University of Denmark. Dataset. https://doi.org/10.11583/DTU.c.6337148 

Skar, Asmus and Alstrøm, Tommy (2023). Live Road Assessment Custom Dataset (LiRA-CD). Technical University of Denmark. Dataset.

Skar et al. LiRA-CD: An Open-Source Dataset for Road Condition Modeling and Research. Data in Brief, in review
