# zomato
Recomendation app

Goal:
- Build a function that takes in restaurant review data and recommends similar restaurants
- Represent the function in a user-friendly format, such as a Tkinter GUI

Data taken from the website https://www.zomato.com/india

Example:
![Hangman](https://user-images.githubusercontent.com/68350145/224948448-6be47aa0-542f-444e-8406-fe12f2c915db.jpg)

Data Dictionary <br >
url = the url of the restaurant in the zomato website <br >
address = the address of the restaurant in Bengalore <br >
name = the name of the restaurant <br >
online_order = whether online ordering is available for this restaurant or not <br >
book_table = option to book a table available or not <br >
rate = the overall rating of the restaurant out of 5 <br >
votes = total number of ratings for the restaurant as of the above mentioned date <br >
phone = the phone number of the restaurant <br >
location = the area in which the restaurant is located <br >
rest_type = restaurant type <br >
dish_liked = dishes people liked at the restaurant <br >
cuisines = food styles, separated by comma <br >
approx_cost(for two people) = the approximate cost for a meal for two people <br >
reviews_list = list of tuples containing reviews for the restaurant, each tuple consists of two values,<br >
rating and review by the customer <br >
menu_item = a list of menus available in the restaurant <br >
listed_in(type) = type of meal <br >
listed_in(city) = the area in which the restaurant is listed<br >
