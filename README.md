# RouaultFlemingLocalGlobal

This repository contains analysis code for the following paper: 
Rouault M. & Fleming S. M. Formation of global self-beliefs in the human brain. (2020)

Script and data files are included in the repository to enable replication of data analyses and generation of the figures in the paper.
The folder DATA contains anonymised behavioral data files for the fMRI experiment and the following metacognition experiment outside of the scanner, providing the summarised individual data for the main plots and statistics of the paper: 

•	MainExp.mat (fMRI experiment)

•	MetacogExp.mat (Metacognition experiment, outside of the scanner)

•	auroc.mat (Metacognition experiment, outside of the scanner, gives the type2-area under the ROC curve; Maniscalco & Lau, 2012)

The folder SCRIPTS contains two main scripts to enable replication of statistical analyses and generation of the figures for each of the experiments in the paper:

•	BehaviorMainExp.m

•	BehaviorMetacogExp.m

The folder SCRIPTS also contains a number of helper scripts, for instance for ANOVA and regressions.
To measure metacognition, we make use of previous work. Metacognitive efficiency can be measured by analysing the correspondence between accuracy and confidence, for instance using a signal detection theoretic metric, meta-d' (http://www.columbia.edu/~bsm2105/type2sdt/) (Maniscalco & Lau, 2012). Metacognitive efficiency can also be estimated hierarchically (https://github.com/metacoglab/HMeta-d) (Fleming, 2017).

License.

This code is being released with a permissive open-source license. You should feel free to use or adapt the utility code as long as you follow the terms of the license, which are enumerated below. If you make use of or build on the analyses, we would appreciate that you cite the paper.
Copyright (c) 2020, Marion Rouault
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

