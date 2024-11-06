# GB-RVFL: Fusion of randomized neural network and granular ball computing

Please cite the following paper if you are using this code. Reference: M. Sajid, A. Quadir, M. Tanveer (2024). GB-RVFL: Fusion of randomized neural network and granular ball computing, Pattern Recognition, Elsevier.
DOI: https://doi.org/10.1016/j.patcog.2024.111142

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% 
The experiments are executed on a computing system possessing Python 3.11 software, an Intel(R) Xeon(R) CPU E5-2697 v4 processor operating at 2.30 GHz with 128-GB Random Access Memory (RAM), and a Windows-11 operating platform.

We have put a demo of the “GB-RVFL” and “GE-GB-RVFL” models with the “aus” dataset

The following are the best hyperparameters set with respect to the “aus” dataset

Regularization Parameter c=0.01 , N= 143, actfun = 8

Description of files: 
main.py: This is the main file to run selected algorithms on datasets. In the path variable specificy the path to the folder containing the codes and datasets on which you wish to run the algorithm. 
gen_ball.py: Generation of granular balls 
RVFL.py: Solving the optimization problem

Some part of the code is taken from "Granular Ball Support Vector Machine [1]" paper.
[1] Xia, Shuyin, et al. "GBSVM: Granular-ball support vector machine." arXiv preprint arXiv:2210.03120 (2022).

For the detailed experimental setup, please follow the paper. If you find any bugs/issues, please write to M. Sajid (phd2101241003@iiti.ac.in) and A. Quadir (mscphd2207141002@iiti.ac.in).
