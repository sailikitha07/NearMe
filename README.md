# Ex04 Places Around Me
## Date: 22-04-2025

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
##Map.html
```
<html>
    <head>
        <title>
            BANGLORE
        </title>
    </head>
    <body>
        <h1 align="center">BANGLORE(likitha-24009865)</h1>
        <center>
            <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-04-21 203241.png" usemap="#mapnew">
            <map name="mapnew">
                <area target="" alt="Koramangala" title="Koramangala" href="krm.html" coords="616,99,775,142" shape="rect">
                <area target="" alt="Bhannargatta" title="Bhannargatta" href="bng.html" coords="263,71,61" shape="circle">
                <area target="" alt="Banglore palace" title="Banglore palace" href="bnp.html" coords="63,481,107,457,179,485,167,521,60,524" shape="poly">
                <area target="" alt="Marthaali" title="Marthaali" href="mrt.html" coords="589,179,41" shape="circle">
                <area target="" alt="Pheonix" title="Pheonix" href="phn.html" coords="256,405,326,436,289,488,204,473,183,422" shape="poly">
            </map>
        </center>
    </body>
</html>
```
##bng.html
```
<html>
    <head>
        <title>
            BANNERGHATTA
        </title>
        <style>
            p{
                font-size: xx-large;
                color: black;
                
            }
            body{
                background-color:bisque;
            }
        </style>
    </head>
    <body>
        <h1 align="center">Bannerghatta</h1>
        <p>
            Bannerghatta Biological Park, located 22 km south of Bangalore, is a popular tourist destination offering a diverse range of 
        wildlife attractions. It features a zoo, safari park, butterfly park, and an animal rescue center. The park is known for its rich biodiversity 
        and provides an opportunity to see various animals in their natural habitats.

        </p>
        <center>
            <img src="C:\Users\admin\Desktop\5.jpg" width="600" height="300">
        </center>
    </body>
</html>
```
##bnp.html
```
<html>
    <head>
        <title>
            BANGLORE PALACE
        </title>
        <style>
            h1{
                font-size: xx-large;
                color: #de1212;
            }
            p{
                font-size: medium;
            }
            
        </style>
    </head>
    <body>
        <h1 align="center">BANGLORE PALACE

        </h1>
        <p>
            The Bangalore Palace, a blend of Tudor and Scottish Gothic architecture, stands as a prominent landmark in Bengaluru, showcasing the city's 
        historical grandeur. Built in 1873 by Rev. Garett and purchased by  the 23rd Maharaja of Mysore, Chamarajendra Wadiyar, the palace is 
        a popular tourist attraction and venue for events. Its expansive grounds and well-maintained gardens attract visitors, offering a glimpse into the 
        opulence of the Mysore royal family.
        </p>
        <center>
            <img src="C:\Users\admin\Desktop\5.jpg"
        </center>
    </body>
</html>
```
##krm.html
```
<html>
    <head>
        <title>
            PKORAMANGALA
        </title>
        <style>
            p{
                font-size: xx-large;
                color: black;
                
            }
            body{
                background-color:bisque;
            }
        </style>
    </head>
    <body>
        <h1 align="center">Koramangala</h1>
        <p>
            Koramangala is a vibrant and upscale residential and commercial area in Bangalore.It is known for its bustling retail and restaurant scene. It's a major hub for IT 
            professionals and startups, with many restaurants, pubs, and shopping centers. It's also a popular hangout spot for locals and visitors alike
        </p>
        <center>
            <img src="C:\Users\admin\Desktop\3.jpg" width="600" height="300">
        </center>
    </body>
</html>
```
##mrt.html
```
<html>
    <head>
        <title>
            MARATHAHALLI
        </title>
        <style>
            p{
                font-size: xx-large;
                color: black;
                
            }
            body{
                background-color:bisque;
            }
        </style>
    </head>
    <body>
        <h1 align="center">Marathahalli</h1>
        <p>
            Marathahalli is an eastern suburb of Bangalore, Karnataka, known for its well-connected location on the Outer Ring Road and good connectivity
            to other parts of the city, including Whitefield and HAL. It's a popular  residential and commercial area, with a mix of residential projects and IT parks. 
            The locality is named after the Marut fighter aircraft.
    
        </p>
        <center>
            <img src="C:\Users\admin\Downloads\mrt.html1.webp"width="600" height="300">
        </center>
    </body>
</html>
```
##phn.html
```
<html>
    <head>
        <title>
           Phoenix Mall
        </title>
        <style>
            h1{
                font-size: xx-large;
                color: #de1212;
            }
            p{
                font-size: medium;
            }
            
        </style>
    </head>
    <body>
        <h1 align="center">Phoenix_Mall

        </h1>
        <p>
            Phoenix Marketcity in Bangalore is a large shopping mall developed by The Phoenix Mills Co. Ltd.It's known for its extensive retail space, featuring numerous stores, a multiplex, and
            a food court. The mall is a popular destination for both shopping and entertainment, often hosting events and concerts.
    
        </p>
        <center>
            <img src="C:\Users\admin\Desktop\1.jpg"
        </center>
    </body>
</html>
```
##OUTPUT
![Screenshot (2)](https://github.com/user-attachments/assets/33cb832c-3e21-4d4e-b724-144a02b8c42d)
![Screenshot (5)](https://github.com/user-attachments/assets/f1e674ad-eab6-4d18-b7ba-6f0e4d59d269)
![Screenshot (6)](https://github.com/user-attachments/assets/488e6f42-3f87-42da-b62a-6bef8803a6c4)
![Screenshot (4)](https://github.com/user-attachments/assets/1f8f3cf8-646c-479d-b53e-d1bbf4f7926e)
![Screenshot (3)](https://github.com/user-attachments/assets/7604788c-a3c0-4c68-9614-ed3666569907)
![Screenshot 2025-04-22 221754](https://github.com/user-attachments/assets/4c6d6ee5-718d-437e-808a-bb2a560f2d5d)

## RESULT
The program for implementing image maps using HTML is executed successfully.



