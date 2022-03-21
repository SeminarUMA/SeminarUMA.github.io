# Previous seminars

Here is a collection of abstracts and slides from all the previous seminars.

# 2022


### March

 - March 18th -14h (Salle 2329)

Speaker : Dorian LEREVEREND

Title :"Inverse Problems Applied to Spatialized Audio"

Abstract : "The ability to identify the directions of incidence of the sounds we hear is the result of an empirical learning of acoustic phenomena since our earliest childhood. When we listen to a recording with headphones, the identification of sources is no longer possible because the sound arrives directly in our ears and does not undergo the same perturbations as during natural hearing. Immersion in a virtual sound scene requires processing the sound signal to reproduce the diffraction phenomena caused by our body. To do this, it is possible to measure (or calculate) its acoustic response and to build an audio filter, called HRTF (Head Related Transfer Function). Having a powerful solver for the direct problem, we are interested in two associated inverse problems: Given a bounded open domain and its HRTFs, what is the boundary condition? Given HRTFs and a boundary condition, what is the shape of the domain?"




### February

 - February 25th -14h (Salle 2329)

Speaker : Rose-Cloé MEYER

Title : Mathematical modeling and simulation of waves in conducting poroelastic media using HDG method.

Abstract : " Near-surface exploration using wave propagation poses significant challenges and has been investigated for many years. Classically, for computational reasons, wave propagating in the subsurface are modeled as solutions to the elastic or acoustic equations. However, to improve the accuracy of the simulation, it is now necessary to consider more complex models such as conducting poroelasticmedia. The poroelasticmaterials are composed of an elastic solid frame and pores filled with fluid.  And the wave propagation is described by Biot’s model. In geophysical materials, when the fluid inside the pores is polarized, we can observe conversions between electromagnetic and seismic fields, which are called electrokinetic effects and are modeled using Pride’s equations, a coupling between Maxwell’s and Biot’s equations. The electrokinetic coupling has been observed in natural geophysical media both in laboratory experiments and on the field. The converted waves are very interesting because they are heavily sensitive to the medium properties, and the seismoelectric conversions could for example help to locate interfaces in the material that seismic waves cannot detect. The characterization of poroelastic or conducting poroelastic media is complex and involves many physical parameters, some of which depend non-linearly on the frequencies. In addition, the seismic and electromagnetic speeds are significantly different, which is complicated to handle for time domain simulations. Hence, we have chosen to solve the equations in the frequency domain and to use a Fourier transform to generate the seismograms in time domain. The main drawback to this is that we must invert one global linear system for each frequency, and this has a large computational cost because of the complexity of the equations and hence the high number of unknowns. We present the development and implementation of a Hybridizable Discontinuous Galerkin (HDG) method for solving Pride’s equations. We validate the code in two dimensions in circular geometry thanks to analytical solutions that we have developed. Using these analytical solutions, we show that the methods have an optimal order of convergence. In addition, to extend the method to infinite domains, we propose new radiation boundary condition for poroelastic equations and electrokinetic equations. We have also implemented Perfectly Matched Layers and we have compared the performances of the two methods. Finally, we show that the code we have developed is capable of modeling electrokinetic conversions in the time domain."



### January

- January 28th -14h (Online)

Speaker : Amond ALLOUKO

Title : "Approche modale hybride semi-analytique/ éléments finis pour le contrôle non destructif de matériaux composites avec les ondes guidées élastiques"

Abstract : "La thèse a pour but de développer un modèle hybride 3D utilisant la méthode des éléments finis pour le contrôle santé intégrée des plaques composites avec les ondes guidées élastiques.  Cette thèse comporte deux aspects, d’une part la propagation des ondes élastiques dans la partie homogène du guide d’onde (matériau), réalisée avec une méthode semi-analytique dénommée « méthode des pinceaux », d’autre part, l’interaction de l’onde avec un défaut localisé (hétérogénéité local) dans le guide, utilisant la méthode des demi-espaces raccordés (HSM). La HSM est une méthode semi-analytique utilisant des éléments finis et des opérateurs intégraux analytiques pour résoudre des problèmes de diffraction d’ondes dans des domaines non bornés. L’évaluation numérique des opérateurs intégraux susmentionnés en champ lointain représente un challenge tant en matière de cout, qu’en matière de précision de calcul. Les travaux réalisés essentiellement dans la HSM ont permis d’introduire deux nouveaux outils pour améliorer l’évaluation numérique : la phase stationnaire et la déformation du contour dans le plan complexe. Ces outils ont été largement validés dans le cas 2D acoustique. L’introduction dans le cas 3D élastique est en cours de réalisation. "




