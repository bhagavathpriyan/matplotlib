import matplotlib.pyplot as plt


x = []
y = []

readFile = open("coord.txt", "r")
data = readFile.read().split("\n")
for i in data:
    val = i.split(",")
    x.append(int(val[0]))
    y.append(int(val[1]))

plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('sample graph')
plt.show()