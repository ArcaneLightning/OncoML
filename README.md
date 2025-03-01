# Summary

OncoML is an AI/ML framework for robust cancer drug response prediction based on single-cell RNA-sequencing (scRNA-seq) data. It is calibrated for diverse cell types, and accounts for tumor heterogeneity. In addition to monotherapy response, OncoML can also predict response to combinatorial therapy targeting tumor sub-clones.

**Key features:**

- Predicts cancer drug response from transcriptomic profiles for (1) single-cells, (2) cell clusters (e.g. using [Scanpy](https://github.com/theislab/scanpy), and (3) from bulk analysis.
- Includes a pre-trained model using the [GDSC](https://www.cancerrxgene.org/celllines) database.  
- Reports half-maximal inhibitory concentrations (IC50) as well as predicted cell death percentages for a specific drug dosage.
- Robust to gene expression measurements across diverse platforms, including microarrays, RNA-seq and scRNA-seq.
- Interpretable model.
- Flexibility to train a new model based on other drug response datasets such as CTRP.

# Usage

``git clone https://github.com/OncoML``

CaDRReS-Sc is based on Python 3.x

**Required packages**

- [Pandas]
- [Numpy]
- [TensorFlow]

**Optional package**

- [Scanpy](https://github.com/theislab/scanpy) (for single-cell clustering)

