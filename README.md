# LiRA-CD
Live Road Assessment Custom Dataset (LiRA-CD) is an open-source dataset for road condition modeling and research. The aim of this dataset is to provide researchers and pavement engineers with a vehicle dataset that is open-source and suitable for developing large-scale road condition monitoring methods. Specifically, this dataset focuses on linking in-vehicle sensor data collected by regular cars to standard road condition parameters utilized by public road agencies (i.e., parameters used as input for planning and management of road networks). 

The LiRA-CD contains 1796 kilometer of road data from highway and urban roads in the Copenhagen area collected during the LiRA project (see e.g., [Pettinari et al. (2020)](https://lira-project.dk/) and [Levenberg et al. (2021)](https://doi.org/10.1177/03611981211016852). It includes more than 50 in-vehicle sensors signals from Renault Zoe electric cars operated by GreenMobility (GM) and 92 road condition parameters collected with standard vehicles operated by the Danish Road Directorate (DRD). A Graphical outline of the data collection and data infrastructure is shown in </b>Figure 1</b>. The full dataset collected in the LiRA project, i.e., the ‘LiRA Data Warehouse’ can be accessed from [Alstrøm et al. (2023)](https://doi.org/10.11583/DTU.c.6337148).

<div>
<img src="images/dataset_overview.jpg" width="60%">
</div>
<p>
 <b>Figure 1:</b> Graphical outline of the data collection and data infrastructure in the LiRA project. 
</p>

## Data description
In-vehicle sensor signals from the Renault Zoe electric car (.hdf5), video recordings from the Renault Zoe electric car (.mp4), high-resolution reference data from standard surveying vehicles (.csv)

In-vehicle sensor data (.hdf5 and .txt) were collected with a AutoPi Telematics Unit (3rd generation) connected to the vehicle's controller area network (CAN) bus. This unit includes a single-board Raspberry Pi computer with added GPS and accelerometer modules.

Videos (.mp4) were collected with GoPro cameras mounted (outside) on the car chassis (on the hood or over the wheels).

Reference data (.csv) were collected from standard vehicles operated by the Danish Road Directorate (DRD). The surveying included: (i) P79 Profilometer – a van equipped with a beam hosting 25 point lasers that measure longitudinal and transverse profiles; (ii) ARAN9000 – a multi-functional road scanning vehicle that quantifies road defects and distresses using cameras and a Laser Cracking Measurement System (LCMS); and (iii) VIAFRIK – a skid resistance device complying with CEN/TS 15901-5 standard.

In-vehicle sensor data were collected and synchronized automatically with a computer connected to the vehicle's controller area network (CAN) bus and then transmitted to a cloud-based system before being stored in the database

A detailed description of the data, experimental design and methods can be found in [Skar et al. (2023)]

## Installation
* Download the package on your PC.
* Open file explorer or similar
* Go to the directory 'LiRA-CD'

## How to contribute
*	If you find a bug in the code: open an 'issue' to notify contributors and create an official record.

# References
Alstrøm et al. (2023). LiRA - Live Road Assessment. Technical University of Denmark. Dataset. https://doi.org/10.11583/DTU.c.6337148 

Skar, Asmus and Alstrøm, Tommy (2023). Live Road Assessment Custom Dataset (LiRA-CD). Technical University of Denmark. Dataset.

Skar et al. LiRA-CD: An Open-Source Dataset for Road Condition Modeling and Research. Data in Brief, in review
