# ATSyRA Nuclear Power Threat Analysis System
A threat modelling tool developed for threat analysis of Nuclear Power Plants using goal reachability computation. Included case studies that are modelled the 2007 Stuxnet attack and 2014 Korean Hydro Nuclear Power attack. 

## Installation 
### Core Functionality 
The project was developed using ATSyRA Studio 3.2.0 which can be [installed here](https://atsyra2.irisa.fr/studio/packages/releases/3.2.0-SNAPSHOT/) (ensure you install the SDK version so all functionality is available). Once ATSyRA Studio is installed you can clone the repository into it by following the steps described in [this tutorial](https://github.com/maxkratz/How-to-Eclipse-with-Github), you now have everything installed!
### Installs for Optional Visualisation
If you wish to use the visualisation system to generate images of NPP models you will need to install Java 11 or Newer (Java 18 was used for development) which can be downloaded and installed either from [this site](https://www.oracle.com/uk/java/technologies/downloads/) or via your system's package manager. If using Windows then a version of GraphViz (the graphics library used for certain diagrams in plantuml) is preinstalled in the PlantUML package which comes included in this repository, if using Linux or MacOS you will need to install GraphViz separately following the steps [described here](https://plantuml.com/graphviz-dot).

## Usage 
There is the possibility to either create your own NPP instances or to perform threat analysis of the defined case studies, this section will give guidance as to how these work in the system.
The working directory for the Nuclear Power Plant threat model is the directory "NPP ABS files"
### Computing Goal Reachability using the Example Case Studies
To perform threat analysis via goal reachability computation, right click on a goal file (the goal files for the provided example case studies are "StuxnetAttackerGoals.abs" and "KHNPAttackerGoals.abs") and then select ATSYRA ABS -> Compute Scenarios (by GAL) from the dropdown menu. 
### Creating NPP Instances 
To create an NPP instance create a new .abs file in the NPP ABS files directory, 
### Creating NPP Behaviours

### Creating Goals for Threat Analysis 

### Visualisation Methods
