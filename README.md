# SARS-CoV-2-molecular-explorer
This repository contains bioinformatic work from my lab in response to the COVID-19 pandemic. 

The file "SarsCov-2_Interactome.cys" is a Cytoscape file (www.cytoscape.org) containing all molecular interactions between SARSCov-2 and human proteins as recently published by the Krogan Lab at UCSF (bioRxiv 2020.03.22.002386; doi: https://doi.org/10.1101/2020.03.22.002386). The file is a heterogeneous network containing 9476 nodes and 73,326 edges. THe net is visualized as a set of concentric circles and a complex network inside. The outermost circle corresponds to the viral proteins (red triangles). The next circle is the human proteins (teal circles) that bind to the viral proteins. The next (third) circle layer is the genes blue circles) encoding the human proteins that interact with the virus. The inner nodes represent drugs (in phase 1-3) that target each protein (purple circles), side effects (light green circles), diseases (red circles), anatomies (green circles), biological process (dark orange circles), cellular component (yellow circles), molecular function (pale orange circles) and cellular pathways (gray circles). 

The network was created by finding first neighbors of each human protein targetted by the virus using SPOKE (https://spoke.ucsf.edu), a knowledge graph containing >5 million nodes and 7 million edges from more than 20 databases. 
Users can Zoom, select and navigate the network to explore the molecular aspects of COVID-19, including drug repurposing efforts, and hypothesis generation. 

This work was done by Sneha Singh, Adil Harroud, James Landefeld, Conrad Huang, Scooter Morris and Sergio Baranzini. 
