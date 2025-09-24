# Ex04 Places Around Me
## Date: 23.09.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
        <title>Tiruvannamalai</title>
    </head>
    <body>
        <center>
            <h1>Arni (Sridharan B-25016127)</h1>
        </center>
    </body>
</html><img src="Screenshot 2025-09-20 141905.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="asif biriyani" title="asif biriyani" href="biryani.html" coords="186,648,92" shape="circle">
    <area target="" alt="rajeshwari theatre" title="rajeshwari theatre" href="theatre.html" coords="1223,531,1386,637" shape="rect">
    <area target="" alt="sathya agencies" title="sathya agencies" href="sathya.html" coords="882,304,1153,439" shape="rect">
    <area target="" alt="lakshmi theatre" title="lakshmi theatre" href="theatre2.html" coords="466,361,651,458" shape="rect">
    <area target="" alt="paary sweets and bakery" title="paary sweets and bakery" href="paary.html" coords="515,218,515,311,742,314,752,233" shape="poly">
</map>

biryani.html

<html>
    <head>
        <title>Biriyani</title>
    </head>
    <body bgcolor="red" text="white">
        <center>
            <h1>Asif Biriyani</h1>
        </center>
        <hr>
        <p>Aasife Biriyani is a Chennai-based restaurant chain founded by C.Y. Aasife in 1999, which grew from a small street-side pushcart to a global brand recognized for its authentic, flavor-rich biryanis made with fresh ingredients and traditional cooking methods. With over 45 outlets across Tamil Nadu, Kerala, Andhra Pradesh, Karnataka, and in Sri Lanka and the UAE, the brand offers a diverse menu including signature biryanis, side dishes, and beverages, and is often referred to as the "World's Best Biryani Restaurant"</p>
        <h2>Menu :</h2>
        <ul>
            <li>Chicken Biriyani - 100/-</li>
            <li>Mutton Biriyani - 200/-</li>
            <li>Chicken 65 - 100/-</li>
            <li>Grill - 150/-</li>
            <li>Chicken Rice - 130/-</li>
        </ul><br><br>
        <center>
            <h3>for contact : 824*******</h3>
            <h3>Email address : asifbiriyani@gmail.com</h3>
        </center> 

    </body>
</html>

paary.html

<html>
    <head>
        <title>Paary</title>
    </head>
    <body bgcolor="blue" text="white">
        <center>
            <h1>Paary Sweets and Bakery</h1>
        </center>
        <hr>
        <p>Paary Sweets & Bakery is a popular confectionery in Arani and the surrounding area, offering a wide array of sweets, baked goods, and snacks like cakes, pastries, and fast food. The bakery emphasizes quality ingredients and serves as a go-to spot for traditional Indian sweets, festive treats, and customized cakes for special occasions. Customers can order online for delivery or visit the physical location to enjoy their products, which are known for their taste and variety.  
Products and Offerings</p>
        <ul>
            <li>sweet 1kg - 240/-</li>
            <li>Kaaram 1kg - 240/-</li>
            <li>Cake 1kg - 400/-</li>
            <li>Ice Cake 1kg - 600/-</li>
            <li>Tea - 15/-</li>
        </ul><br><br>
        <center>
            <h2>for contact : 8248******</h2>
            <h2>Email address : paarysab@gmail.com</h2>
        </center>
    </body>
</html>

sathya.html

<html>
    <head>
        <title>Sathya</title>
    </head>
    <body bgcolor="green" text="white">
        <center>
            <h1>Sathya Agencies</h1>
        </center>
        <hr>
        <p>Sathya Agencies Pvt. Ltd. is a retail chain founded in 1983 in Tuticorin, Tamil Nadu, that sells consumer electronics, household appliances, mobiles, and kitchenware across South India, with hundreds of branches and a strong online presence. Known for its wide range of products and customer service, it also offers installment plans and exchange offers. 
</p>
        <ul>
            <li>Tv 32'inch - 25000/-</li>
            <li>Refrigerator - 30000/-</li>
            <li>Mobile - 15000/-</li>
            <li>AC - 35000/-</li>
            <li>Washing machine - 40000/-</li>
        </ul><br><br>
        <center>
            <h2>For contact : 8248******</h2>
            <h2>Email address : sathyaagencies@gamil.com</h2>
        </center>
    </body>
</html>

theatre.html

<html>
    <head>
        <title>Rajeswari theatre</title>
    </head>
    <body bgcolor="yellow">
        <center>
        <h1>Rajeswari Theatre (AC)</h1>
        </center>
        <hr>
        <p>"Rajeswari Theatre" refers to multiple cinema halls in Tamil Nadu, India, with the most prominent being the AVM Rajeswari Theatre in Vadapalani, Chennai, which was an iconic, single-screen establishment owned by the famous AVM Group but has since been permanently closed. Other "Rajeswari" theaters include Shri Rajeswari Cinemas in Arni, a modern multiplex with 4K Dolby Atmos, and Ms Rw Cinemas Rajeshwari in places like Arakkonam and Thiruthani, which are also listed on booking sites. 
</p>
        <h2>Movie Time</h2>
        <ul>
            <li>11:00 am - 2:00 pm</li>
            <li>2:30 pm - 5:30 pm</li>
            <li>6:00 pm - 9:30 pm</li>
            <li>10:00 pm - 1:00 pm</li>
        </ul><br><br>
        <center>
            <h3>For contact : 9843******</h3>
            <h3>Email address : rajeswaritheatre@gmail.com</h3>
        </center>
    </body>
</html>

theatre2.html

<html>
    <head>
        <title>Lakshmi theatre</title>
    </head>
    <body bgcolor="purple" text="white">
        <center>
        <h1>Lakshmi Theatre (AC)</h1>
        </center>
        <hr>
        <p>Lakshmi Theatre" refers to various different entertainment venues across Tamil Nadu, including auditoriums in Tiruvallur and cinema halls in Arcot, Chennai, and Madurai. The services and features vary by location, but they generally serve as either a venue for events or a movie theater showing films. 
</p>
        <h2>Movie Time</h2>
        <ul>
            <li>11:00 am - 2:00 pm</li>
            <li>2:30 pm - 5:30 pm</li>
            <li>6:00 pm - 9:30 pm</li>
            <li>10:00 pm - 1:00 pm</li>
        </ul><br><br>
        <center>
            <h3>For contact : 9843******</h3>
            <h3>Email address : Lakshmitheatre@gmail.com</h3>
        </center>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (23)-1.png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
