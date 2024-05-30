This code is the program implementation of the article of  Wenqiang Yang, Wenyuan Wu, Greg Reid's article "Embedding Method by Real Numerical Algebraic Geometry for Structurally Unamenable Differential-Algebraic Equations”. It is based on the MAPLE software. 


To facilitate comparative experiments and demonstrate the advantages of the examples, Oki Taihe's program code is used, and numerical solutions for DAE are implemented based on the same DAE solving environment and program in Matlab.
Therefore, to achieve the effects of all the examples in this article, it is necessary to input the regularized equations obtained from the embedding method into Matlab software for numerical solution, which involves the use of additional toolkits: 

(1) Solution code for nonlinear DAE: Oki Taihe's（https://github.com/OptMist-Tokyo/DAEPreprocessingToolbox. ）. 

(2) Solving all consistent initial values of polynomial constraints: Using the Homotopy Continuation Algorithm HOM4PS-2.0 by Li Zongling（https://www.math.nsysu.edu.tw/~Leetsung/) for solving. It should be noted that the home4ps2.bat file and bin folder should be installed in the folder of the Embedding method in MAPLE. 


This code provides the code and experimental results for all the examples involved in the article. Users can implement it themselves based on the flowchart for further work. 


If you have any questions, you can contact us at email address: yangwenqiang@cigit.ac.cn. 

