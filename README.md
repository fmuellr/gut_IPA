# The gut metabolite indole-3 propionate promotes nerve regeneration and repair

> Published in [Nature](https://doi.org/10.1038/s41586-022-04884-x)
> November 2023

Serger, E., Luengo-Gutierrez, L., Chadwick J.S., Kong, G., Zhou, L., Crawford, G., Danzi, M.C., Myridakis, A., Brandis, A., Bello, A.T., **Mueller, F.** et al. (2022) The gut metabolite indole-3 propionate promotes nerve regeneration and repair. *Nature*  607, pp.585-592.


## Abstract
The regenerative potential of mammalian peripheral nervous system neurons after injury is critically limited by their slow axonal regenerative rate. Regenerative ability is influenced by both injury-dependent and injury-independent mechanisms. Among the latter, environmental factors such as exercise and environmental enrichment have been shown to affect signalling pathways that promote axonal regeneration. Several of these pathways, including modifications in gene transcription and protein synthesis, mitochondrial metabolism and the release of neurotrophins, can be activated by intermittent fasting (IF). However, whether IF influences the axonal regenerative ability remains to be investigated. Here we show that IF promotes axonal regeneration after sciatic nerve crush in mice through an unexpected mechanism that relies on the gram-positive gut microbiome and an increase in the gut bacteria-derived metabolite indole-3-propionic acid (IPA) in the serum. IPA production by Clostridium sporogenes is required for efficient axonal regeneration, and delivery of IPA after sciatic injury significantly enhances axonal regeneration, accelerating the recovery of sensory function. Mechanistically, RNA sequencing analysis from sciatic dorsal root ganglia suggested a role for neutrophil chemotaxis in the IPA-dependent regenerative phenotype, which was confirmed by inhibition of neutrophil chemotaxis. Our results demonstrate the ability of a microbiome-derived metabolite, such as IPA, to facilitate regeneration and functional recovery of sensory axons through an immune-mediated mechanism.

## 16S rRNA amplicon sequencing analysis 

**Methodology:** 
Mice (ages 6-8 weeks) caecum content was collected and faecal DNA was extracted using a Fast DNA SPIN Kit (MP Biomedicals). Libraries were prepared using the 16S Metagenomic Sequencing Library Preparation protocol for sequencing using the Illumina MiSeq2500 System. Data was processed using the DADA2 pipeline to generate amplicon sequence variants (ASVs), which were annotated using SILVA rRNA database version 132. 

As 16S rRNA sequencing provides only taxonomic but not functional observations. Therefore, [Piphillin](https://github.com/dmcskim/pyphillin) was used to predict functional metagenomic data based on annotated genome databases. PUMA-v1.2 was used to annotate the predicted pathway abundances from Piphillin output, and STAMP-v2.1.3 was used to carry out statistical analysis. 

Piphillin analysis was done using the web server (no longer available). Input: ASV abundance tables and FASTA sequencing files. Each group was run separately due to size limitations. 
As Piphillin provides 

## Figures and associated scripts
- Extended Data Fig 4: Piphillin analysis reveals increased abundance of specific metabolic pathways.

- Supplementary data 2: 16S-Seq percentage abundances




