Andrea Sacchi Algorithms for Massive Dataset clustering project.

<a target="_blank" href="https://colab.research.google.com/github//alsacchi/clustering-project/blob/master/Sacchi_Andrea.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


# PARAMETERS
| Name | Description | Default Value |
| - | - | - |
| SAMPLE | Enable or Disable sampling | True |
| RANDOM_INIT | Enable or Disable the KMeans++ initialization | False |
| ABSTRACT_VECTOR_LENGTH | Length of the vector that represent an article | 500 | 
| ITERATIONS | Number of iteration for the clustering algorithm | 20 |
| SEED | Random number generator seed | None |

# Optimization for Google Colab
Google colab run time with RANDOM_INTI set to False is ~28 minutes, by setting it to TRUE it's possible to halve the runtime by initializing the algorithm with random centroids.

