# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
NAME: Rishab P Doshi

REG NO:212224240134
```
 import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt
 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student,marker='o', linestyle='--')
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
 student=['A','B','C','D']
 attendence=[90,85,73,88]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()
```


<img width="501" height="726" alt="image" src="https://github.com/user-attachments/assets/011afe4e-a5f8-4f16-a4a8-7e294f242863" />


```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='blue',marker='*',s=30)
 plt.show()
 x=np.arange(0,15)
 y=np.arange(0,15)
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```


<img width="474" height="729" alt="image" src="https://github.com/user-attachments/assets/097f82b8-973e-4631-9ca2-5134ccf19f4b" />


```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.09,0.09,0.09,0.09),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```


<img width="385" height="689" alt="image" src="https://github.com/user-attachments/assets/410edea0-b64a-41b0-890e-5cb702d3f33e" />


```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 plt.fill_between(x, y1, color='lime')
 plt.fill_between(x, y2, color='seagreen')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```


<img width="465" height="347" alt="image" src="https://github.com/user-attachments/assets/513f22c2-ad02-49e8-8eef-5a1f214ca703" />


```
 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['orange', 'green'] 
 c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart!')
 plt.show()
```


<img width="464" height="368" alt="image" src="https://github.com/user-attachments/assets/a70081a9-a61e-47bf-b0bc-ce2679de8092" />


```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```


<img width="443" height="340" alt="image" src="https://github.com/user-attachments/assets/99cce6e2-09f6-4098-8392-a7c5c16d1ff6" />


```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 print(data)
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```


<img width="493" height="647" alt="image" src="https://github.com/user-attachments/assets/0a9f437d-b8b0-446c-8c9b-dea8fd2bd459" />






# Result:
 All visualization of matplotlib is visualised successfully.
