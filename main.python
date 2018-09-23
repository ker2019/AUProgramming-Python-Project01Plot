#!/usr/local/bin/python3.6

#to calculate sin()
import math
#to create range 
import numpy
#to build and show plot
import matplotlib.pyplot as mpp

#do if only this module is main 
if __name__=='__main__':
	#save range {0;0.1;0.2;...;200} in arguments
	arguments = numpy.r_[0:200:0.1]
	#build plot with x in arguments, y = sin(x)*sin*(x/20)
	mpp.plot(
		arguments,
		#array {sin(0)sin(0);sin(0.1)sin(0.2/20);...;sin(200)sin(200/20)}
		[math.sin(a) * math.sin(a/20.0) for a in arguments]
	)
	#show plot in graphical window
	mpp.show()

