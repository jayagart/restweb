# Ex.07 Restaurant Website
## Date:12/12/2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html



<html>
    <head>
        

        <style>
            
            .container{
                width: 1500px;
                height: 100%;
                position: absolute;
                
            }
            body{
                overflow-x: hidden;
                margin: 0;
            }
            .box{
                width: 5000px;
                height: 160px;
                position: absolute;    
            }
            h1{
                top: 30px;
                left: 35%;
                color: rgb(248, 243, 243);
                font-style: italic;
                position: relative;
                font-size: 120px;
                display: flex;
                text-shadow:  0 0 5px #ffffff,   
                   0 0 15px #ffffff;
            }
            .word{
                position: absolute;
                right: 1400px;
                text-align: center;
                bottom: -200%;
                
                

                

            }
            .word a{
                text-decoration: none;
                color:rgb(248, 243, 243);
                font-style: italic;
                padding: 180px;
                font-size: 80px;
            
                
                
            }

            .word button{
                border: none;
                background: none;
                padding: 10px 10px;
                cursor: pointer
            }
            .word button:hover{
                background-color: white;
                border-radius: 5px ;   
            } 
            .class{
                
                height: 2300px;
                width: 6200px;
                
                
                background-image: url('b1.jpg');
               


            }
            .class h2{
                position: absolute;
                color:rgb(248, 243, 243);
                font-style: italic;
                font-size: 45px;

                top: 37%;
                left: 10%;

            }
            
            
            .class p{
                color:rgb(248, 243, 243);
                font-style: italic;

                position:absolute;
                top: 42%;
                left: 10%;
                right: -10%;
                font-size: 50px;
            }
            
        
            .time p{
                color:rgb(248, 243, 243);
                font-size: 80px;
                font-style: italic;
                left: 130%;
                position: absolute;
            
                
                top: 40%;
                
            }
            footer{
                    
                    background-color: black;
                   width: 6200px;
                   height: 160px;
                    
                    
                    
                   }
           
        footer p{
                    font-style: italic;
                    position: absolute;
                    text-align: center;
                    right: -1400px;
                    color:rgb(248, 243, 243);
                    font-size: 40px;
               }
         .book-table {
                   background-color: #faebd7; 
                   border: 1px solid #ddd; 
                   border-radius: 8px; 
                   padding: 16px;
                   text-align: center;
                box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.1); 
            }

        .book-table h3 {
            font-size: 20px;
            font-style: italic;
            color: #333; 
          }
       .book-table p {
           font-size: 60px;
           font-style: italic;
           position: absolute;
           top: 44%;
           left: 50%;
           right: 10px;

           color: rgb(248, 243, 243); 
           
        }

         .book-table-link {
             display: inline-block;
            font-size: 60px;
            color: rgb(248, 243, 243);
             
            padding: 10px 20px;
           font-style: italic;
           
           position: absolute;
           top: 38%;
           right: 1500px;
  
}

