# CIS129_lab03_coffeeShop.py
#tile of receipt
#enter input of number of coffees and muffins
#two variables
#coffee variable and muffin variable
#sum of variables
#tax of sum with equation

print('*************************************** \nMy Coffee and Muffin Shop Receipt\n***************************************')

value1 = input('How many coffee(s) bought?:\n ')
value2 = input('How many muffin(s) bought?:\n ')

x = int(value1) * 5
y = int(value2) * 4

total = x + y
totalprice = total
formatted_price = "{:.2f}".format(totalprice)

print('*************************************** \n\n***************************************\n')

price = x
formatted_price = "{:.2f}".format(price)

if int(value1) == 1 :
    print(value1,"Coffee bought at $5.00 each: ${}".format(formatted_price))
else:
    print(value1,"Coffees bought at $5.00 each: ${}".format(formatted_price))

price2 = y
formatted_price = "{:.2f}".format(price2)

if int(value2) == 1 :
    print(value2,"Muffin bought at $4.00 each: ${}".format(formatted_price))
else:
    print(value2,"Muffins bought at $4.00 each: ${}".format(formatted_price))

total = x + y
totalprice = total
formatted_price = "{:.2f}".format(totalprice)
print("Total: ${}".format(formatted_price))

print('*************************************** \n\n***************************************\n')

z = total * 0.060
print('+6.00% tax')
taxesprice = z
formatted_price = "{:.2f}".format(taxesprice)
print('+ ${} added tax'.format(formatted_price))

print('---------')

taxprice = total + z
formatted_price ="{:.2f}".format(taxprice)
print("Total: ${}".format(formatted_price))
print('Enjoy Your coffee! ^-^')

print('***************************************')
