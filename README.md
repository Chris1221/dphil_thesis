### <p align="center" style="font-size:15px"> Machine Learning Methods for Next Generation Sequencing Data </p> 
### <p align="center"> Applications to MLL-AF4 Leukemia and Demographic Inference
 

 
<p align="center"> Christopher B. Cole
  
<p align="center"> Exeter College
<p align="center"> University of Oxford
<p align="center"> Michaelmas 2021 </p>

<p align="center">
<a href=#><img src="https://img.shields.io/badge/View%20on%20ORA-Official%20thesis%20record-darkblue"></a>
</p> 

As next generation sequencing technologies continue to mature and find applications across genomics, it has become clear that the scale and scope of generated data far exceeds our ability for manual interpretation. Machine learning has shown remarkable success in finding patterns in this data and generating biologically testable hypotheses. In this thesis, I develop and apply machine learning methods which use NGS data to answer outstanding questions in population and functional genomics.
An understanding of the genetic history of global populations has been hindered by a lack of methods capable of inferring directional migration over time. 
I use a sequential Monte Carlo approach (a particle filter) to sample from the posterior distribution of ancestral recombination graphs and infer likely population size and migration histories from whole genome sequencing data.
I apply this particle filter to global sequencing biobanks and uncover an abundance of migration from the ancestors of non-Africans into Africa between 40 and 70 thousand years ago. I show that latent directional migration has broader implications for the inference of population size in gold-standard approaches and explore this migration in the context of African pre-history.
On a cellular rather than population scale, I apply latent Dirichlet allocation to NGS-based chromatin accessibility assays in order to model shared and distinct regulatory pathways between different cell types. I demonstrate the method's utility by recovering known regulatory biology in erythroblast development. I apply this topic modelling approach to understand cis-regulatory element usage in a treatment-resistant leukemia caused by the MLL-AF4 oncoprotein. The results highlight a previously uncharacterized class of enhancer elements depleted in DOT1L-deposited H3 lysine 79 methylation and enriched for PAF1c binding. 
In this thesis, I have developed and applied machine learning approaches to identify patterns in large genomics databases and answer biological questions on both population and cellular levels. 
