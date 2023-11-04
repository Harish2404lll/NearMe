# Ex04 Places Around Me

## DATE : 27.10.2023

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

### INDEX
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"MAP"</title>
    <h1 align="center">
        <font color="blueS" face="cursive">
           HARISH G 23000630- MAP 
        </font>
    </h1>
</head>
<body>
    <img src="/static/map.jpg" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="AGSWATER" title="AGSWATER" href="watersupply.html" coords="289,542,102" shape="circle">
        <area target="" alt="maharishischool" title="maharishischool" href="school.html" coords="532,425,126" shape="circle">
        <area target="" alt="healthcenter" title="healthcenter" href="healthcenter.html" coords="926,532,117" shape="circle">
        <area target="" alt="akkitabadminton" title="akkitabadminton" href="badminton.html" coords="253,205,94" shape="circle">
        <area target="" alt="sumangallisilvershop" title="sumangallisilvershop" href="silvershop.html" coords="800,215,114" shape="circle">
    </map>
</body>
</html>
```
### WATERSUPPLY :
```
<h1 align="center">
    <font color="blueS" face="cursive">
        A G S WATER SUPPLY
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is best water supply company in our areaa<br></LI>     
            <LI>They supplies the water in cheap and best.<br></LI>
        </OL>


    </font>
    <font color ="blue" face = "cursive" size="20" > 
        "BEST WATER SUPPLY COMPANY"
    </font>
```
### SCHOOL :
```
<h1 align="center">
    <font color="purple" face="cursive">
           MAHARISHI NURSERY AND PRIMARY SCHOOL
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>.<br></LI>     
            <LI>This is the best primary and nyrsery school in our area.<br></LI>
            <LI>Students enjoys their studies in that school.<br></LI>
            
        </OL>


    </font>
    <font color ="purple" face = "cursive" size="20" > 
    "FAMOUS NURSERY SCHOOL"
    </font>
```
### HEALTHCARE :
```
<h1 align="center">
    <font color="purple" face="cursive">
        URBAN PRIMARY HEALTH CARE CENTER
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is a very popular Health care center.<br></LI>     
            <LI>They provide the best services at low cost.<br></LI>
            
        </OL>


    </font>
    <font color ="purple" face = "cursive" size="20" > 
    "MOST POPULAR BUS STAND"
    </font>
```
### BATMINTON :
```
<h1 align="center">
    <font color="purple" face="cursive">
           AKKITA BADMINTON CLUB
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is best badminton club in our areaa<br></LI>     
            <LI>youngesters loves to play badminton in that area.<br></LI>
            
        </OL>


    </font>
    <font color ="purple" face = "cursive" size="20" > 
    "BEST WATER SUPPLY COMPANY"
    </font>
```
### SILVER SHOP :
```
<h1 align="center">
    <font color="purple" face="cursive">
        SUMANGALLI SILVER SHOP
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>sumangalli silver shop is the best selling shop in our area<br></LI>     
            <LI>This is the biggest selling shop in our district<br></LI>
            
        </OL>


    </font>
    <font color ="purple" face = "cursive" size="20" > 
    "CHEAP AND BEST SILVER SHOP"
    </font>
```

## OUTPUT
### INDEX :
![WhatsApp Image 2023-11-04 at 08 38 20_6899cc09](https://github.com/Harish2404lll/NearMe/assets/141472096/0cb2c317-4b19-489c-b0dc-798040c7dd2d)

### WATER SUPPLY :
![WhatsApp Image 2023-11-04 at 09 03 15_507445f8](https://github.com/Harish2404lll/NearMe/assets/141472096/cc770cc0-0f70-4790-9f2a-cb2dcce2b2c4)

### SCHOOL :
![WhatsApp Image 2023-11-04 at 09 03 49_bb6a5c49](https://github.com/Harish2404lll/NearMe/assets/141472096/f669399f-63ba-4244-b240-db48480392d6)

### HEALTHCARE :
![WhatsApp Image 2023-11-04 at 09 03 13_7e8a9296](https://github.com/Harish2404lll/NearMe/assets/141472096/3abfc87f-395b-40bc-a7fe-ce0ee21f7e73)

### BADMINTON :
![WhatsApp Image 2023-11-04 at 09 02 16_3ddde0f7](https://github.com/Harish2404lll/NearMe/assets/141472096/d8f3182f-03f6-49f5-834d-9fd93b89473b)

### SILVER SHOP :
![WhatsApp Image 2023-11-04 at 08 39 14_d9c9d1c9](https://github.com/Harish2404lll/NearMe/assets/141472096/64009f8b-eb3a-4767-a4b3-4c1031639653)

## RESULT
The program for implementing image maps using HTML is executed successfully.
