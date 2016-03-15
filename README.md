# pyView
This is to give View Function to pandas DataFrame using the pyQT framework
This is tested for python 3+ version.

To use this you need to have pyQT,pandas installed. 
A small example will be

````python
from helper import View
import pandas as pd
import numpy as np

df = pd.DataFrame(np.arrange(5,5)
View(df)

````
That's all. 

###Warning : This is process is resource intensive as it creates lot of pyQt objects. Still the sort by column methods are not implemented. It will take sometime to implement them.



