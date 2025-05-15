# Ex04 Places Around Me
## Date: 14.05.2025

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
Create clickable regions in the image using ```<area>``` tag.![


### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
~~~
map.html
<html>
<head>
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Virudhachalam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>MANISHA.M (24900673)</b></font>
</h3>
<center>
    -<img src="map.png.png" usemap="#image-map">
    <map name="image-map">
            <area target="" alt="virudhachalam" title="virudhachalam" href="viru.html" coords="292,405,473,464" shape="rect">
            <area target="" alt="nachiyarpet" title="nachiyarpet" href="nachi.html" coords="466,577,66" shape="circle">
            <area target="" alt="ponneri" title="ponneri" href="pon.html" coords="899,267,1064,329" shape="rect">
            <area target="" alt="thiruvallurnagar" title="thiruvallurnagar" href="thiru.html" coords="392,318,67" shape="circle">
            <area target="" alt="gopalapuram" title="gopalapuram" href="gopal.html" coords="136,527,1,476" shape="rect">
    </map>
</center>
</body>
</html>

viru.html

<!DOCTYPE html>
<html>
<head>
    <title>Virudhachalam</title>
    <style>
        body { background-color: #ffeaa7; font-family: 'Segoe UI', sans-serif; color: #2d3436; padding: 20px; }
        h1 { color: #d63031; }
    </style>
</head>
<body>
    <h1>Virudhachalam (Vriddhachalam)</h1>
    <p>Virudhachalam is a historic town in Cuddalore district, Tamil Nadu. The town is famous for the **Vriddhagiriswarar Temple**, an ancient Shiva temple attracting pilgrims from all over the state.</p>
    <p>It's located on the banks of the Manimuktha River and is surrounded by agricultural fields, making it a hub for rice and sugarcane production.</p>
    <ul>
        <li>District: Cuddalore</li>
        <li>Famous for: Vriddhagiriswarar Temple, sugar mills</li>
        <li>Languages: Tamil</li>
    </ul>
</body>
</html>

nachi.html

<!DOCTYPE html>
<html>
<head>
    <title>Nachiyarpet</title>
    <style>
        body { background-color: #a29bfe; font-family: 'Georgia', serif; color: #fff; padding: 20px; }
        h1 { color: #ffeaa7; }
    </style>
</head>
<body>
    <h1>Nachiyarpet</h1>
    <p>Nachiyarpet is a quaint and culturally rich area known for its temples and traditional lifestyle. This small locality embodies the serene Tamil Nadu village vibe.</p>
    <p>It is often visited during festival seasons for its traditional celebrations and warm hospitality.</p>
    <ul>
        <li>Main attraction: Local temples and festivals</li>
        <li>Culture: Deep-rooted in Tamil traditions</li>
        <li>Nearby towns: Virudhachalam, Bhuvanagiri</li>
    </ul>
</body>
</html>

gopal.html

<!DOCTYPE html>
<html>
<head>
    <title>Gopalapuram</title>
    <style>
        body { background-color: #fd79a8; font-family: 'Helvetica', sans-serif; color: #fff; padding: 20px; }
        h1 { color: #ffeaa7; }
    </style>
</head>
<body>
    <h1>Gopalapuram</h1>
    <p>Gopalapuram is a prime locality in Chennai city. It is well known for educational institutions like DAV School and proximity to Marina Beach.</p>
    <p>The area is highly urbanized and attracts students, working professionals, and tourists alike.</p>
    <ul>
        <li>Popular spots: Marina Beach, DAV School, Music Academy</li>
        <li>Type: Urban, upscale</li>
        <li>Transport: Easily accessible via metro and road</li>
    </ul>
</body>
</html>

pon.html
<!DOCTYPE html>
<html>
<head>
    <title>Ponneri</title>
    <style>
        body { background-color: #81ecec; font-family: 'Tahoma', sans-serif; color: #2d3436; padding: 20px; }
        h1 { color: #00b894; }
    </style>
</head>
<body>
    <h1>Ponneri</h1>
    <p>Ponneri is a fast-developing town near Chennai, Tamil Nadu. It is known for its industrial development and proximity to the upcoming smart city projects.</p>
    <p>The town is well-connected by rail and road, and serves as a gateway to the northern part of the Chennai metropolitan area.</p>
    <ul>
        <li>District: Thiruvallur</li>
        <li>Key Projects: Smart City Development Plan</li>
        <li>Transport: Ponneri Railway Station, NH16</li>
    </ul>
</body>
</html>

thiru.html

<!DOCTYPE html>
<html>
<head>
    <title>Thiruvallur Nagar</title>
    <style>
        body { background-color: #fab1a0; font-family: 'Verdana', sans-serif; color: #2c3e50; padding: 20px; }
        h1 { color: #6c5ce7; }
    </style>
</head>
<body>
    <h1>Thiruvallur Nagar</h1>
    <p>Thiruvallur Nagar is a peaceful and green residential area. It is well known for its calm atmosphere and friendly community, making it an ideal place for families.</p>
    <p>It also offers access to schools, parks, and shops while remaining less chaotic than the city core.</p>
    <ul>
        <li>Nearby cities: Chennai, Avadi</li>
        <li>Known for: Residential calmness, accessibility</li>
        <li>Best for: Families, students</li>
    </ul>
</body>
</html>
~~~



## OUTPUT
![Screenshot 2025-05-15 193544](https://github.com/user-attachments/assets/1833e8c6-1cf7-4886-9386-a0c7078021b6)
![Screenshot 2025-05-15 193554](https://github.com/user-attachments/assets/ce653f38-ae33-45a4-8eb2-59711f8f8fb3)
![Screenshot 2025-05-15 193604](https://github.com/user-attachments/assets/2bd9431e-6dd5-4dac-85ca-04d3a5779a7d)







## RESULT
The program for implementing image maps using HTML is executed successfully.
