# CAMP-test-simulator
This simulator was designed to predict the hemolysis phenomenoun in the CAMP test(a classical microbiology test for detecting Group B Streptococcus). 
According to the known hemolysis and biological features of S.a and GBS, we made three assumptions:
1. It was CAMP factor that caused hemolysis, not β-lysin. β-lysin just enhanced the collapse of SRBC membrane.
2. Decompostion of the sphingolipids by β-lysin in SRBC membrane was the prerequsity of enhanced hemolysis.
3. The reaction between β-lyzed SRBC and CAMP factor was proportional and specifical, in other words, what happend here was like reaction between antibody and antigen.

So, it was clear that CAMP test should have shore a similar mode with DID(double Immuno Diffusion test).
However，CAMP test will not reflect the reaction directly with "Immunoprecipitation" like stuffs, instead, CAMP test can merely depict the hemolysis of SRBC.
That is the reason why CAMP test was half-different with DID on the one side but half matched on the other side.

The diffusion of out-membrane proteins is a field diffusion problem at all whose exact spatial extent is unclear(even 2-Dimensional). The traditional object-oriented spatial data model requires an accurate description of the spatial extent of the object and a record of the regional extent using spatial coordinates, whereas the boundary of the field object itself is ambiguous and its change with the extrapolation of time becomes more uncertain. Therefore, the use of an object-oriented data model is not conducive to the representation of the dispersion process of CAMP factor and β-lysin. Of course, the object-oriented data model is not discarded in the course of researching new data models, but exists simultaneously.

