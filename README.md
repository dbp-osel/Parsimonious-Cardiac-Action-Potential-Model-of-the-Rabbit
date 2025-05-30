# Parsimonious-Cardiac-Action-Potential-Model-of-the-Rabbit
This software code provides a model of the rabbit cardiac action potential described in [1]. The model code is written in CellML which is an open standard based on the XML markup language [2]. The model was derived from high-fidelity experimental data from the rabbit (both single cells and during propagation in the isolated whole heart). This model of the ‘parsimonious’ rabbit action potential is very simple with only two currents and three variables, including a novel non-linear phenomenological model of repolarization. The novelty of this model is that it is mathematically identifiable and extremely simple. The model allows a prediction of the dynamical patterns during ventricular fibrillation in the rabbit. For more information about the model please refer to [1]. There are a variety of OpenSource Tools to run this CellML model (see [2]).

The code itself is provided in the two files (representing two types of stimulation: current clamp or voltage clamp):

PR-2016-with-stimulus.cellml for current clamp & PR-2016-with-holding.cellml for voltage clamp

# Regulatory Science Tool (RST) Reference
•	RST Reference Number: RST24CV06.01  
•	Date of Publication: 08/08/2023  
•	Recommended Citation: U.S. Food and Drug Administration. (2023). Parsimonious Cardiac Action Potential Model of the Rabbit (RST24CV06.01). https://cdrh-rst.fda.gov/parsimonious-cardiac-action-potential-model-rabbit  

# Disclaimer
About the Catalog of Regulatory Science Tools  
The enclosed tool is part of the Catalog of Regulatory Science Tools, which provides a peer- reviewed resource for stakeholders to use where standards and qualified Medical Device Development Tools (MDDTs) do not yet exist. These tools do not replace FDA-recognized standards or MDDTs. This catalog collates a variety of regulatory science tools that the FDA's Center for Devices and Radiological Health's (CDRH) Office of Science and Engineering Labs (OSEL) developed. These tools use the most innovative science to support medical device development and patient access to safe and effective medical devices. If you are considering using a tool from this catalog in your marketing submissions, note that these tools have not been qualified as Medical Device Development Tools and the FDA has not evaluated the suitability of these tools within any specific context of use. You may request feedback or meetings for medical device submissions as part of the Q-Submission Program.  

For more information about the Catalog of Regulatory Science Tools, email OSEL_CDRH@fda.hhs.gov.  


This software and documentation (the "Software") were developed at the Food and Drug Administration (FDA) by employees of the Federal Government in the course of their official duties. Pursuant to Title 17, Section 105 of the United States Code, this work is not subject to copyright protection and is in the public domain. Permission is hereby granted, free of charge, to any person obtaining a copy of the Software, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of the Software or derivatives, and to permit persons to whom the Software is furnished to do so. FDA assumes no responsibility whatsoever for use by other parties of the Software, its source code, documentation or compiled executables, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic. Further, use of this code in no way implies endorsement by the FDA or confers any advantage in regulatory decisions. Although this software can be redistributed and/or modified freely, we ask that any derivative works bear some notice that they are derived from it, and any modified versions bear some notice that they have been modified.

References

[1] Gray RA, Pathmanathan P. A Parsimonious Model of the Rabbit Action Potential Elucidates the Minimal Physiological Requirements for Alternans and Spiral Wave Breakup. PLOS Computational Biology, 2016, 12(10): e1005087. doi:10.1371/journal.pcbi.1005087. https://pubmed.ncbi.nlm.nih.gov/27749895/

[2] CellML.Org


