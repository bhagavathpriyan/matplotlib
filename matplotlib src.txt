import matplotlib.pyplot as plt


year = []
profit = []

for i in range(0,5):
    year_input = int(input("Enter the year: "))
    year.append(year_input)
    profit_input = int(input(f'Enter the Profit of {year_input}: '))
    profit.append(profit_input)

plt.plot(year,profit)
plt.xlabel('Year')
plt.ylabel('Profit')
plt.title('Anual Profit in Years')
plt.show()