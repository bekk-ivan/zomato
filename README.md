# zomato
Recomendation app

Goal:
- Build a function that takes in restaurant review data and recommends similar restaurants
- Represent the function in a user-friendly format, such as a Tkinter GUI

Data Dictionary:
url = the url of the restaurant in the zomato website
address = the address of the restaurant in Bengalore
name = the name of the restaurant
online_order = whether online ordering is available for this restaurant or not
book_table = option to book a table available or not
rate = the overall rating of the restaurant out of 5
votes = total number of ratings for the restaurant as of the above mentioned date
phone = the phone number of the restaurant
location = the area in which the restaurant is located
rest_type = restaurant type
dish_liked = dishes people liked at the restaurant
cuisines = food styles, separated by comma
approx_cost(for two people) = the approximate cost for a meal for two people
reviews_list = list of tuples containing reviews for the restaurant, each tuple consists of two values,
rating and review by the customer
menu_item = a list of menus available in the restaurant
listed_in(type) = type of meal
listed_in(city) = the area in which the restaurant is listed
