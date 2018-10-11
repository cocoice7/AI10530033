

```python
import numpy as np
import matplotlib.pyplot as plt

class ass:
    def __init__(self,x):
        self.x = np.arange(0, 6, 0.1)
    def sin(self):
        
        y = np.sin(self.x)
        plt.plot(self.x,y)
        plt.show()
    def cos(self):
        y = np.cos(self.x)
        plt.plot(self.x,y)
        plt.show()
```


```python
m = ass("")
m.sin()
m.cos()
```


![png](output_1_0.png)



![png](output_1_1.png)



```python

```

    Hello David!
    
