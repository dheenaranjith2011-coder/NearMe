# Ex04 Places Around Me
## Date: 26/09/2025

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
    <title>My City</title>
</head>
<body>
    <h1 align="center">
        <font color="blue"><b>Namakkal</b></font>
    </h1>
    <h3 align="center">
        <font color="red"><b>Dheenadhaya S R (25017597)</b></font>
    </h3>
    <center>
        
       <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="My Home Town" title="My Home Town" href="home.html" coords="886,105,1020,166" shape="rect">
    <area target="" alt="Muthugapati" title="Muthugapati" href="temple.html" coords="867,360,943,353,966,299,905,268,855,303" shape="poly">
    <area target="" alt="Eranapuram" title="Eranapuram" href="lake.html" coords="269,286,71" shape="circle">
    <area target="" alt="Pottanam" title="Pottanam" href="garden.html" coords="797,28,91" shape="circle">
    <area target="" alt="Namakkal" title="Namakkal" href="school.html" coords="569,415,678,485" shape="rect">
</map>
       
       
        
    </center>
</body>
</html>
home.html
<html>

<head>
    <title>My Home Town</title>
</head>

<body bgcolor="green">
    <h1 align="center">
        <font color="blue"><b>Namakkal</b></font>
    </h1>
    <h3 align="center">
        <font color="black"><b>hometown</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            our home town is the mesmerizing place I had seen in my life time.there is history behind it name and it is
            popular in our district.everyone in the village is happy and always active.</font>
    </p>
</body>

</html>
temple.html
<html>

<head>
    <title>Muthugapati</title>
</head>

<body bgcolor="yellow">
    <h1 align="center">
        <font color="purple"><b>Namakkal</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>Muthugapati</b></font>
    </h3>
    <hr size="3" color="pink">
    <p align="justify">
        <font face="Georgia" size="5">
            The most divine place in the world is temple because of their built place,they always built on the place
            where the positive energy is accomplished.In my village temple and god,godess are very important.they always
            instruct us and lead us in good path</font>
    </p>
</body>

</html>
lake.html
<html>
<head>
<title>Eranapuram</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="yellow"><b>Namakkal</b></font>
</h1>
<h3 align="center">
<font color="white"><b>Eranapuram</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The lake in the village is the Gods gift and it is located in Eranapuram .it is act as the key for water scarcity problem and other water requirements.all the nearby villages depend on the water from this village only ,so it is the main source of water in that surrounding</font>
</p>
</body>
</html>
garden.html
<html>
<head>
<title>Pottanam</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Namakkal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Pottanam</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Georgia" size="5">
A Garden is the best place in the house. As it is the only place where a person c. Moreover having a garden in the house welcomes many health benefits. For instance More than 310 tree species have been planted in the 25-acre arboretum, 5,500 spec forest, and a TDEF plant nursery has been created, capable of producing 50,000 ser
indigenous flora of the region.</font>
</p>
</body>
</html>
school.html
<html>

<head>
    <title>Namakkal</title>
</head>

<body bgcolor="orange">
    <h1 align="center">
        <font color="pink"><b>Namakkal</b></font>
    </h1>
    <h3 align="center">
        <font color="lime"><b>Namakkal</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
        <font face="Georgia" size="5">
            I was studied in this school and I gather lot of memories in here .I gather more friends in this
            school.teachers make everything to understand and I always thankful to them for my lifetime</font>
    </p>
</body>

</html>
```


## OUTPUT


![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (26).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
