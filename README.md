# GenomicBPE

A Data-driven DNA Sequence Tokenizer

## Description

GenomicBPE is a specialized implementation of Byte-Pair Encoding (BPE) for genomic sequence representation, enabling efficient tokenization and compression of DNA sequences through data-driven vocabulary learning. The learned representations facilitate downstream genomic tasks including functional annotation, regulatory element prediction, and comparative genomics.

## Highlight

- **Adaptive Vocabulary Learning**: Data-driven discovery of frequent nucleotide n-grams
- **High Compression Ratios**: 2.5-3.2× sequence length reduction
-  **Embedding Compatibility**: Generated tokens suitable for neural network training
- **Computational Efficiency**: Optimized for large-scale genomic datasets

## Hyperparameters Tuning
- Our initial exploration of vocabulary size and frequency hyperparameters reveals that BPE achieves **3×** compression with a **2,000-token vocabulary** and **minimum frequency of 5**, representing **1,600bp** sequences using merely **500 tokens**.

![hyperparameter tuning](D:\github\GenomicBPE\bpe_comparison.png)