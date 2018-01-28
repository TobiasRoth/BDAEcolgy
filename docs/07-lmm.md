
# Linear Mixed Effects Models {#lmm}


## BACKGROUND

### Why Mixed Effects Models?
Mixed effects models (or hierarchical models; see Gelman & Hill, 2007, for a discussion on the terminology) are used to analyze nonindependent, grouped, or hierarchical data. For example, when we measure growth rates of nestlings in different nests by taking mass measurements of each nestling several times during the nestling phase, the measurements are grouped within nestlings (because there are repeated measurements of each) and the nestlings are grouped within nests. Measurements from the same individual are likely to be more similar than measurements from different individuals, and individuals from the same nest are likely to be more similar than nestlings from different nests. Measurements of the same group (here, the “groups” are individuals or nests) are not independent. If the grouping structure of the data is ignored in the model, the residuals do not fulfill the independence assumption.
