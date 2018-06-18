## Define a ticket object model and implement ticket price calculation

For a specific buy on our platform we need to calculate the total price of that order. Buyer will always make 1 order, but this order can contain more tickets and products (for example T-shirt or book):

* Prices are always in Euro.
* An order can have 1 or more tickets.
* Each ticket has a price and can have a discount code.
* Total price of the ticket consists of ticket's price and it's product prices.
* A ticket can have 0 or more products that each have own price.
* A discount code can offer a specific deduction in percent on the ticket's total price.
Define a data model and implement the price calculation logic. Make sure it is unit tested.

Timeboxed: 30 minutes
