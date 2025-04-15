# Ex04 Places Around Me
# Date:13.03.2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE 
```
chruch.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>church</title>
</head>
<body bgcolor="green">
    <font color="black"><b>MADHAVARAM</b></font>
</h1>
  <h3 align="center">
    <font color="blue"><b>CHURCH<sub>-</sub>St sebastian chruch</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
    <font face="avenue" size="5">
        St. Sebastian Church in Madhavaram is a prominent Roman Catholic church located in Chennai, Tamil Nadu.
         Known for its peaceful ambiance and beautiful architecture, the church is a place of deep devotion for the local Catholic community. It is dedicated to St. Sebastian, 
         a Christian martyr known for his unwavering faith. 
         The church holds regular Mass services, novenas,
          and is especially vibrant during feast celebrations, drawing people from surrounding areas. It serves not only as a spiritual center but also plays a role in community 
        development and outreach.
    </font>
</p>
</body>
</html> 

home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>church</title>
</head>
<body bgcolor="pink">
    <font color="black"><b>MADHAVARAM</b></font>
</h1>
  <h3 align="center">
    <font color="blue"><b>CHURCH<sub>-</sub>St sebastian chruch</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
    <font face="avenue" size="5">
        Casagrand Premier Builder Limited is a prominent real estate developer headquartered in Chennai, Tamil Nadu.
        Established in 2003, the company has made significant strides in the real estate sector, particularly in South India.​  
    </font>
</p>
</body>
</html>

hospital.html 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>church</title>
</head>
<body bgcolor="red">
    <font color="black"><b>MADHAVARAM</b></font>
</h1>
  <h3 align="center">
    <font color="blue"><b>CHURCH<sub>-</sub>St sebastian chruch</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
    <font face="avenue" size="5">
        Madhavaram, a neighborhood in Chennai,
        offers a variety of hospitals catering to diverse healthcare needs.
        Here are some notable hospitals in the area:
        St. Anthony’s Hospital
        KM Multi Speciality Hospital

    </font>
</p>
</body>
</html>
 
turf.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>church</title>
</head>
<body bgcolor="blue">
    <font color="black"><b>MADHAVARAM</b></font>
</h1>
  <h3 align="center">
    <font color="blue"><b>CHURCH<sub>-</sub>St sebastian chruch</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
    <font face="avenue" size="5">
        Artificial turf is a surface made of synthetic fibers designed to mimic the look and feel of natural grass.
        Initially gaining prominence in the 1960s with the introduction of AstroTurf, it has since evolved significantly.
        Modern artificial turf is used in various settings, including sports arenas, residential lawns, and commercial landscapes.​
    </font>
</p>
</body>
</html>

vijaypark.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>church</title>
</head>
<body bgcolor="yellow">
    <font color="black"><b>MADHAVARAM</b></font>
</h1>
  <h3 align="center">
    <font color="blue"><b>CHURCH<sub>-</sub>St sebastian chruch</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
    <font face="avenue" size="5">
        Hotel Vijay Park is a chain of business-class hotels
        offering comfortable accommodations and modern amenities across multiple locations in Chennai and Coimbatore.
    </font>
</p>
</body>
</html>

web.html

<html>
<head>
    <title>My city</title>
</head>
<body>
    <h1 align="center">
    <font color="black"><b>MADHAVARAM</b></font>
    </h1>
    <center>
        <img src="map.png" usemap="#area near my home" height="700" width="1500">
        <map name="MADHAVARAM">
        <area shape="rect" coords="1237,484,1446,656" href="home.html" title="Home">
        <area shape="rect" coords="629,81,333,273" href="vijaypark.html" title="vijaypark">
        <area shape="rect" coords="179,487,404,62"   href="hospital.html" title="meridian hospital">
        <area shape="circle" coords="770,434,166"   href="turf.html" title="TURF">
        <area shap="rect"  coords="1403,211,1738,372"  href="church.html" title="CHURCH">
        </map>
    </center>
</body>
</html>
```


# OUTPUT
![alt text](<tarun/mapapp/static/Screenshot 2025-04-15 221244.png>)
![alt text](<tarun/mapapp/static/Screenshot 2025-04-15 221326.png>)
![alt text](<tarun/mapapp/static/Screenshot 2025-04-15 221356.png>)
![alt text](<tarun/mapapp/static/Screenshot 2025-04-15 221427.png>)
![alt text](<tarun/mapapp/static/Screenshot 2025-04-15 221504.png>)
![alt text](<tarun/mapapp/static/Screenshot 2025-04-15 221531.png>)
# RESULT
The program for implementing image maps using HTML is executed successfully.
