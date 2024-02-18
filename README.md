# pie-chart
#importing matplotlib module
import matplotlib.pyplot as plt
#Data for the pie charts
labels=['Geeks 1','Geeks 2','Geeks 3']
sizes=[35,35,30]
#plotting the pie charts
plt.pie(sizes,labels=labels,autopct='%1.1f%%',startangle=90)
plt.title('pie chart example')
plt.show()
