# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:
### Project Title or Name of the Application	: Isotime
### Section			   	      : 9-Sodium
### Group Members			    : 
1. Dizon, Catrice Daniele D.
2. Bautista, Aubrey Rexie Angel D.
3. Chu, Diorella Ingrid L.
### Date (Proposal Date)  : Nov 19, 2026
### Project Description:

The application quickly computes dozens of rock samples' ages using a consistent, structured system. It addresses the problem of the likelihood of errors and tedious process from manually calculating entire datasets of measurements.

**System Components and Features**

Classes

- MeteoriteSample - This is to store the information of the meteorite sample the student inputs, or the info of any sample they choose from the archive

- DatingCalc - This is to contain all the formulas and commands regarding the meteorite sample (basically all or most of the methods needed)

Main Features

- Contains name of the meteorite sample, stores amount of parent isotope, and saves half-life of said isotope
 
- Calculates the estimated age, and gets the decay curve

Attributes and Methods

- name

- parent_ratio

- half_life

- calculate_age()

- get_decay_curve()

Interaction Between Classes

MeteoritesSample is the data storage and handles the initialization of attributes, while DatingCalc handles all the methods such as computational logic and the formulas needed. The latter accepts the former as input. Separating them makes the program simpler.

Target users

Scientists determining absolute ages for different meteor samples, as well as high school STEM students (or curious/bored people). Relative dating only tells them whether a rock is older or younger than another, but radiometric dating, a kind of absolute dating, that gives a specific age or range. While this method cannot be reliable alone, it helps provide a basis for cross-checking—which ultimately improves accuracy in certain aspects.

Class Diagram

<img width="211" height="318" alt="image" src="https://github.com/user-attachments/assets/1e882c14-5e1a-4d3c-b8ba-62b0a30a4ba9" />

### Goals:

Describe the long term outcomes of your project followed by a couple of objectives to meet the goals stated in this paragraph

- Objective 1:
- Objective 2:
- Objective n:

[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)
