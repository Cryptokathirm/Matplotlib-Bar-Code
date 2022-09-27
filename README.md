# Matplotlib-Bar-Code
#python Matplotlib library
#pip install matplotlib
#as alias key
import matplotlib.pyplot as plt
#pip install numpy
import numpy as np


#x value
x = np.array(['Bike', 'Car', 'Bus', 'Auto'])
#y value
y = np.array([40, 18 , 80, 55])

#Bar Code Title use title
plt.title("Usage Vehicle Of Chennai Graph",loc='center')

#width, Blue Color
plt.bar(x,y, color='b',width=0.6)

#show the BarCode
plt.show()
