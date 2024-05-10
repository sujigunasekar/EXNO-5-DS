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
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![328743300-69c6383e-99f5-43c5-aa51-86dba3704924](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/5a447d5b-a39b-42ac-a043-e68a09d4165d)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```
![328743184-fb64ac21-a1a7-484e-a4b6-425311ed49ae](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/a1fa75c9-f01c-4a3f-9698-1274a80e5b7e)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![328743837-30ebd91b-ec0c-47dc-928d-050542017f9c](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/bf6e4c20-c5d7-40a0-b06f-8243026ceef2)
```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![328743896-843c5efe-aeba-4643-8089-f58c99ea6e8c](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/d4aff217-b522-48e5-889d-e6dd76c86821)
```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);
```
![328743957-0c79a361-26ab-4978-8531-d0a08fab0ca5](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/403dbb94-141e-4050-b4b4-65439add086c)
```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```
![328744004-589e1264-9426-4e52-a9ae-1c504f4a0f88](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/f276fd99-7c8b-4586-8eb8-482022b9a26e)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![328744071-118407ac-0f1d-4d01-bd3a-0be14280edb6](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/4cb63538-bcbb-43d4-9c0a-d2515e19d87e)
```
y
```
![328744115-e4f603e5-100c-49a0-9ca9-1ff6d7d5d3eb](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/a0519632-e095-4da8-a648-ad121dca25ce)
```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![328745107-5b078a15-dc9e-4456-9b71-e3cc29803981](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/0b0a5018-3df5-4344-8acf-a39922e406eb)
```
y=x*x
y
```
![328745295-b1d93fa1-94c3-4b11-8dcd-e0a16b9e206c](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/19c9801a-5338-4373-9322-11e83254603a)
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![328745350-a3a8e245-25dd-4162-8c38-892b3877c17c](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/2880fd9d-1b9a-4ab6-8062-37da0a17141e)
```
np.pi
```
![328744192-3b8f0d68-94f6-4907-889b-65b2f19a06d1](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/e2e22917-f36b-4b24-8900-54f26db9f841)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![328744341-882ff1ec-06a8-41b8-a973-6a58db0c359f](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/106d8195-b1fd-415e-bb70-cb8c56c23b53)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
```
![328744379-cd93631d-e1ec-4f0d-b393-279953b2bd67](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/e73a4952-3105-4d24-9400-a0c40f2dda03)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')

plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```
![328744410-c2687412-0627-494f-940e-6c27ec58c3d2](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/74056a05-8e05-499d-b9ba-1cf13ce2693e)
```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![328744444-f84d9b93-bb7c-4afd-8472-d796b0ce0498](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/f9a4c649-c59a-4147-a84b-00bbe38725bc)
```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![328744486-596ac2d7-ceed-4d03-9474-418e6e104367](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/c5ece0c3-5f38-449a-b6cc-96b5ab4b8d30)
```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
![328744518-aeda23bd-1a9e-4022-97b3-b4eb26a020b9](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/cdd9856a-8eb2-4ecf-931c-d4cb68921894)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![328744551-1e18e3be-98d4-42af-83a0-c91400229db2](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/d2fd75a9-57a3-497e-bdf4-0a980028a2cb)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![328744580-dc5ce2f7-5b16-45c4-b605-a8284cd4793e](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/9860580e-cdcf-4911-8d2f-c82a628b8d66)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![328744616-66e37ab8-a865-4e01-9dbe-5b7c19f0d03f](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/79c809a8-9954-4130-b275-3dc6a47011fe)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![328744649-995b0d9f-2622-483a-98fa-ca48ce6d2d81](https://github.com/sujigunasekar/EXNO-5-DS/assets/119559822/19777ed9-2247-47dd-abde-b7495dd0c8dd)

# Result:
Thus, The implementation of data visualization using matplotlib has been successfully verified.
