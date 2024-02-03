import matplotlib.pyplot as plt
import numpy as np
data=np.array([25,15,10,25,5,20])
datacolors=['k','orange','c','k','g','red']
datalabels=['biscuits','candies','pasteries','cookies','chocolates','softdrinks']
popup=[0,0,0.3,0,0,0]
plt.pie(data,colors=datacolors,labels=datalabels,explode=popup,shadow='true')
plt.title('Canteen')
plt.legend(loc='best',title='Menu')
plt.show()
