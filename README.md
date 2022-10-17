# Maven Pizza Challenge
In this project I played the role of a BI Consultant hired by **Plato's Pizza**, a Greek-inspired pizza place in New Jersey. I've been hired  to help the restaurant use data to improve operations.

## [Notebook Viewer](https://nbviewer.org/github/TelRich/Plato-s_Pizza_Analysis/blob/master/pizza_sales.ipynb?flush_cache=True)

<center><img src="/pictures/pizza.jpg"/></center>

### Some questions that we'd like to answer:
* What days and times do we tend to be busiest?
* How many pizzas are we making during peak periods?
* What are our best and worst selling pizzas?
* What's our average order value?

## About the dataset
* This dataset contains 4 tables in CSV format
* The Orders table contains the date & time that all 5,238 table orders were placed
* The Order Details table contains the different pizzas served with each order in the Orders table, and their quantities
* The Pizzas table contains the size and price for each distinct pizza in the Order Details table, as well as its broader pizza type
* The Pizza Types table contains details on the pizza types in the Pizzas table, including their name as it appears on the menu, the category it falls under, and its list of ingredients

<center><img src="/pictures/weekday_order.png"/></center>

## Answers
* The most **busiest day** is _**Friday**_ with order count of **8,106**. 
* More than **1000 pizza are made during peak peiods**. For _January_ record, _1,410 pizza_ was made in the period of _12 pm - 3pm_ while in _February_, _1,275 pizza_ was ordered during the same period _(early afternoon)_
* The **3 best selling pizzas** include, _**The Classic Deluxe**_, _**The Barbecue Chicken Pizza**_, and _**The Hawaiian Pizza**_.
* The **3 worst selling pizza** include, _**The Soppressatan Pizza**_, _**The Spinach Pesto Pizza**_ and _**The Spinach Supreme Pizza**_.
* The average order value is approximately **$17**.

<center><img src="/pictures/cat_size_sale.png"/></center>

## Summary
* Earliest open hour is 09:52 am and latest closing hour is 23:05 pm
* The average quantity of _pizza ordered is very high around 10 a.m_ and reduces as the hour goes by.
* Average sales is high on _Tuesdays_ and _Thursdays_.
* The _highest sale was made in July with average of $4,301_, while the _least sale was made in October with average of $3,797_.
* Small size pizza from the veggie category is the most purchase pizza.

## Recommendation
* Replace the worst selling pizza with new pizza type.
* The shop be open early for more sales in the morning.
* Do a promo or sales discount with the best selling pizza to attract more customers.
