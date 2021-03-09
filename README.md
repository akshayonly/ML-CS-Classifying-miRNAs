# Classifying-miRNA-ML

This is an attempt to classifying miRNA sequences from different species.

**update1** - Working with Homo sapiens and Mus musculus sequences

- Featurization:
  - different kmers counts (1, 2, 3, 4) 
  - GC Content
  - zCurve 
- EDA conclusion:
  - kmers features are not informative, they are leading to high overlaps among two species.
  - Additional features require (Motifs)
