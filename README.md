# Ex04 Places Around Me
## Date: 03-12-2024

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

map.html
```
<html>
<head>
    <title>My City</title>
</head>
<body>

    <h1 align="center">
        <font color="red"><b>Thambikottai</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>Abisheik priyan V (24900599)</b></font>
    </h3>
    <center>
        <img src="mapimage.png" usermap="#MyCity">
        <map name="MyCity">
            <area shape="rect" coords="579,388,617,418" title="My House" href="house.html">
            <area shape="rect" coords="391,99,427,114" title="N.R Public school" href="school.html">
            <area shape="rect" coords="839,275,881,315" title="Cricket ground" href="ground.html">
            <area shape="rect" coords="77,324,120,358" title="Mariyamman Temple" href="temple.html">
            
        </map>
    </center>
</body>
</html>
```

ground.html
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cricket ground</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Cricket ground</h1>
    </header>
    <div class="content">
        <p>Cricket grounds can vary in size depending on their location and level of play, with international stadiums being larger and more elaborate than local or community grounds. Some well-known cricket grounds include Lord’s Cricket Ground in London, Melbourne Cricket Ground in Australia, and tamilnadu, India.</p>
        
    </div>
</body>
</html>

```
house.html
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My House</h1>
    </header>
    <div class="content">
        <p>My house is a cozy and comfortable place where I live with my family. It has a beautiful garden in the front, a spacious living room, and a warm kitchen that fills the air with delightful aromas.</p>
        <p>The bedrooms are painted in soft, calming colors, and the walls are adorned with family photographs and artwork. My favorite spot is the balcony, where I enjoy watching sunsets and sipping tea.</p>
    </div>
</body>
</html>
```

school.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>N.R Public school</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to N.R Public school</h1>
    </header>
    <div class="content">
        <p>It seems like I can’t do more browsing right now. Please try again later. If you need information about a specific school or educational institution, feel free to provide additional details, and I will do my best to help with the resources available!</p>
        
    </div>
</body>
</html>
```
temple.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mariyamman Temple</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Mariyamman Temple</h1>
    </header>
    <div class="content">
        <p>Mariyamman Temple is a Hindu temple dedicated to Mariyamman, a regional goddess widely worshipped in South India, especially in Tamil Nadu, Andhra Pradesh, and Karnataka. Mariyamman is considered a powerful goddess associated with rain, fertility, and the protection against diseases like smallpox, cholera, and other epidemics. The temple is usually built in honor of her, and it is known for its vibrant rituals and festivals.</p>
        
    </div>
</body>
</html>
```





















## OUTPUT
![Screenshot (190)](https://github.com/user-attachments/assets/ee544038-a071-4769-993b-60761277c072)

![alt text](<Screenshot (156).png>)

![alt text](<Screenshot (157).png>)

![alt text](<Screenshot (158).png>)

![alt text](<Screenshot (159).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
