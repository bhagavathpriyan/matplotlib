import matplotlib.pyplot as plt


x = [3, 5, 8, 10]
y = [5, 8, 12, 14]

fig = plt.figure()
rect = fig.patch
rect.set_facecolor('green')

graph1 = fig.gca()
graph1.set_facecolor('black')

graph1.plot(x,y,'red',linewidth=4)


plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('sample graph')
plt.show()