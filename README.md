**Burger**
This is a simple burger logger app created with MySQL, Node, Express, Handlebars.

#### Functionality
  Using an home-grown ORM, the app has 3 basic CRUD functions..
   1. READ all entries from the MySQL database and display them to the DOM using HAndlebars.

    2. UPDATE a selected burger by clicking "Devour It", which... * hits an /burger/eat/:id route in Express to change its "devoured" status in the MySQL database * re-routes the webpage back to the index, where the burger is now in the devoured column (via Handlebars).

    3. CREATE a new burger using the "Place Order" form, which... * hits a /burger/create route in Express to insert a new burger into the MySQL database * re-routes the webpage back to the index, where the burger is now ready to be eaten column (via Handlebars).
 
Here is the link deployed in Heroku [Heroku] ( https://pacific-bastion-19820.herokuapp.com/)
  

