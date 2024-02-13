# coffee_machine_2:

# This is the same as the previous coffee_machine, but this time with Object Oriented Programming.  

# starts out pulling in the Menu, CoffeeMaker, and MoneyMachine classes
# then assigns variables to these classes.
# Starts out with the coffee machine turned on,
# While it is on, sets an 'options' variable that pulls the information from the 'menu' variable, specifically the get_items function.
# it then presents these 'options' for the user to select their drink
# If the user selects 'off' (choice variable)it turns the coffee machine off and ends the game
# if user selects 'report', (choice variable) it takes the CoffeeMaker method of report (prints remaining resources), and the MoneyMachine method of report (prints current cash in the machine).
# if user selects a drink (choice variable fed into drink variable), it runs the Menu class method of find_drink, then checks to see if there are enough resources (CoffeeMaker method is_resource_sufficient), and payment (MoneyMachine method make_payment)
# Finally, it makes the drink (CoffeeMaker method of make_coffee)
