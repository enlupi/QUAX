- Andrea De Vita
- Enrico Lupi
- Manfredi Miranda
- Francesco Zane

-----------------------

# QUAX Data Analysis

Final project for *Laboratory of Computational Physics (Mod. B)* course, Physics of Data degree at University of Padova.

## Abstract

The axion is a hypothetical particle introduced to solve the strong CP problem of Quantum Chromo Dynamics. It is speculated that axions may also constitute the dark matter content in our galaxy. The [QUAX](https://www.pd.infn.it/eng/quax/) (QUaerere AXions) experiment aims at detecting this particle by using a copper cavity immersed in a static magnetic field of 8.1 T, cooled down at a working temperature of about 150 mK.

In this work we present the results of the analysis conducted on [the search for galactic axions](https://arxiv.org/abs/2304.07505). The data collected by INFN is analysed using the same procedure followed by the [LHC for the Higgs boson search](http://cds.cern.ch/record/1379837/?ln=it),

## Repository Structure

The aforementioned files are available in the **References** folder, while the analyzed INFN dataset is contained in **datasets** as Excel files.

As the name suggests, the **SingleRun** folder contains the results of the analysis conducted on a single run of data taking, i.e. with only one setting for the cavity frequency. Inside, **prepData.ipynb** explains the procedure to take and prepare the data from the raw Excel files for the following analysis,  **fitFunc.ipynb** illustrates the functions for the background and signal fit while **Statistics.ipynb** describes the actual statistical procedure; lastly, **SingleRunAnalysis.ipynb** shows the obtained results.

The **MultipleRunAnalysis** folder cobtains the same elements and analysis as **SingleRun**, but adapts them to work simultaneously on the whole dataset with different cavity frequency settings.
