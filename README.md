# miRNA-maturation-project
This repository contains a Fortran 90 code (miRNA_maturation_project.f90), regarding the Gillespie simulation (Stochastic simulation) for time evolution of 'miRNA-mediated positive and negative feedback loop' in the manuscript, "Impact of competition between precursor and mature microRNAs on gene expression noise", Raunak Adhikary1, Dipjyoti Das1*

1 Department of Biological Sciences, Indian Institute of Science Education and Research Kolkata, Mohanpur, Nadia, West Bengal, 741246, India.

Email: ra19rs093@iiserkol.ac.in

*Corresponding Authors: dipjyoti.das@iiserkol.ac.in

Instructions to obtain the code: Click on the 'Code' menu (green button) and select the 'Download Zip' option from the drop-down menu. Then extract it to any directory on your desktop.

Instructions to run the code: Open the f90 code in an editor. Model parameter values and initial molecule numbers are already given in the code. The user can manipulate those values according to their need. Execute the code using the Fortran 90 compiler. After execution, two data files will be created, 'parameter.txt' and 'output.dat'. Here, 'parameter.txt' will contain the model parameter values provided as input, and 'output.dat' will contain the number of molecules for mRNA, protein, miRNA, and the mRNA-miRNA complex at any time up to the stopping time.
