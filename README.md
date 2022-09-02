# Restaurant Information App
_____________________________
## Description:
This app takes a json-server with data from the URLs http://localhost:3003/menu and http://localhost:3003/restaurants
and allows a user to view a list of all the restaurants in the server, where you can either view the menu of each restaurant or delete the restaurant,
which also deletes all of the menu items with a matching restaurant ID.
_____________________________
## Endpoints:
1. Get all restaurants (GET)
2. Get all menu items for a particular restaurant (GET)
3. Add restaurant to list (POST)
4. Delete restaurant from list (DELETE)
5. Delete menu item from list (DELETE)

## URLs
1. http://localhost:3001 : Home page with list of restaurants
2. http://localhost:3001/restaurant/{id} : Page with list of menu items for particular restaurant
3. http://localhost:3001/add-restaurant : Page that allows the user to add restaurants to the json-server