- January 7th -14h (Online)

 Speaker : Quentin GOEPFERT
 
 Title : "A small trip into homogenization and echo imaging."

 Abstract : [here](https://seminarUMA.github.io/PDF/Abstract_seminaire_doctorant.pdf)
 

# 2021

### November

- November 26th - 14h (Salle 2320)

  Speaker : Alan TEIXEIRA NICÁCIO DE MESSIAS

  Title : "About low dimension bessel SDES and associated semilinear PDES."

  Abstract : [here](https://alnssr.github.io/PDF/Abstract_Alan.pdf)
  

- November 5th - 14h (Salle 2320)
  
  Speaker :  Etienne PEILLON
  
  Title : "Limiting absorption principle and mixedvariational formulation for resonant Maxwell’sequations in cold magnetized plasma."
  
  Abstract : [here](https://alnssr.github.io/PDF/AbstractEtienne0511.pdf).
  
  Download the slides [here](https://seminarUMA.github.io/PDF/presentation_etienne.pdf).
  
  

### October
- October 8th - 14h (Salle 2320)
  
  Speaker :  Yassine NAGHMOUCHI
  
  Title : "A Branch-and-Cut algorithm for the Proactive Countermeasures Selection Problem."
  
  Abstract : "We consider the Proactive Countermeasures Selection Problem (PCSP). An instance of the PCSP is given by a triplet (G, K, D). Here, G is a directed graph called the Risk Assessment Graph, where the set of nodes is partitioned into a set of attack access points and a set of  asset-vulnerability nodes (to be secured). Each arc of G has a positive weight representing the difficulty of propagation. K is a set of available countermeasures to place on the asset-vulnerability nodes. The placement of a countermeasure on a node increases the weight of its ongoing arcs by the effect of the countermeasure and has a positive cost. D is a positive security threshold vector. The PCSP consists in selecting a set of countermeasures, at minimal cost, such that the security thresholds are respected. A bilevel model, as well as a compact and a path formulation were introduced to solve the PCSP. In this work, we give polyhedral results and a Branch-and-Cut algorithm developed for solving the path formulation as well as some numerical results showing the eciency of the algorithm. "
  
  

### September
- September 17th - 14h (Salle 2329)
  
  Speaker :  Alice Nassor
  
  Title : "A convergent iterative method for global-in-time elastodynamic-acoustic FEM-BEM coupling."
  
  Abstract : "This talk concerns the fluid-structure interaction occurring during the impact of an underwater shock wave on a submerged structure. To simulate the phenomenon an iterative, global-in-time FEM-BEM coupling is studied. The present contribution highlights two possible formulations of this coupling: one based on Neumann transmission conditions at the interface between the fluid and solid domains, and the other based on Robin conditions. We will show the convergence of the Robin scheme and justifying the non-convergence of the Neumann scheme. We will also discuss other possible iterative FEM-BEM coupling method." 
  
  Download the slides [here](https://alnssr.github.io/PDF/Nassor_seminar.pdf).
  
 
### August
- August 2nd - 14h (Online)
  
  Speaker : Pierre Amenoagbadji
  
  Title : "Ondes en milieux quasi-périodiques localement perturbés : le cas unidimensionnel dissipatif"
  
  

### June
- June 30th - 14h (Online)
  
  Speaker :  Othmane Jerhaoui
  
  Title : "Optimal control problems on stratified space."


- June 11th - 14h (Online)

   Speaker :  Akram Beni Hamed
   
   Title : "Comparison between 3D and 1D approaches for the computation of electromagnetic wave propagation in co-axial cables."
   
  

### May
- May 21st  - 14h (Online)
    
    Speaker : Laura Bagur 
    
    Title : "Three-dimensional modeling of seismic and aseismic slip using Fast Boundary Element Methods"
    
    

### April
- April 23th - 14h (Online)
 
   Speaker : Mathieu Verhchère
   
   Title: "Tight linear relaxations for unconstrained polynomial optimization problems."
   
  
- April 2nd - 14h (Online)
  
   Speaker : Markus Wess
   
   Title : "Frequency-Dependent Complex-Scaled Infinite Elements for Exterior Helmholtz Resonance Problems."
   
 
- April 2nd - 14h30 (Online)
 
   Speaker : Damien Chicaud
   
   Title : "Analysis and simulation of time-harmonic Maxwell equations in anisotropic media."

 
