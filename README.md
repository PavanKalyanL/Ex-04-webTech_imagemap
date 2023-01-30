# Places Around Me
# Aim:
To develop a website to display details about the places around my house.

# Design Steps:
## Step 1
Create the main html page that contains the image-mapping.


## Step 2
Use the paint softwere to obtain the coordinates of the special area, which is going to redirect to another html page.


## Step 3
Create the other html pages that are going to be linked with the main html page.



# Code:
```
imagemap.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>My Area</title>
</head>
<body>
    
        <div >
        <img src="web map google.png" usemap="#MyArea" height="725" width="1510">
        <map name="MyArea">
        <area shape="rect" coords="900,314,1058,370" href="Divyamedicals.html"  title="Divya">
        <area shape="rect" coords="871,6,1064,84" href="spartanschool.html"  title="spartan School">
        <area shape="rect" coords="8,301,174,371" href="indianoil.html"  title="Indian Oil">
        <area shape="rect" coords="560,68,718,317" href="temple.html"  title="Temple">
        <area shape="rect" coords="923,97,1195,272" href="house.html"  title="Home">
        
        </map>
        </div>
        
</body>
Divyamedicals.html


<!DOCTYPE html>
<html lang="en">
<head>
<title>Divya medicals</title>
</head>
<body>
    <center>
        <h1>Divyamedicals</h1>
        <img src="thumbnail.jpeg">
    </center>
    

</body>
</html>


spartanschool.html


<!DOCTYPE html>
<html lang="en">
<head>
<title>Spartan school</title>
</head>
<body>
    <center>
        <h1>spartan School</h1>
    <img src="spartan.jpeg">
    </center>

</body>
</html>

indianoil.html


<!DOCTYPE html>
<html lang="en">
<head>
<title>Indian oil</title>
</head>
<body>
    <center>
        <h1>Indian oil</h1>
    <img src="petrol.jpg">
    </center>

</body>
</html>


temple.html


<!DOCTYPE html>
<html lang="en">
<head>
<title>Temple</title>
</head>
<body>
    <center>
        <h1>Temple</h1>
    <img src="temple.jpg">
    </center>

</body>
</html>

house.html



<!DOCTYPE html>
<html lang="en">
<head>
<title>House</title>
</head>
<body>
    <center>
        <h1>House</h1>
    <img src="home.jpg">
    </center>

</body>
</html>


```

# Output:
![](Screenshot%20(49).png)
![](Screenshot%20(58).png)
![](Screenshot%20(59).png)
![](Screenshot%20(60).png)
![](Screenshot%20(61).png)
![](Screenshot%20(62).png)
# Result:
Image-Mapping is done successfully


