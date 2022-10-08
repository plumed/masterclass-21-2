#  PLUMED Masterclass 21.2: Statistical errors in MD 

This lesson was given as part of the PLUMED masterclass.  It includes:

* A videos that explain the theory covered and a second video which shows you how the exercises should be completed.
* A series of exercises that you should try to complete yourself.
* Some supplementary python notebooks that provide further background information on the exercise.

The flow chart shown below indicates the order in which you should consult the resources.  You can click on the nodes to access the various resources.  Follow the thick black lines for the best results.  The resources that are connected by dashed lines are supplmentary resources that you may find useful when completing the exercise. 

```mermaid
flowchart LR
A[Lecture I] ==> B[Instructions]
A -.-> G[how data was generated]
A -.-> C[template notebook]
B ==> D[Lecture II]
C -.-> D
G -.-> D
D --> E[solution]
D --> F[alternative solution]
click A "data/video1.html" "A lecture that was given on February 1st 2021 as part of the plumed masterclass series that introduces you to the exercises in this lesson" 
click B "data/README.html" "The instructions for the exercises" 
click G "data/notebooks/gendata.html" "A python notebook that shows how the data sets in the files uncorrelated_data, correlated_data and weighted data that are all used in the exericses was generated" 
click C "data/notebooks/template.html" "A python notebook file that explains how you can work on the exercises from a python notebook.  Advice on running PLUMED from a notebook and on plotting the data that is generated is given." 
click D "data/video2.html" "A lecture that was given on February 8th 2021 as part of the plumed masterclass series that goes through the solutions to the exercises in the lesson" 
click E "data/notebooks/solution.html" "A python notebook file that provides a complete set of solutions to the exercises" 
click F "data/notebooks/answers_notebook.html" "A second python notebook file that contains solutions to the exercises.  In this notebook a different method has been used to generate the figures showing the final free energy surfaces." 
```
