import pandas as pd
import math

print("Enter elements in array :")

x = list(map(int,input().split()))

array=pd.Series(x)

print("Mean : %.lf" % array.mean())

print("Median : %.lf" % array.median())

print("Mode : "  ,array.mode())

print("Standard Deviation : %.lf" % array.std())

n = len(array)

lower= array.mean()-1.96*array.std()/math.sqrt(n)
higher= array.mean()+1.96*array.std()/math.sqrt(n)
print("Lower Limit :",lower)
print("higher Limit :",higher)
