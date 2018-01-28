
# Generalized Linear Models {#glm}


## BACKGROUND
Up to now, we have dealt with models that assume normally distributed residuals (first row in Figure 8-1). Sometimes the nature of the outcome variable makes it impossible to fulfill this assumption as might occur with binary variables (e.g., alive/dead, a specific behavior occurred/did not occur), proportions (which are confined to be between 0 and 1), or counts that cannot have negative values. For such cases, models for distributions other than the normal distribution are needed; such models are called generalized linear models (GLM). They consist of three elements: the linear predictor, the link function, f, and the error distribution.