.book-table-link:hover {
  background-color: chocolate; 
}

           
            
        </style>
    </head>
    <body>
        <div class="container">
            <div class="box">
                <h1>MARINER'S FEAST</h1>
                 <h2 class="word">
                    <a href="home.html">Home</a>
                    <a href="menu.html">Menu</a>
                    <a href="admin.html">Administrator</a>
                    <a href="contact.html">Contact us</a>
                </h2>

            </div>
            <div class="class">
                <h2>About Us</h2>
                <p>
                   <b> Welcome to MARINER'S FEAST</b> The ultimate destination for seafood lovers! Nestled in the heart of [chennai], our restaurant brings the freshness of the ocean straight to your plate. Inspired by the vibrant flavors of the sea, Mariner's Freak is dedicated to serving the finest, freshest seafood prepared with passion and expertise.<br>

                  <br> At Mariner’s Freak, every dish tells a story of oceanic adventure. Our menu boasts a wide array of delicacies, from succulent grilled prawns and buttery lobster tails to hearty crab bisques and refreshing ceviche. We take pride in sourcing our seafood responsibly, ensuring that every bite is not only delicious but also sustainable.<br>
                   
                  <br> The ambiance at Mariner’s Freak mirrors the tranquil beauty of the sea. With nautical-themed decor, soothing blues, and soft lighting, we’ve created the perfect setting for a memorable dining experience. Whether you’re enjoying a cozy dinner with loved ones, celebrating a special occasion, or simply indulging in your love for seafood, Mariner’s Freak promises to make every visit unforgettable.<br>
                   
                   <br>Dive into the flavors of the ocean at Mariner’s Freak – where every meal is a celebration of the sea.<br>
                </p>
                
            </div>
            
            <div class="time">
                <p>
                   
                    Opening Hours:<br> Mo to fr - 8am to 8pm |<br>
                    Sat & Sun - 8am to 11pm

                </p>
            
            </div>
            <footer class="footer">
                <p>&copy; 2024 MARINER'S FEAST. All copyrights reserved | Designed by JAYAGAR.T.</p>
                </footer>
        </div>
        


        <div class="book-table">
            <h3>Book a table</h3>
            <img src="b1 (2).jpg"  class="book-table-image">
            <p>
                Step into a world of delicious flavors and warm hospitality at [MARINER'S FEAST].
                <br> Whether you're planning a romantic dinner, a celebration with friends, or simply treating yourself to <br>something special, we’re here to make it unforgettable.<br> 
                Our cozy ambiance, mouthwatering dishes, and top-notch service are waiting for you.<br>

               Don’t wait—secure your table today and let us take care of the rest.<br> Booking is quick and easy, so reserve your spot now and get ready for an exceptional dining experience!
            </p>
            <a href="#" class="book-table-link">Book your table </a>
          </div>
          
        
    </body>
</htm>

menu.html

<html>
    <head>
        <style>
            .box{

                font-size: 60px;
                text-align: center;
                font-style: italic;

            }
            .imn1{
                height: 620px;
                width: 821px;
                left: 400px;
                position: absolute;
                

            }
             h2{
                font-style: italic;
                font-size: 50px;
                left: 400px;
                position: absolute;
                bottom: 1420px;
                

            }
            .imn2{
                height: 620px;
                width: 821px;
                left: 1400px;
                position: absolute;
            }
            h3{
                font-size: 50px;
                font-style: italic;
                left: 1400px;
                position: absolute;
                bottom: 1360px;
            }
            .imn3{
                height: 800px;
                width: 821px;
                left: 2400px;
                position: absolute;
            }
            h4{
                font-size: 50px;
                font-style: italic;
                left: 2440px;
                position: absolute;
                bottom: 1220px;
            }
            .imn4{
                height:620px;
                width:821px;
                left: 3480px;
                position: absolute;

            }
            h5{
                font-size: 50px;
                font-style: italic;
                left: 3470px;
                position: absolute;
                bottom: 1270px;
            }
            .imn5{
                height: 620px;
                width: 821px;
                left: 400px;
                bottom: 450px;
                position: absolute;

            }
            h6{
                font-size: 50px;
                font-style: italic;
                left: 400px;
                position: absolute;
                bottom: 200px;

            }
            .imn6{
                height: 620px;
                width: 821px;
                left: 1400px;
                bottom: 450px;
                position: absolute;

            }
            h7{
                font-size: 50px;
                font-style: italic;
                left:1460px ;
                position: absolute;
                bottom:360px;

            }
            .imn7{
                height: 620px;
                width: 821px;
                left: 2400px;
                bottom: 450px;
                position: absolute;

            }
            h8{
                font-size: 50px;
                font-style: italic;
                left: 2380px;
                position: absolute;
                bottom: 320px;

            }
            .imn8{
                height: 620px;
                width: 821px;
                left: 3480px;
                bottom: 450px;
                position: absolute;

            }
            h9{
                font-size: 50px;
                font-style: italic;
                position: absolute;
                left: 3470px;
                bottom: 280px;
            }
            .imn9{
                height: 620px;
                width: 821px;
                position: absolute;
                left:400px;
                bottom: -600px;

            }
            h10{
                font-size: 50px;
                font-style: italic;
                position: absolute;
                left: 400px;
                bottom: -720px;

            }
            .imn10{
                height: 620px;
                width: 821px;
                position: absolute;
                left:1420px;
                bottom: -600px;

            }
            h11{
                font-size: 50px;
                font-style: italic;
                position: absolute;
                left: 1420px ;
                bottom: -840px;


            }
            .imn11{
                height: 620px;
                width: 821px;
                position: absolute;
                left:2400px;
                bottom: -600px;

            }
            h12{
                font-size: 50px;
                font-style: italic;
                position: absolute;
                left: 2500px;
                bottom: -680px;

            }
            .imn12{
                height: 620px;
                width: 821px;
                position: absolute;
                left:3480px;
                bottom: -600px;

            }
            h13{
                font-size: 50px;
                font-style: italic;
                position: absolute;
                left:3470px;
                
                bottom: -680;

            }
            footer{
                font-style: italic;
                right: 1400px;
                background-color: black;
                bottom: -1000px;
                width: 1500px;
                font-size: 40px;
                position: absolute;
                color: rgb(248, 243, 243);
                text-align: center;
            }
            

            

        </style>
    </head>
    <body>
        <div class="box">
            <h1>Menu</h1>
        </div>
        <div>
            <img src="d1.jpg" class="imn1">
            <h2>Mezze manichie pasta. (Rs - 249)
            </h2>
        
            <img src="d2.jpg" class="imn2">
            <h3>seared scallops on a bed of vegetable. <br>(Rs - 199)
                
                
            </h3>

            <img src="d3.jpg" class="imn3">
            <h4>Prawn plated with Greens.(Rs - 199)
                <br>

            </h4>

            <img src="d4.jpg" class="imn4">
            <h5>Seafood platter. Grilled lobster,<br> shrimps, scallops, langoustines, octopus,<br> squid on white plate. (Rs - 399)
                <br>

            </h5>

            <img src="d5.jpg" class="imn5">
            <h6>Composition of squid,shrimp,<br>
                salmon steak and octopus. (Rs - 349)<br>

            </h6>

            <img src="d6.jpg" class="imn6">
            <h7><b>juicy octopus. (rs - 269)</b>
                <br>

            </h7>

            <img src="d7.jpg" class="imn7">
            <h8><b>Grilled fish with spices, Indian cuisine.<br> (Rs - 499)</b>
                <br>

            </h8> 

            <img src="d8.jpg" class="imn8">
            <h9><b>Italian pasta with seafood and herbs.<br> (Rs - 149) <br>
                <br>

            </h9>

            <img src="d9.jpg" class="imn9">
            <h10><b>Fresh seafood shrimps served on table<br> with wine. (Rs - 699)</b>
                <br>

            </h10>

            <img src="d12.jpg" class="imn10">
            <h11><b>Brazilian food: Moqueca Baiana of fish and <br>bell peppers in spicy coconut sauce <br>close-up on a plate on a table. <br> (Rs - 299)
                <br>

            </h11>

            <img src="d11.jpg" class="imn11">
            <h12><b>King's plate. (Rs - 699)</b>

            </h12>

            <img src="d10.jpg" class="imn12">
            <h13>
               <b> Prawns on Bed of Veggies. (Rs - 199)</b>

            </h13>
            <footer class="footer">
                <p>&copy; 2024 MARINER'S FEAST. All copyrights reserved | Designed by JAYAGAR.T.</p>
                </footer>
        </div>

    </body>
</html>

admin.html

<html>
    <head>
        
        
        <style>
             .box{
                font-size: 100px;
                left: 100px;
                top: 10px;
                position: absolute;   
                
            }
            h1{
                text-align: center;
                left: 1700px;
                color:rgba(255, 255, 255, 0.915);
                font-style: italic;
                
                text-shadow:  0 0 5px #ffffff,   
                   0 0 15px #ffffff;
                position: absolute;
                font-size: 100px;
             }
             body{
                overflow-x: hidden;
                margin: 0;
             }

            
            
            .pic{
                width:450px;
                height:600px;
                top: 35%;
                left:6%;
                position:absolute;
                border-radius: 5px;
            }
            h2{
                position:absolute;
                top: 60%;
                left: 8%;
                color: white;
                font-size: 40px;
            }
            .pic1{
                width: 600px;
                height: 600px;
                top:35%;
                left: 20%;
                position:absolute;
                border-radius: 5px;
            }
            h3{
                top:60%;
                position:absolute;
                left: 25%;
                color:white;
                font-size: 25px;
                font-size: 40px;
            }
            .pic2{
                width: 650px;
                height: 600px;
                top:35%;
                left: 38%;
                position:absolute;
                border-radius: 5px;

            }
            h4{
                top:59%;
                position:absolute;
                left: 44%;
                color:white;
                font-size: 25px;
                font-size: 40px;
            }
            .pic3{
                width: 650px;
                height: 600px;
                top:35%;
                left: 59%;
                position:absolute;
                border-radius: 5px;

            }
            h5{
                top:59%;
                position:absolute;
                left: 64%;
                color:white;
                font-size: 25px;
                font-size: 40px;
            }
            .pic4{
                width: 650px;
                height: 600px;
                top:35%;
                left: 79%;
                position:absolute;
                border-radius: 5px;

            }
            h6{
                top:58%;
                position:absolute;
                left: 84%;
                color:white;
                font-size: 25px;
                font-size: 40px;
            }
            
            p{
                top:47%;
                position:absolute;
                left: 85%;
                color:white;
                font-size: 25px;


            }
           
           footer{
                    
                    background-color: black;
                   width: 6200px;
                   height: 160px;
                    
                    position: absolute;
                    
                   }
                   footer p{
                    text-align: center;
                    color: rgb(248, 243, 243);
                    font-style: italic;
                    left: 1700px;
                    font-size: 40px;
                    bottom: 0%;

                   }
        </style>
        <body>
            <div class="box">
                <h1>Administrators</h1>
            </div>
            <div>
                <img src="b3.jpg"  height="2250px" width="6200">
                <img src="chef5.jpg" class="pic">
                <h2>Jayagar.T (CEO)
                </h2>
                <img src="chef 1.webp" class="pic1">
                <h3>Chef.ROSE</h3>
                <img src="chef2.webp" class="pic2">
                <h4>Chef.AURORA</h4>
                
                <img src="chef3.jpg" class="pic3">
                <h5>Chef. DHAMU

                </h5>
                <img src="chef4.jpg" class="pic4">
                <h6>Chef.BHAT</h6>
                

                <footer>
                    <p>&copy; 2024 MARINER'S FEAST. All copyrights reserved | Designed by JAYAGAR.T.</p>
                    </footer>
                
                
            </div>
            
            
            
        </body>
    </head>
</html>

contact.html

<html>
    <head>
        <style>
            .box{
                width: 4620px;
                height: 140px;
                background-color: black;
                position: relative;
                
                
                
            }
            h1{
                top: 25%;
                color:rgba(255, 255, 255, 0.915);
                position: relative;
                font-style: italic;
                font-size: 70px;
                text-align: center;
                text-shadow:  0 0 5px #ffffff,   
                   0 0 15px #ffffff;
                
             }
             body{
                overflow-x: hidden;
                margin: 0;
             }

            
            h2{
                color: aliceblue;
                font-style: italic;
                position: absolute;
                top: 30%;
                left: 10%;
                font-size:80px;
            }
            p{
                color: rgb(247, 240, 240);
                top: 35%;
                left: 15%;
                position: absolute;
                font-style: italic;
                padding: 30px;
                font-size: 60px;
            }
            
            footer{
                position:fixed;
            text-align: center;
            color:rgb(247, 240, 240);
            background-color: black;
            width: 4620px;
            height:140px;
            bottom:0%;
            position: absolute;
            font-size: 40px;
            font-style: italic;
           
           }
           body{
                overflow-y: hidden;
                margin: 0;
            }
            .thanksgiving p{
                font-size: 70px;
                font-style: italic;
                color: rgb(247, 240, 240);
                left: 8px;
                top: 1200px;

            }
            .visit{
                font-size: 60px;
                left: 100px;

            }
            
        


        </style>
        <body>
            <div class="box">
                <h1>CONTACT US</h1>
    
            </div>
            <div>
                <img src="bg.jpg" width="100%" height="2500">
                <h2>For Contact:</h2>
                <p>Phone No.: 9342087376<br>

                Email: marinersfeast6996@gmail.com</p>
                <footer>
                    &copy; 2024 MARINER'S FEAST. All copyrights reserved | Designed by JAYAGAR.T
                </footer>
            </div>
            <div class="Thanksgiving">

                <p>
                        
                    <br>This Thanksgiving, gather your loved ones and set sail on a culinary journey at Mariners Feast. Our tables are adorned with the bounty of the season, offering a feast filled with gratitude, warmth, and togetherness. From savory classics like roasted turkey and buttery mashed potatoes to indulgent desserts that capture the essence of autumn, every bite is a celebration of the harvest.<br>

                 <br>At Mariners Feast, we believe in creating memories that last a lifetime. Let us be part of your Thanksgiving tradition as we share the joy of great food, heartfelt thanks, and cherished company. Reserve your table today, and join us in giving thanks the Mariners way.<br>


                </p>

                <div class="visit">

                    <p>
                        "Feasts of Gratitude at Mariners"
                    </p>
                </div>
                

        </body>
    </head>
</html>

```


## OUTPUT:
![alt text](<vijay/restapp/static/Screenshot 2024-12-12 213349.png>)
![alt text](<vijay/restapp/static/Screenshot 2024-12-12 213359.png>)
![alt text](<vijay/restapp/static/Screenshot 2024-12-12 213417.png>)
![alt text](<vijay/restapp/static/Screenshot 2024-12-12 213433.png>)
![alt text](<vijay/restapp/static/Screenshot 2024-12-12 213454.png>)






## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
