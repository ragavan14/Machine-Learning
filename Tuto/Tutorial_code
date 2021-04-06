import numpy as nmp
import matplotlib.pyplot as plot
x= nmp.array([1,2,3])
y=nmp.array([1.2,1.9,3.2])

a=x.sum()
b=y.sum()
c=(x*x).sum()
d=(y*y).sum()
e=len(x)

w0=(c*b-a*d)/(c*e-a*a)
w1=(b-(e*w0))/a
slope=w1
intercept=w0

values=[slope*i+ intercept for i in x]
plot.title("Maximum Likelihood Linear Function")
plot.xlabel("Data points")
plot.ylabel("Fitted points")
plot.scatter(x,y)
plot.plot(x,values,'r')
plot.show() 
