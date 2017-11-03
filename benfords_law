#Закон Бенфорда
import re 
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import numpy.random as rand
import random
%matplotlib inline 

s=0
l=[]
random.seed(1)
for i in range(10000):
    s = i*np.random.sample()*10
    #print(s, str(s)[0])
    l.append(int(str(s)[0]))
h=[]
for i in range(1,10):
    print("Число",i, "встречается",l.count(i),"раз")
    h.append(l.count(i))
print(h)
plt.bar(range(1,10), h, facecolor='blue', alpha=0.5)
