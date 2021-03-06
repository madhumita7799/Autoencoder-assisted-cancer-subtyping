# Autoencoder-assisted-cancer-subtyping
Capturing the latent space of an autoencoder for multi-omics integration and cancer subtyping

# Abstract
Background and Objective: The motivation behind cancer subtyping is to identify subgroups of cancer patients withd istinguishable phenotypes of clinical importance. It can assist in advancement of subtype-targeted based treatments. Subtype identification is a complicated task, therefore requires multi-omics data integration to identify the precise patients' subgroup.  Over the years, several computational attempts have been made to identify the cancer subtypes accurately using integrative multi-omics analysis. Some studies have used Autoencoders (AE) to capture multi-omics feature integration in lower dimensions for identifying subtypes in specific types of cancer. However, capturing the highly informative latent space by learning the deep architectures of AE to attain a satisfactory generalized performance is required. Therefore, a novel AE-assisted cancer subtyping framework is presented that utilizes the compressed latent space of a Sparse AE neural network for multi-omics clustering.

Method: The proposed framework first performs a supervised feature selection based on the survival status of the patients. The selected features from each of the omic data are passed to the AE. The information embedded in the latent space of the trained AE neural networks are then used for cancer subtyping using Spectral clustering. The AE architecture designed in this study exhaustively searches the best compression for multi-omics data by varying the number of neurons in the hidden layers and penalizing activations within the layers.

# Related Article 
Madhumita and Sushmita Paul, Capturing the Latent Space of an Autoencoder for Multi-omics Integration and Cancer Subtyping,Computers in Biology and Medicine, pp. 1-23, 2022. https://doi.org/10.1016/j.compbiomed.2022.105832 

