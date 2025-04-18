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

Name : ROHIT GP

Reg no : 212224220082

```
import matplotlib.pyplot as plt
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.plot(x,y)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH")
plt.show()
```
![Screenshot 2025-04-18 101243](https://github.com/user-attachments/assets/6d55f959-1712-4a3b-addc-71d4288515eb)
```
x1=[1,2,3]
y1=[2,4,1]
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.plot(x1,y1,label="line 1")
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH")
plt.legend()
plt.show()
```
![Screenshot 2025-04-18 101251](https://github.com/user-attachments/assets/4a355b61-0559-4491-9167-59c3effda8ce)
```
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color="red",linewidth=9,linestyle="dashed",marker='o',markerfacecolor='green',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH")
plt.show()
```
![Screenshot 2025-04-18 101256](https://github.com/user-attachments/assets/2d533a76-608e-45ea-b612-80efe9247f2d)
```
years = range(2000, 2012)
apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.9375, 0.9372, 0.939]
oranges = [0.962, 0.941, 0.93, 0.923, 0.918, 0.908, 0.897, 0.894, 0.891, 0.886, 0.9, 0.896]

plt.plot(years, apples)
plt.plot(years, oranges)

plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples', 'Oranges'])
```
![Screenshot 2025-04-18 101302](https://github.com/user-attachments/assets/6a87cac5-7990-4741-ac69-e7c47bbf5b1c)
```
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(yield_apples)
```
![Screenshot 2025-04-18 101329](https://github.com/user-attachments/assets/7a281228-18d8-4761-a2dd-0db7b1dd368e)
```
years = [2010, 2011, 2012, 2013, 2014, 2015]
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(years, yield_apples)
plt.xlabel('YEAR')
plt.ylabel('YIELD(tons per hectare)')
```
![Screenshot 2025-04-18 101335](https://github.com/user-attachments/assets/63d5afc2-f58a-4731-bea5-de9b2c19dfd1)
```
plt.figure(figsize=(10,6))
y=list(range(2000,2012))
plt.plot(y,oranges,marker='o')
plt.title("YIELD OF ORANGES(tons per hectare)")
```
![Screenshot 2025-04-18 101345](https://github.com/user-attachments/assets/dcbbb2c5-baca-41c9-b8f1-763b78068551)
```
plt.plot(y,oranges,marker='x')
plt.plot(y,apples,marker='o')
plt.xlabel("YEAR")
plt.ylabel("YIELD(tons per hectare)")
plt.title("YIELD OF ORANGES AND APPLES(tons per hectare)")
plt.legend(["oranges","apples"])
```
![Screenshot 2025-04-18 101355](https://github.com/user-attachments/assets/4e4a7165-1973-44cf-a534-8f6b6be11f8c)
```
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.scatter(x,y,s=30,color="red")
plt.show()
```
![Screenshot 2025-04-18 101401](https://github.com/user-attachments/assets/3a7aa169-5530-45ed-9de7-0c4fb12659b2)
```
x=[0,1,2,3,4,5]
y=[10,20,4,16,30,40]
plt.scatter(x,y,marker="*",color="blue")
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("SCATTER PLOT")
plt.legend()
plt.show()
```
![Screenshot 2025-04-18 101408](https://github.com/user-attachments/assets/9ec63721-6d83-4036-bec0-56f28fcac1e2)
```
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![Screenshot 2025-04-18 101416](https://github.com/user-attachments/assets/b215f1c8-96a9-489f-9a46-fb83b4b3e5bf)
```
y
```
![Screenshot 2025-04-18 101420](https://github.com/user-attachments/assets/1df03d5c-cbaa-4ecf-a507-f640eb4d56e8)
```
plt.scatter(x,y,c="r")
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("GRAPH IN 2D")
plt.savefig("Test.png")
```
![Screenshot 2025-04-18 101428](https://github.com/user-attachments/assets/6984a147-ddbf-4c26-961d-50b261087c17)
```
y=x*x
y
```
![Screenshot 2025-04-18 101433](https://github.com/user-attachments/assets/a3993491-9b52-44d1-88b4-a348f9a1b18a)
```
plt.plot(x,y,'g*',linestyle="dashed",linewidth=2,markersize=12)
plt.xlabel("X-AXIS")
plt.ylabel("Y-AXIS")
plt.title("2D GRAPH")
```
![Screenshot 2025-04-18 101440](https://github.com/user-attachments/assets/937ca30f-1198-4720-af01-d4f8f3bcc08e)
```
plt.subplot(2, 2, 1)
plt.plot(x, y, 'r--')

plt.subplot(2, 2, 2)
plt.plot(x, y, 'g*--')

plt.subplot(2, 2, 3)
plt.plot(x, y, 'bo')

plt.subplot(2, 2, 4)
plt.plot(x, y, 'go')
```
![Screenshot 2025-04-18 101448](https://github.com/user-attachments/assets/bdec62a6-fa42-4a39-bf38-919bee51eff9)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x, y)
plt.show()
```
![Screenshot 2025-04-18 101455](https://github.com/user-attachments/assets/d7a42928-b52f-4ca7-83cf-6f1fb4de195b)
```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2=[5, 7, 9, 11, 13]
y3=[2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```
![Screenshot 2025-04-18 101503](https://github.com/user-attachments/assets/b442a435-4fd2-4e4a-b138-2a2da138367a)
```
plt.stackplot(x, y1, y2, y3, labels=['Line 1', 'Line 2', 'Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```
![Screenshot 2025-04-18 101511](https://github.com/user-attachments/assets/1805d337-e5ee-4010-9671-8db337d4522f)
```
from scipy.interpolate import make_interp_spline
x= np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
y = np.array([2, 4, 5, 7, 8, 8, 9, 10, 11, 12])
spl = make_interp_spline(x, y)
x_smooth = np.linspace(x.min(), x.max(), 100)
y_smooth = spl(x_smooth)
plt.plot(x, y, 'o', label='data')
plt.plot(x_smooth, y_smooth, '-', label='spline')
plt.legend()
plt.title("SPLINE CHART")
plt.show()
```
![Screenshot 2025-04-18 101517](https://github.com/user-attachments/assets/9b57dce3-1826-42ea-8d29-560d9e454516)
```
val=[5,4,8,6,3]
names=["A","B","C","D","E"]
plt.bar(names,val,color="red")
plt.title("BAR GRAPH")
plt.show()
```
![Screenshot 2025-04-18 101555](https://github.com/user-attachments/assets/87aa27d7-f1dd-4e90-ac55-aeb5eed6f519)
```
plt.barh(names,val,color="pink")
plt.title("BAR GRAPH(horizontal)")
plt.show()
```
![Screenshot 2025-04-18 101603](https://github.com/user-attachments/assets/72274299-ca74-48a5-8fd9-6d1ff175364c)
```
height=[10,24,36,37,45]
names=['one','two','three','four','five']
c1=['red','blue']
c2=['b','g']
plt.bar(names,height,color=c1,width=0.8)
plt.xlabel("names")
plt.ylabel("height")
plt.title("BAR CHART")
plt.show()
```
![Screenshot 2025-04-18 101610](https://github.com/user-attachments/assets/137b9a82-b2e3-4310-ac99-b941b826cef2)
```
x=[2,8,10]
y=[11,16,9] 
x2=[3,9,11] 
y2=[6,15,7]
plt.bar(x, y,color='yellowgreen') 
plt.bar(x2, y2, color = 'purple')
plt.title("Bar graph")
plt.ylabel('Y axis')
plt.xlabel('x axis')
plt.show()
```
![Screenshot 2025-04-18 101617](https://github.com/user-attachments/assets/b07cb535-b99e-4667-a165-4983eef71f5a)
```
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0, 100)
bins=10
plt.hist(ages, bins, range, color='cyan', histtype='bar', rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('Histogram')
plt.show()
```
![Screenshot 2025-04-18 101624](https://github.com/user-attachments/assets/0015514d-573c-4896-86e1-bcd17e4283bc)
```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins=10, color='blue', alpha=0.5)
plt.show()
```
![Screenshot 2025-04-18 101631](https://github.com/user-attachments/assets/c08cde75-2328-4c81-a0c1-9981f7656d06)
```
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![Screenshot 2025-04-18 101637](https://github.com/user-attachments/assets/98c175dd-fdcc-4059-bf4b-493e6156819e)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_title("BOX PLOT")
ax.set_ylabel("Y-AXIS")
ax.set_xlabel("X-AXIS")
```
![Screenshot 2025-04-18 101643](https://github.com/user-attachments/assets/0abac06b-f893-4e20-8fc5-e566b698f048)
```
activities = ['eat', 'sleep', 'work', 'play']
slices=[3, 7, 8, 6]
colors = ['r', 'y', 'g', 'b']
plt.pie(slices,labels=activities,colors=colors,startangle=90, 
        shadow=True,explode=(0,0,0.1,0), radius=1.2, autopct='%1.1f%%')
plt.legend ()
plt.show()
```
![Screenshot 2025-04-18 101649](https://github.com/user-attachments/assets/7dde3fea-12e6-4249-9730-65ab84a0f516)
```
labels=['Python','C++','Ruby','Java']
sizes=[215, 130, 245, 210] 
colors=['gold', 'yellowgreen', 'lightcoral', 'lightskyblue'] 
explode=(0,0.4,0,0.5)
plt.pie(sizes, explode=explode, labels=labels, colors=colors, autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![Screenshot 2025-04-18 101655](https://github.com/user-attachments/assets/c6f1fab0-e920-4cfc-a258-c90b75986997)

# Result:
Successfully performed Data Visualization using matplot python library for the given datas.
