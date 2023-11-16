# Ex04 Places Around Me
## Date: 16.11.2023

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
<title> My City </title>
</head>
<body>
<h1 align="center"> 
<font color="charcoal"><b> Kanchipuram </b></font>
</h1>
<h3 align="center">
<font color="black"><b> Shanmuga Vasanth M (23008968)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="910" width="2050">
<map name="MyCity">
<area shape="rect" coords="1000,400,1180,465" href="home.html" title="My Home Town">
<area shape="rect" coords="1460,70,1750,120" href="silk.html" title="Prakash Silks & Sarees">
<area shape="rect" coords="1050,30,1200,80" href="cinema.html" title="Babu Cinemas">
<area shape="circle" coords="490,640,60" href="lake.html" title="Sevlimedu Lake">
<area shape="rect" coords="900,210,1140,300" href="office.html" title="Collector Office">
</map>
</center>
</body>
</html>


home.html

<html>
<head>
<title> My Home Town </title>
</head>
<body bgcolor="lavender">
<h1 align="center">
<font color="charcoal"><b> Kanchipuram </b></font>
</h1>
<h3 align="center">
<font color="blue"><b> Karur - My Home Town </b></font>
</h3>
<hr size="3" color="grey">
<p align="justify">
<font face="Georgia" size="5">
Karur village, situated in the Kanchipuram district of Tamil Nadu, embodies a population of approximately [mention population number if available] residents. Its economy thrives primarily on agriculture, with rice, sugarcane, and vegetables being major crops cultivated in the fertile lands. Additionally, handloom weaving and textile industries contribute significantly to the village's economic sustenance, renowned for producing exquisite fabrics.
Culture in Karur village is deeply rooted in traditions and heritage. The village celebrates various festivals with fervor, including Pongal, Diwali, and local temple festivals, where rituals, dance, and music play a central role. Temples dot the landscape, showcasing the village's religious significance and architectural beauty. The community holds traditional values in high regard, fostering a close-knit society where customs and rituals are preserved with pride. Karur village cherishes its cultural heritage while embracing modern influences, creating a harmonious blend of tradition and progress.
</font>
</p>
</body>
</html>


silk.html

<html>
<head>
<title> Prakash Silks & Sarees </title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="charcoal"><b> Kanchipuram </b></font>
</h1>
<h3 align="center">
<font color="blue"><b> Prakash Silks & Sarees </b></font>
</h3>
<hr size="3" color="grey">
<p align="justify">
<font face="Georgia" size="5">
Prakash Silk & Sarees is a well-known establishment situated in Kanchipuram, a city renowned for its exquisite silk sarees in Tamil Nadu, India. This store is highly regarded for its collection of high-quality silk sarees, including the famous Kanchipuram silk sarees known for their intricate designs, vibrant colors, and fine craftsmanship.
Prakash Silk & Sarees offers a wide range of traditional and contemporary silk sarees, catering to various tastes and preferences. The store is recognized for its commitment to providing customers with authentic and superior-quality silk products, making it a preferred destination for those seeking elegant and culturally significant attire.
This establishment typically attracts both locals and tourists seeking to purchase or explore the beauty of Kanchipuram silk sarees, showcasing the rich heritage and craftsmanship of the region's textile industry. 
</font>
</p>
</body>
</html>


cinema.html

<html>
<head>
<title> Babu Cinemas </title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="charcoal"><b> Kanchipuram </b></font>
</h1>
<h3 align="center">
<font color="blue"><b> Babu Cinemas </b></font>
</h3>
<hr size="3" color="grey">
<p align="justify">
<font face="Georgia" size="5">
Situated in the cultural city of Kanchipuram, our babu cinema theatre stands as a hub of entertainment and cultural experiences. The theatre embodies a blend of modern cinematic technology and traditional architectural aesthetics. With its inviting facade and well-maintained premises, it offers a comfortable and enjoyable movie-watching experience for patrons. The theatre screens a diverse range of films, catering to various preferences, from mainstream blockbusters to regional cinema, ensuring something for everyone. Inside, the spacious seating arrangements and state-of-the-art sound and projection systems enhance the viewing pleasure. The theatre is not just a place for movies but also serves as a social gathering spot, fostering a sense of community among movie enthusiasts in Kanchipuram. Its central location makes it easily accessible, contributing to its popularity among locals and visitors alike.
</font>
</p>
</body>
</html>


lake.html

<html>
<head>
<title> Sevlimedu Lake </title>
</head>
<body bgcolor="lightgrey">
<h1 align="center">
<font color="charcoal"><b> Kanchipuram </b></font>
</h1>
<h3 align="center">
<font color="blue"><b> Sevlimedu Lake </b></font>
</h3>
<hr size="3" color="grey">
<p align="justify">
<font face="Georgia" size="5">
Sevlimedu Lake is a picturesque water body nestled in Kanchipuram, Tamil Nadu, offering serene natural beauty and tranquility. Spread across a vast expanse, the lake serves as a serene retreat amidst lush greenery and peaceful surroundings. Its pristine waters and scenic landscape attract visitors seeking a respite from the hustle and bustle of city life.
This freshwater lake not only serves as a sightseeing spot but also plays a crucial role in supporting the local ecosystem by providing a habitat for various bird species and aquatic life. Visitors can indulge in leisurely walks along the lake's banks, enjoying the cool breeze and captivating views.
Sevlimedu Lake is not only a scenic delight but also holds cultural and environmental significance for the local community, serving as a source of freshwater and a place for relaxation and natural rejuvenation.
</font>
</p>
</body>
</html>


office.html

<html>
<head>
<title> Collector Office </title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="charcoal"><b> Kanchipuram </b></font>
</h1>
<h3 align="center">
<font color="blue"><b> Kanchipuram District Collector Office </b></font>
</h3>
<hr size="3" color="grey">
<p align="justify">
<font face="Georgia" size="5">
The Collector's Office in Kanchipuram serves as the administrative hub for the district's governance, situated in the heart of the city. This pivotal government institution oversees various essential functions, including revenue administration, law and order, public welfare schemes, and overall district development. It acts as the focal point for coordinating and implementing government policies and initiatives at the local level. The office facilitates the issuance of important documents such as land records, certificates, and permits, ensuring efficient public service delivery. Moreover, it plays a crucial role in disaster management and relief efforts during emergencies. With its multifaceted responsibilities, the Collector's Office in Kanchipuram stands as a cornerstone in maintaining the district's civic infrastructure and ensuring the well-being of its residents.
</font>
</p>
</body>
</html>

```

## OUTPUT

![Alt text](<Image Map.png>)
![Alt text](<My Home Town.png>)
![Alt text](<Prakash Silk & Sarees.png>)
![Alt text](<Babu Cinemas.png>)
![Alt text](<Sevlimedu Lake.png>)
![Alt text](<Collector Office.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
