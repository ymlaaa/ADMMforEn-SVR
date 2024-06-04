# ADMMforEn-SVR
Paper: Menglei Yang, Hao Liang, Xiaofei Wu and Zhimin Zhang. A Flexible and Efficient Algorithm for High Dimensional Support Vector Regression.

In this paper, we propose the Elastic-net Support Vector Regression (En-SVR) model to address high-dimensional statistical learning problems. A novel and efficient Alternating Direction Method of Multipliers (ADMM) is employed to solve the En-SVR model.

R codes for implementing ADMM algorithm in the "ADMMforEn-SVR.zip".

The ADMMFunction.R file contains a function that is an implementation of the ADMM algorithm used to solve the En-SVR model.

Examples 1-6 are codes for artificial data experiments.

Real 1-7 are codes for real data study.

The file OpenBLAS-0.3.24-x64.zip is a compressed package downloaded from openblas laboratory. If you want to implement accelerated matrix calculation in R, you only need to decompress the compressed package, and then put the decompressed file in the bin folder. Rename the libopenblas.dll file to Rblas.dll, and replace this file with the Rblas.dll file in the x64 query in the bin file in R.
