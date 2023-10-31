# Ex04 Places Around Me
# Date:15-10-23
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
# map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"MAP"</title>
    <h1 align="center">
        <font color="blueS" face="cursive">
           ALAGU NACHIYAR 212222240006- MAP 
        </font>
    </h1>
</head>
<body>
    <img src="images/mapss.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="BUS STAND" title="BUS STAND" href="bus.html" coords="517,371,699,425" 
shape="rect">
        <area target="_blank" alt="MAPS" title="MAPS" href="market.html" coords="141,497,337,419" shape="rect">
        <area target="_blank" alt="MY HOME " title="MY HOME" href="home.html" coords="827,309,607,173" shape="rect">
        <area target="_blank" alt="THEATRE" title="THEATRE" href="theatre.html" coords="47,93,245,-1" shape="rect">
        <area target="_blank" alt="TEMPLE" title="TEMPLE" href="temple.html" coords="433,299,204,177" shape="rect">
    </map>
</body>
</html>
```
# bus.html
```
<h1 align="center">
    <font color="blueS" face="cursive">
        BUS STAND
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is a very popular bus satnd in chennai.<br></LI>     
            <LI>its one of chennai's biggest bus stand.<br></LI>
            
        </OL>


    </font>
    <font color ="blue" face = "cursive" size="20" > 
    "MOST POPULAR BUS STAND"
    </font>
```
# home.html
```
<h1 align="center">
    <font color="purple" face="cursive">
        MY HOME
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is where i live.<br></LI>     
            <LI>my home is always the best place .<br></LI>
            <LI>and the view from my house is just spectacular.<br></LI>
            
        </OL>


    </font>
    <font color ="purple" face = "cursive" size="20" > 
    "HOME WILL ALWAYS BE HOME"
    </font>
```
# market.html
```
<!DOCTYPE html>
<html>
<head>
    <title>
        MARKET
    </title>
</head>
<body bgcolor="red">
<h1 align="center">
    <font color="green"face="Road" size="30">
        
    </font>
</h1>
<p align="center">
    <font color="yellow" face="stretch" size="24">
            <LI>this is the area where we get all the needed vegetable,fruits,flowers,etc.
    </font>
</p>
</body>
</html>
```
# theatre.html
```
!DOCTYPE html>
<html>
<head>
    <title>
        THEATRE
    </title>
</head>
<body bgcolor="premium">
<h1 align="center">
    <font color="silver" face="body">
        THEATRE
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>A place where everyone enjoys wacthing a movie.<br></LI> 
        </OL>
    </font>
    <font color ="red" face = "cursive" size="16" > 
    "A theatre always entertains."
    </font>
</p>
</body>
</html>
```
# temple.html
```
<h1 align="center">
    <font color="blueS" face="cursive">
        TEMPLE
    </font>
</h1>
<p align="center">
    <font color="red" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>this is a very auspicious place,where everyone workships god.<br></LI>     
            <LI>Its one of the most famous temples in chennai.<br></LI>
            
        </OL>


    </font>
    <font color ="blue" face = "cursive" size="20" > 
    "Temple Is A Place Of Peace"
    
    
    </font>
```


## OUTPUT
![Screenshot 2023-10-25 194336](https://github.com/Nachiyarr/NearMe/assets/113497340/2a5e548e-f711-451d-ba04-61059b0e3b96)

![o1](https://github.com/Nachiyarr/NearMe/assets/113497340/27a7dace-4d3a-47fd-98e3-3aa13e0acc31)
![06](https://github.com/Nachiyarr/NearMe/assets/113497340/60e7e32f-468d-4e65-b559-5b1af809a88b)
![o4](https://github.com/Nachiyarr/NearMe/assets/113497340/8beb2b23-d756-46e5-84c9-59bb957e6e03)

![02](https://github.com/Nachiyarr/NearMe/assets/113497340/f02d7014-0a25-4cdc-a00c-8713e50ba380)
![05](https://github.com/Nachiyarr/NearMe/assets/113497340/7e4115e8-dd42-4e08-8685-616e0c19788c)
![03](https://github.com/Nachiyarr/NearMe/assets/113497340/6f7beb71-093f-4534-9554-83c73594a994)




## RESULT
The program for implementing image maps using HTML is executed successfully.
