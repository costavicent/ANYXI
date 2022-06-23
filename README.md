# ANYXI

The ANYXI stands for the logic Art paiNting stYle eXplainable classIfier. 

The ANYXI classifies paintings into the Baroque, Impressionism, and Post-Impressionism styles. It uses human-understandable color features 
and categorizations based on the art experts’ definitions of the styles, yielding human-friendly explanations of its classification results. 
The interested reader is referred to the following publication for further details on the design of the ANYXI: 
  Costa, Alonso, Falomir, Dellunde: _An Art Painting Style Explainable Classifier grounded on Logical and Commonsense Reasoning_, submitted.

## Contents of this project

**The QArt337 dataset**. This dataset comes out of joining the QArt-Dataset and the Painting-91-BIP dataset. For further details on the QArt-Dataset, the
reader is referred to
   Falomir, Cabedo, Sanz, and Abril (2018): _Categorizing paintings in art styles based on qualitative color descriptors, quantitative global features and
machine learning (QArt-Learn)_. Expert Syst. Appl., 97, 83–94. Retrieved from https://doi.org/10.1016/j.eswa.2017.11.056

For further details on the Painting-91-BIP dataset, the reader is referred to
Costa, Dellunde, and Falomir (2021): _The logical style painting classifier based on Horn clauses and explanations (l-she)_. Log. J. IGPL, 29 (1), 96–119. 
Retrieved from https://doi.org/10.1093/jigpal/jzz029

The QArt337 dataset includes 337 samples of paintings. Each sample is described in terms of the following 12 meaningful color features, described in 
detail in the submitted work referenced at the beginning of this text:

_darknesslevel, nopalenesslevel, contrastlevel, redcolors, diversityofhues, diversityofqcds, bluishlevel, greyishlevel, vividness, warmcolorlevel, 
contrastblueyellowlevel, and contrastredgreenlevel_.

The classification task consists of identifying one out of the Baroque, Impressionism, and Post-Impressionism, in terms of the values given for 
all the 12 selected features. 

**The details on the experimental results of the ANYXI**.

## Usage
