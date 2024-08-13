{% load static %}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>King Pizza</title>
    <link rel="stylesheet" href="{% static 'menu/styles.css' %}">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h1>Welcome to King Pizza</h1>
        <p>Your favorite pizza place!</p>
    </section>
    
    <section id="menu">
        <h2>Our Menu</h2>

        <h3>On a Home Made Base</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Description</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Margherita</td>
                <td>Made with Homemade Sauce & 100% Mozzarella Cheese</td>
                <td>€9.00 / €11.00 / €15.00</td>
                <td><button onclick="addToCart('Margherita', 9)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Hot & Spicy</td>
                <td>Beef, Pepperoni & Chilli Peppers</td>
                <td>€10.00 / €12.00 / €16.00</td>
                <td><button onclick="addToCart('Hot & Spicy', 10)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Chicken BBQ</td>
                <td>BBQ Sauce, Chicken, Peppers & Onion</td>
                <td>€10.00 / €12.00 / €16.00</td>
                <td><button onclick="addToCart('Chicken BBQ', 10)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Cajun Delight</td>
                <td>Cajun Chicken, Onions, Peppers & Olives</td>
                <td>€11.00 / €13.00 / €17.00</td>
                <td><button onclick="addToCart('Cajun Delight', 11)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Vegetarian</td>
                <td>Mushrooms, Onions, Peppers, Sweetcorn & Pineapple</td>
                <td>€10.00 / €12.00 / €16.00</td>
                <td><button onclick="addToCart('Vegetarian', 10)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Pepperoni Express</td>
                <td>Double Pepperoni & Extra Cheese</td>
                <td>€11.00 / €13.00 / €17.00</td>
                <td><button onclick="addToCart('Pepperoni Express', 11)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Big Bite</td>
                <td>Ham, Pepperoni, Chicken, Mushrooms, Peppers & Sweetcorn</td>
                <td>€11.00 / €13.00 / €17.00</td>
                <td><button onclick="addToCart('Big Bite', 11)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>King Special</td>
                <td>Chicken, Mushrooms, Ham, Pepperoni, Onions & Sweetcorn</td>
                <td>€11.00 / €13.00 / €17.00</td>
                <td><button onclick="addToCart('King Special', 11)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Meat Mighty</td>
                <td>Ham, Pepperoni & Chicken</td>
                <td>€11.00 / €13.00 / €17.00</td>
                <td><button onclick="addToCart('Meat Mighty', 11)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Hawaiian</td>
                <td>Ham & Pineapple</td>
                <td>€10.00 / €12.00 / €16.00</td>
                <td><button onclick="addToCart('Hawaiian', 10)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Newmarket Special</td>
                <td>Chicken, Mushrooms, Ham, Pepperoni, Onions & Jalapeno</td>
                <td>€11.00 / €13.00 / €17.00</td>
                <td><button onclick="addToCart('Newmarket Special', 11)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Doner Kebabelar</td>
                <td>Onions & Doner Meat</td>
                <td>€11.00 / €13.00 / €17.00</td>
                <td><button onclick="addToCart('Doner Kebabelar', 11)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Make Your Own Pizza</td>
                <td>Beef, Chicken, Ham, Pepperoni, Mushroom, Peppers, Chilli Peppers, BBQ Sauce, Onion, Cajun, Olives, Sweetcorn, Pineapple & Extra Cheese</td>
                <td>€11.00 / €13.00 / €17.00</td>
                <td><button onclick="addToCart('Make Your Own Pizza', 11)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Garlic Bread Plain</td>
                <td></td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Garlic Bread Plain', 6)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Garlic Bread with Cheese</td>
                <td></td>
                <td>€8.00 / €10.00</td>
                <td><button onclick="addToCart('Garlic Bread with Cheese', 8)">Add to Cart</button></td>
            </tr>
        </table>

        <h3>Kebabs</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Doner Kebab</td>
                <td>€8.00</td>
                <td><button onclick="addToCart('Doner Kebab', 8)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Chicken Kebab</td>
                <td>€8.50</td>
                <td><button onclick="addToCart('Chicken Kebab', 8.5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Mix Kebab</td>
                <td>€9.00</td>
                <td><button onclick="addToCart('Mix Kebab', 9)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Chicken Fillet Kebab</td>
                <td>€8.50</td>
                <td><button onclick="addToCart('Chicken Fillet Kebab', 8.5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Doner Meat & Chips</td>
                <td>€8.00</td>
                <td><button onclick="addToCart('Doner Meat & Chips', 8)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Chicken Meat & Chips</td>
                <td>€8.50</td>
                <td><button onclick="addToCart('Chicken Meat & Chips', 8.5)">Add to Cart</button></td>
            </tr>
        </table>

        <h3>Burgers</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Half Pounder</td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Half Pounder', 6)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Chicken Fillet Burger</td>
                <td>€5.00</td>
                <td><button onclick="addToCart('Chicken Fillet Burger', 5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Chicken Burger</td>
                <td>€5.00</td>
                <td><button onclick="addToCart('Chicken Burger', 5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Quarter Pounder</td>
                <td>€5.00</td>
                <td><button onclick="addToCart('Quarter Pounder', 5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Doner Burger</td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Doner Burger', 6)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Cheese Burger</td>
                <td>€4.00</td>
                <td><button onclick="addToCart('Cheese Burger', 4)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Salad Burger</td>
                <td>€3.00</td>
                <td><button onclick="addToCart('Salad Burger', 3)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Regular Burger</td>
                <td>€3.00</td>
                <td><button onclick="addToCart('Regular Burger', 3)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Veggie Burger</td>
                <td>€4.00</td>
                <td><button onclick="addToCart('Veggie Burger', 4)">Add to Cart</button></td>
            </tr>
        </table>

        <h3>Wraps</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Chicken Wrap</td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Chicken Wrap', 6)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Doner Wrap</td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Doner Wrap', 6)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Special Mix Wrap</td>
                <td>€6.50</td>
                <td><button onclick="addToCart('Special Mix Wrap', 6.5)">Add to Cart</button></td>
            </tr>
        </table>

        <h3>Hoagie</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Doner Hoagie</td>
                <td>€8.50</td>
                <td><button onclick="addToCart('Doner Hoagie', 8.5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Chicken Hoagie</td>
                <td>€9.00</td>
                <td><button onclick="addToCart('Chicken Hoagie', 9)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Mix Hoagie</td>
                <td>€9.50</td>
                <td><button onclick="addToCart('Mix Hoagie', 9.5)">Add to Cart</button></td>
            </tr>
        </table>

        <h3>Chips</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Large Chips</td>
                <td>€3.00</td>
                <td><button onclick="addToCart('Large Chips', 3)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Curry Chips</td>
                <td>€4.00</td>
                <td><button onclick="addToCart('Curry Chips', 4)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Garlic Chips</td>
                <td>€4.00</td>
                <td><button onclick="addToCart('Garlic Chips', 4)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Cheese Chips</td>
                <td>€4.00</td>
                <td><button onclick="addToCart('Cheese Chips', 4)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Garlic Cheese Chips</td>
                <td>€5.00</td>
                <td><button onclick="addToCart('Garlic Cheese Chips', 5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Taco Cheese Chips</td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Taco Cheese Chips', 6)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Curry Cheese Chips</td>
                <td>€5.00</td>
                <td><button onclick="addToCart('Curry Cheese Chips', 5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Potato Wedges</td>
                <td>€3.50</td>
                <td><button onclick="addToCart('Potato Wedges', 3.5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Chicken Curry Chips</td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Chicken Curry Chips', 6)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Twisty Fries</td>
                <td>€4.00</td>
                <td><button onclick="addToCart('Twisty Fries', 4)">Add to Cart</button></td>
            </tr>
        </table>

        <h3>Side Orders</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Description</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Chicken Goujons</td>
                <td>6 pcs</td>
                <td>€5.00</td>
                <td><button onclick="addToCart('Chicken Goujons', 5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Spicy Chicken Wings</td>
                <td>6 pcs</td>
                <td>€5.00</td>
                <td><button onclick="addToCart('Spicy Chicken Wings', 5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Chicken Nuggets</td>
                <td>8 pcs</td>
                <td>€4.50</td>
                <td><button onclick="addToCart('Chicken Nuggets', 4.5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Popcorn Chicken</td>
                <td>12 pcs</td>
                <td>€4.00</td>
                <td><button onclick="addToCart('Popcorn Chicken', 4)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Fried Garlic Mushrooms</td>
                <td>8 pcs</td>
                <td>€3.50</td>
                <td><button onclick="addToCart('Fried Garlic Mushrooms', 3.5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Onion Rings</td>
                <td>8 pcs</td>
                <td>€3.50</td>
                <td><button onclick="addToCart('Onion Rings', 3.5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Fresh Naan Bread</td>
                <td></td>
                <td>€2.00</td>
                <td><button onclick="addToCart('Fresh Naan Bread', 2)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Plain Sausages</td>
                <td>2 pcs</td>
                <td>€2.50</td>
                <td><button onclick="addToCart('Plain Sausages', 2.5)">Add to Cart</button></td>
            </tr>
        </table>

        <h3>S.F. Chicken</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Mini Box</td>
                <td>€5.00</td>
                <td><button onclick="addToCart('Mini Box', 5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Snack Box</td>
                <td>€6.50</td>
                <td><button onclick="addToCart('Snack Box', 6.5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Chicken Breast Box</td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Chicken Breast Box', 6)">Add to Cart</button></td>
            </tr>
        </table>

        <h3>Fish</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Fresh Cod</td>
                <td>€5.00</td>
                <td><button onclick="addToCart('Fresh Cod', 5)">Add to Cart</button></td>
            </tr>
            <tr>
                <td>Fresh Cod & Chips</td>
                <td>€7.00</td>
                <td><button onclick="addToCart('Fresh Cod & Chips', 7)">Add to Cart</button></td>
            </tr>
        </table>

        <h3>Drinks</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Cans & Water</td>
                <td>€1.50</td>
                <td><button onclick="addToCart('Cans & Water', 1.5)">Add to Cart</td>
            </tr>
            <tr>
                <td>Drink 500ml Bottle</td>
                <td>€2.00</td>
                <td><button onclick="addToCart('Drink 500ml Bottle', 2)">Add to Cart</td>
            </tr>
            <tr>
                <td>Large Coke</td>
                <td>€3.50</td>
                <td><button onclick="addToCart('Large Coke', 3.5)">Add to Cart</td>
            </tr>
            <tr>
                <td>Small Milk Shake</td>
                <td>€3.00</td>
                <td><button onclick="addToCart('Small Milk Shake', 3)">Add to Cart</td>
            </tr>
            <tr>
                <td>Large Milk Shake</td>
                <td>€4.00</td>
                <td><button onclick="addToCart('Large Milk Shake', 4)">Add to Cart</td>
            </tr>
        </table>

        <h3>Sauces</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Curry Sauce</td>
                <td>€1.50</td>
                <td><button onclick="addToCart('Curry Sauce', 1.5)">Add to Cart</td>
            </tr>
            <tr>
                <td>Taco, Chilli, Garlic, Ketchup, Pink</td>
                <td>€1.00</td>
                <td><button onclick="addToCart('Taco, Chilli, Garlic, Ketchup, Pink', 1)">Add to Cart</td>
            </tr>
        </table>

        <h3>Goujons Meal</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Description</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Goujons Meal</td>
                <td>Chips & Drink</td>
                <td>€7.50</td>
                <td><button onclick="addToCart('Goujons Meal', 7.5)">Add to Cart</td>
            </tr>
        </table>

        <h3>Popcorn Box Meal</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Description</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Popcorn Box Meal</td>
                <td>Chips & Drink</td>
                <td>€7.50</td>
                <td><button onclick="addToCart('Popcorn Box Meal', 7.5)">Add to Cart</td>
            </tr>
        </table>

        <h3>Kids Happy Meal</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Description</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Chicken Nuggets</td>
                <td>4 pcs, Chips & Capri-Sun</td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Chicken Nuggets Kids Meal', 6)">Add to Cart</td>
            </tr>
            <tr>
                <td>Burger</td>
                <td>Chips & Capri-Sun</td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Burger Kids Meal', 6)">Add to Cart</td>
            </tr>
            <tr>
                <td>Sausage</td>
                <td>Chips & Capri-Sun</td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Sausage Kids Meal', 6)">Add to Cart</td>
            </tr>
        </table>

        <h3>Meal Deals</h3>
        <table>
            <tr>
                <th>Item Name</th>
                <th>Description</th>
                <th>Price</th>
                <th></th>
            </tr>
            <tr>
                <td>Doner Kebab Meal</td>
                <td>Chips & Drink</td>
                <td>€11.50</td>
                <td><button onclick="addToCart('Doner Kebab Meal', 11.5)">Add to Cart</td>
            </tr>
            <tr>
                <td>Chicken Kebab Meal</td>
                <td>Chips & Drink</td>
                <td>€12.50</td>
                <td><button onclick="addToCart('Chicken Kebab Meal', 12.5)">Add to Cart</td>
            </tr>
            <tr>
                <td>Mix Kebab Meal</td>
                <td>Chips & Drink</td>
                <td>€13.00</td>
                <td><button onclick="addToCart('Mix Kebab Meal', 13)">Add to Cart</td>
            </tr>
            <tr>
                <td>Doner Wrap Meal</td>
                <td>Chips & Drink</td>
                <td>€9.00</td>
                <td><button onclick="addToCart('Doner Wrap Meal', 9)">Add to Cart</td>
            </tr>
            <tr>
                <td>Chicken Wrap Meal</td>
                <td>Chips & Drink</td>
                <td>€9.00</td>
                <td><button onclick="addToCart('Chicken Wrap Meal', 9)">Add to Cart</td>
            </tr>
            <tr>
                <td>Fish & Chips Meal</td>
                <td>Chips & Drink</td>
                <td>€8.00</td>
                <td><button onclick="addToCart('Fish & Chips Meal', 8)">Add to Cart</td>
            </tr>
            <tr>
                <td>Quarter Pounder Meal</td>
                <td>Chips & Drink</td>
                <td>€8.00</td>
                <td><button onclick="addToCart('Quarter Pounder Meal', 8)">Add to Cart</td>
            </tr>
            <tr>
                <td>Half Pounder Meal</td>
                <td>Chips & Drink</td>
                <td>€9.00</td>
                <td><button onclick="addToCart('Half Pounder Meal', 9)">Add to Cart</td>
            </tr>
            <tr>
                <td>Chicken Burger Meal</td>
                <td>Chips & Drink</td>
                <td>€8.00</td>
                <td><button onclick="addToCart('Chicken Burger Meal', 8)">Add to Cart</td>
            </tr>
            <tr>
                <td>Chicken Fillet Meal</td>
                <td>Chips & Drink</td>
                <td>€9.00</td>
                <td><button onclick="addToCart('Chicken Fillet Meal', 9)">Add to Cart</td>
            </tr>
            <tr>
                <td>10" Pizza Meal</td>
                <td>Chips & Drink</td>
                <td>€13.50</td>
                <td><button onclick="addToCart('10 Pizza Meal', 13.5)">Add to Cart</td>
            </tr>
            <tr>
                <td>12" Pizza Meal</td>
                <td>Chips & Drink</td>
                <td>€15.50</td>
                <td><button onclick="addToCart('12 Pizza Meal', 15.5)">Add to Cart</td>
            </tr>
            <tr>
                <td>16" Pizza Meal</td>
                <td>With any 5 toppings, Garlic Dip, 2 Chips & 2 Drinks</td>
                <td>€22.00</td>
                <td><button onclick="addToCart('16 Pizza Meal', 22)">Add to Cart</td>
            </tr>
            <tr>
                <td>Munchy Box</td>
                <td>2 Goujons, 3 Nuggets, 3 Onion Rings, 2 Sausages, Doner Meat, Chips & Drink</td>
                <td>€12.00</td>
                <td><button onclick="addToCart('Munchy Box', 12)">Add to Cart</td>
            </tr>
            <tr>
                <td>King Feast</td>
                <td>16" Pizza, 10" Garlic Bread, 3 Chips, 1 Curry Dip, 1 Garlic Dip & 1.25ltr Coke</td>
                <td>€30.00</td>
                <td><button onclick="addToCart('King Feast', 30)">Add to Cart</td>
            </tr>
            <tr>
                <td>Kids Happy Meals</td>
                <td>Chicken Nuggets Meal (4 pcs), Burger Meal, Sausage Meal (1 pc), Chips & Capri-Sun</td>
                <td>€6.00</td>
                <td><button onclick="addToCart('Kids Happy Meals', 6)">Add to Cart</td>
            </tr>
        </table>

        <button onclick="orderOnline()">Order Online</button>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contactForm" onsubmit="submitForm(event)">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>
            <label for="subject">Subject:</label>
            <input type="text" id="subject" name="subject" required><br>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea><br>
            <button type="submit">Send</button>
        </form>
        <div class="whatsapp-contact">
            <a href="https://wa.me/353838442425" target="_blank">Contact us on WhatsApp: +353838442425</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 King Pizza. All rights reserved.</p>
    </footer>

    <script src="{% static 'menu/script.js' %}"></script>
</body>
</html>
