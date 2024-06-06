# UCI_2024

## Overview 

## Preliminary mateirals and prep
### Installing Python and PhysiCell Studio
* See README at the [studio_template](https://github.com/rheiland/studio_template)
### Background reading 
* [PhysiCell paper](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005991)
* [Rules paper](https://www.biorxiv.org/content/10.1101/2023.09.17.557982v3)
* Watch [video on PhysiCell Studio](https://www.youtube.com/watch?v=jkbPP1yDzME) - slightly out of date, but still very relevant

## Morning talks

### Paul's Talk (link coming soon)
* intro to ABM
* signals and behaviors
* grammar
* examples 

### Heber's Talk (link coming soon)
* Overview of Digital Twins
* Forward and inverse problem in PhysiCell models (uncertainty quantification)
  * Sensitivity Analysis
  * Calibration
* Toy model: Single cell chemotaxis (Quantitative outcomes)
* Immune surveillance in micromestatases (Qualitative outcomes)
* Integration of macro- and micro- scales (Model selection)

## Hands-On Session

###  1:00-2:45 Session 1 -- Paul (link coming soon)
* notion of modeling workflow
  * what's important? -- modeling goal and planning 
  *   identify types
  *   identify fields
  * set up domain and fields
  * set up basic cell defs and base param values / behaviors
  * add rules
  * initial conditions 
  * simualte - look - improve
* signals
* behaviors (careful!!!!) 
* reminder on response functions -- PKPKD
* Walkthrough of PHysICell Studio

* zombies from SMB
  * attack
  * damage --> deth
  * dmagae --> dtype change  

###  2:45-3:15 break 

### 3:00-5:00 Session 2 (link coming soon)
* Basic model: turmo growht
* Mechanofeedback 

* cytotoxic drug <-- transient rules 
* cytostaitc drug <-- rtran
* stromal cell co-option (?)
* better death -- debris release
* macrophages -- eat debris and cels
  * dfdf
* transint vs persistnet changes

* M0, M1, and M2 as state swiching <-- firs tpersistent rule 
  * contact with debris or dead incraeases M1 --> M2.
    * M1 secfete pro-infl
    * M2 secrete anti-infl 
  * mackgroudn M2 --> M1
  * debriss supresses M2 --> M1?  
* Add T cells
  * Effector attack
  * pro-infl increase effecto attack
  * anti-infl turn to 
* add differntiatoin rules

* free-for-all : fake drugs and what-if 
