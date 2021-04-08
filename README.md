# matplotlibcodes
#Write a Python program to draw a line with suitable label in the x axis, y axis and a title.
import matplotlib.pyplot as plt
x=range(1,50)
y=[value*3 for value in x]
print("value of x:",*range (1,50))
print("value of y:",y)
plt.plot(x,y)# to plot the markers on axes
plt.xlabel("x-axes")# to mark the x axes
plt.ylabel("y-axes")#to mark the y-axes
plt.title("draw the line")# to set the title
plt.show()# to display the graph


#Write a Python program to draw a line using given axis values with suitable label in the x axis , y axis and a title.
import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)# to plot the markers on axes
plt.xlabel("x-axes")# to mark the x axes
plt.ylabel("y-axes")#to mark the y-axes
plt.title("sample graph")# to set the title
plt.show()# to display the graph
