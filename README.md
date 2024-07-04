# Tutorials on DNA-Foundation Models

## Tutorial 1 Nucleotide Transformer - Fine-Tuning
In this tutorial, we will get introduced to a powerful AI model specifically designed for analyzing genetic information (genomics). 
The model(s), called Nucleotide Transformer (NT), come in different sizes and have been trained on massive datasets. (Dalla-torre et al, 2023)

They can create insightful representations of DNA sequences, unlocking the potential to solve a wide range of problems in genetics.

These problems include predicting,
- chromatin accessibility
- identifying causal genetic variations
- classifying regulatory elements like promoters and enhancers
The useful information captured by the transformers can be directly extracted (probing) or used to further train the models for specific tasks (fine-tuning).

## Tutorial 2 Segment-NT: Inferring embeddings
SegmentNT models utilize a Nucleotide Transformer (NT) core without its language modeling head, replaced by a specialized 1-dimensional U-Net segmentation head.

In this tutorial, we will use SegmentNT models from the GitHub repo and try to infer segments of DNA into probabilities of being a genomic feature. (out of 14)

