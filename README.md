# IA-Proyecto-3
Solución a 4 problemas como evaluación final de la materia Inteligencia Artificial de la maestría en Ciencias Matemáticas de la UNAM

25 January 2021

**Final Evaluation**

The project test consists of 4 problems/questions, for which a brief written report with pictures and brief explanation of the results should be provided. The student must discuss the report on 04 February 2021 on a ZOOM channel. The student will explain his/her results and will answer a question about the course slides. 
Remark: Provide a brief reasoning in the report why you choose certain algorithm. Please provide in your report full name and matriculate number. 
The oral examination will be a discussion of the project, tools and a general question. 
The codes you use for the project should be upload in the platform before 1:00 pm 04 February 2021.

**Problem 1**. Using the data set called „problem1.csv (x_training, y_training)“ :
a)	Find the polynomial that fits the best the training data
b)	Using the AIC criteria, find the best polynomial that can fit the data.
c)	Cross validate the polynomial with the data set called “problem1.csv (x_test, y_test)”

**Problem 2**. Having the following logic table
 <table>
<tr><td>

|$x_1$|$x_2$|$x_1\&x_2$|
|--|--|--|
|0|0|1|    
|1|0|1|
|0|1|1|
|1|1|0|    
    
</td><td>

|$x_1$|$x_2$|$x_1\$x_2$| 
|--|--|--|
|0|0|0|    
|1|0|0|
|0|1|0|
|1|1|1|

</td></tr> </table>
Using Keras, construct an & and $ operator gate with a simple perceptron. If A=[1.001 0 0.001 1], B=[0 1 0 1] and C=[0  1 1 0]. Compute the operation (A&B)$C with the perceptron.
**Problem 3**. From a clinical trial, we have 12 patients with HIV infection. After treatment, the disease progressed in 6 patients (1) and in 6 patients the infection did not progress (0). Four measurements are taken in the 12 patients (Age, sugar levels, T cell levels and Cholesterol). Which measurement can be used as a marker to describe progression of the disease? Which will be the criteria to predict the progression? The data can be found in „problem3.csv (x_age, x_sugar, x_Tcell, x_cholesterol, outcome). Arrange the data and briefly explain your results. The variable “y” (target) is a vector of 0 and 1 to represent the progression.
**Problem 4**. Using a multilayer perceptron with Keras produce a cone with the dimension of your election. Remark: In other words, use the equation of a cone, then generate artificial data to generate X, Y and Z. Then you use data of X, Y Z to train a Neural Network, and then form the shape of a cone but produce by the Neural Network. In your report you should mention the equation of the cone you selected, and the figures generate by the equation and by your neural network.
