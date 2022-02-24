# TOPSIS
Technique for Order Preference by Similarity to Ideal Solution is a multi-criteria decision making method. The method is based on finding an ideal and an anti-ideal solution and comparing the distance of each one of the alternatives to those. TOPSIS chooses the alternative of shortest Euclidean distance from the ideal solution, and greatest distance from the negative-ideal solution.
## Package Usage
To install the package:
pip install Topsis_Samridhi_101916086
This is a package focusing on finding the topsis score and rank of a dataframe (csv file) with only numerical values except for the first column.
## OUTPUT
The python file consists of the logic which excepts 4 parameter:
1. Input csv file
2. Weights given by user comma separted
3. Impact given by user comma separated
4. Result csv file, just to restore the naming convention.. result file will contain 2 additional columns contianing topsis_score and rank
## LICENSE
Copyright (c) 2022 Samridhi Garg
## To install Package
To install the package:
!pip install python-topsis-Samridhi-101916086==4.1.1
This is a package focusing on finding the topsis score and rank of a dataframe (csv file) with only numerical values and give comma-sep input of weights and impacts.
## To Run from Command-Propmt/ python-IDLE/ editor
from python_topsis_Samridhi_101916086 import *
from python_topsis_Samridhi_101916086 import topsis as tp
f = "input_csv_filepath"
w = "1,1,1,1"
im = "+,+,+,-"
result1 = "result_csv_filepath"
tp.topsis(f,w,im,result1)
The final result can be seen in the result file given as result1.
