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
 ```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img width="596" height="426" alt="image" src="https://github.com/user-attachments/assets/c2940ba2-3ad1-40a5-9eb4-8b8c2bb9e0c3" />
<img width="568" height="442" alt="image" src="https://github.com/user-attachments/assets/79f7a763-af05-44c1-8034-b52149657de6" />
<img width="568" height="424" alt="image" src="https://github.com/user-attachments/assets/36023abd-5cee-4191-9095-63c9c143d793" />
<img width="577" height="452" alt="image" src="https://github.com/user-attachments/assets/2c6fa4c7-1938-4781-9cfc-2827358403d1" />
<img width="458" height="420" alt="image" src="https://github.com/user-attachments/assets/14b39134-27a2-4b28-b44e-44219c456b92" />
<img width="449" height="402" alt="image" src="https://github.com/user-attachments/assets/61cbbff4-fbf0-4159-a022-7899ca6b57f0" />
<img width="573" height="418" alt="image" src="https://github.com/user-attachments/assets/f08aa44f-50eb-4037-bd86-e5ed80809f17" />
<img width="579" height="469" alt="image" src="https://github.com/user-attachments/assets/f60f5fb9-d62b-4a10-8331-0faf8af1d149" />
<img width="486" height="373" alt="image" src="https://github.com/user-attachments/assets/7813f15b-d974-43d7-9054-616b953f1c18" />
<img width="579" height="462" alt="image" src="https://github.com/user-attachments/assets/6540406f-54a0-441f-8005-4727c6417ff4" />


# Result:
  Thus, all the data visualization techniques of matplotlib has been implemented.
