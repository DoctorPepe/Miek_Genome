# Miek_Genome
Annotated Genome for the Actinobacteriophage Miek

## Data Availability
PhagesDB Entry:
https://phagesdb.org/phages/Miek/

GeneBank Entry:
https://www.ncbi.nlm.nih.gov/nuccore/OQ938581

## Annotation Process
Gene prediction was accomplished using DNAMaster v5.23.6 with integrated predictive algorithms Glimmer v3.02b and GeneMark v4.28. Automatic gene calls were validated manually using parameters including predicted coding potential, ribosome binding sites scores, and sequence similarity to known proteins using BLASTp. GeneMark.hmm version 2.5p with Streptomyces_scabiei_87_22 as the selected species was used to further support start site calls. Functional annotations were also generated manually using BLASTp, Phamerator v3.0, and HHPred v57v87, and were only called with significant support.

The exact support behind each predicted protein coding gene and functional assignment can be found in the attached spreadsheet.
