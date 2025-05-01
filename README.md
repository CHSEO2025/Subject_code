Aim:
To get the overall Subject_Count from the input file. 

Requiement List:
1.Code language ------> Python version(3.12.7).
2.libraries     ------> * Pandas version(2.2.2),
                        * Numpy version(1.26.4).
3.Input File    ------> **********.

Steps:
* Import the required libraries.
* Load and read the required input file.
* Now list all the required subject columns to which we need to check the value count of the subjects.
* subject_counts = df[subject_cols].stack().value_counts().....
* This gives the individual value (subject) counts, present in the listed columns.

Sample Output:

E      5049
O      4765
PHY    3025
CHE    3025
ECO    2024
M      1720
BIO    1305
POL    1266
HIS    1266
ITE     990
BSM     758   
