# meanvariancevageesh
EXPT.NO.5	SIMULATION OF MEAN AND VARIANCE USING SCILAB
AIM:
To write a program for mean, variance and cross correlation in SCILAB and verify the output.

EQUIPMENTS Needed

•	Computer with i3 Processor
•	SCI LAB


Algorithm
1.	Define	the	Function:	Specify the	function	you	want	to	simulate.	For	example, f(x)=sin⁡(x)f(x) = \sin(x)f(x)=sin(x) or any other function.
2.	Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.
3.	Evaluate the Function: Compute the function values at each of these sample points.
4.	Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.
5.	Display Results: Output the computed mean variance and Cross Correlation PROCEDURE
•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
•	Execute the code
•	If any Error, correct it in code and execute again
•	Verify the generated results


PROGRAM
clear; clc; clear;
//Mean Value function X=f(x),
z=3*(1-x)^2,//Marginal Probability Density Function X=x*z
endfunction a=0;
b=1;
EX=intg(a,b,f);//Mean value of X function Y=c(y)
z=3*(1-y)^2,//Marginal Probability Density Function Y=y*z
 
endfunction EY=intg(a,b,c);//Mean value of Y disp(EX,"i)Mean of X =") disp(EY," Mean of Y =")


Variance
function X=g(x),


z=3*(1-x)^2,//Marginal Probability Density Function X=x^2*z


endfunction a=0;

b=1;

EX2=intg(a,b,g); function Y=h(y)

z=3*(1-y)^2,//Marginal Probability Density Function Y=y^2*z

endfunction EY2=intg(a,b,h);

vX2=EX2-(EX)^2;//Variance of X vY2=EY2-(EY)^2;//Variance of Y disp(vX2,"ii)Variance of X"); disp(vY2," Variance of Y");

Cross Correlation



x= input("type in the reference sequence="); y= input("type in the second sequence="); n1=max(size(y))-1;

n2=max(size(x))-1;

r=corr(x,y,n1);

plot2d3('gnn',r);

THEOREY CALCULATIONS


<img width="806" height="1280" alt="image" src="https://github.com/user-attachments/assets/578ff104-0b48-489e-8b4b-53bdfc5c5c53" />
<img width="782" height="1280" alt="image" src="https://github.com/user-attachments/assets/dfdc2490-90a4-47d8-8114-faf870b30bfa" />
<img width="754" height="1280" alt="image" src="https://github.com/user-attachments/assets/8b3c75d4-e56a-4be6-a296-5d41ad53ca28" />
<img width="775" height="1280" alt="image" src="https://github.com/user-attachments/assets/5b22571e-3532-45df-9573-3d0fc788ea3e" />
<img width="732" height="1280" alt="image" src="https://github.com/user-attachments/assets/bf4beb2b-cc4f-4c7d-832c-8005dcabe806" />
<img width="765" height="1280" alt="image" src="https://github.com/user-attachments/assets/ce132bac-7f3d-44ec-97ba-8fdb8c1f45a8" />

OUTPUT
<img width="1527" height="885" alt="image" src="https://github.com/user-attachments/assets/8a0174de-6a0b-43da-9ff9-d7d7abd8edf1" />






OUTPUT
i)	Mean of X =	1.75 Mean of Y =	1.75

ii)	Variance of X	 0.0375 Variance of Y	0.0375

Cross Correlation
Type in the reference sequence = [1 2 3 4 5 6 7 8]

Type in the second sequence = [2 1 3 5 6 3 5 9]
 
 









RESULT:
Thus the mean , variance and cross correlation are executed in Scilab and output is verified.
