ex3*	ex3*	ex3*	ex3*	ex3*	ex3*	ex3*	ex3*	ex3*	ex3*
*******************************************************************************
*******************************************************************************
			

***************************************
Hadassah college:
Computer since
Object oriented programing Simester A Year 2011(2010)


*****************************************************

Students Info:
**************
ex3-andreysh_iliaga

	#	id:	321470882	Andrey Shamis	-	אנדריי שמיס
	#	id:	309480051	Ilia Gaysinsky	-	איליה גייסינסקי
	
	#	All rights reserved  ©



General explanation of the exercise:
************************************

A Program that realized class that reprisente Polynom.
- can creat polynom trough iterpulation (lagrange).
- The program Demonsytrait polynom graph using Glut.
- the class contain OVERLOADING of OPERATOR: 

[##] 	 = , == , =! , + , =+ , * , =* , << , ()	[##]

- we can use thuse operator on polynoms.



List of files that been created:									
********************************


    file name:		|                                Explonation:
*******************************************************************************
Poly.cpp			|This class represent polynom. The class contain allot of 
					|constractors wich let as biuld the polinom through many
					|differente methods. the main method is Interpulation 
					|Lagrange type.
					|Also the class overloading the next operators:
					|[##] 	 = , == , =! , + , =+ , * , =* , << , ()	[##]
					|wich work with polynoms.
					|In fact, thanks to those operaotrs let as build other 
					|functions in eaziast way. For example: fuc' in Lagrange 
					|we used those operators.
-------------------------------------------------------------------------------
Poly.h				| header file
*******************************************************************************


List of files that been upaded:									
*******************************


    file name:		|                                Explonation:
*******************************************************************************
PlotPoly.cpp		|We add functions that use class poly. Thay let user to 
					|create polynom through interpulation ant prisent a graph
					|of that polynom.
*******************************************************************************

User guide:
***********

#	To run this program:
	* 1  - Compile
	* 2  - Run

#	All othere nessesery instractio builed-in in program interface.


Main data structures and their functionality:
*********************************************

Vector of monoms. Reprisent Polynom.
- This vector don't save monoms with scalar that equal to zero.
  this feature can save alot of mamory.

Notable algorithms:												
*******************

- Lagrange algorithem: Realization of Lagrange formula by using overload
  operators that can sum and multiple polynoms, let the code be: short, easy to
  anderstanding and effective.
- Recursive function that ignor usless spaces that user put between the 
  interpulations, and warning about wromg input (if not double values hav been
  puted).
  
  
Interesting points:															
*******************

- Update globalse function: We took this mission to another level!
  The algorithem prisent the graph all ways in 500 points of x vairebels,
  even if the points are very close to each other. we calculate an proportion
  variable and that feature print the graph always in focus (even if the y points
  of polynom go to infinity)
  Another interesting feature: Asix of the graph moves acording to the min and 
  max points of y and x points of polynom.
  Also the the points of graph that user fill, stay in frame of glat window 
  wich alow to allways see that points (x,y).
  
- The interface of the program:
  We builed a very friendly interface to users. the user get all nessesry 
  instructions - how to fill the interpolations, if the user make an a mistake,
  the program tell him about it and let him fill data again.
  the user can fill the points of interpulation with more then one space 
  between each point. 
  
- We reprisent "Zero polynom" as empty vector (vector size = 0) and becouse of
  that default constractor and zero polynom constractor it is the same 
  constractor.
  
  
Known bugs:
***********

		NO BAGS!!! The program work very well!!!
-------------------------------------------------------------------------------
