# Ex04 Places Around Me
## Date: 08/10/2025

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
home.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1 align="center">Experiment-04 Athul Krishna A V (25013602)</h1>
    
<img src="Screenshot 2025-10-09 080839.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="" title="" href="saveetha.html" coords="721,352,828,400" shape="rect">
    <area target="" alt="" title="" href="chem.html" coords="1545,515,123" shape="circle">
    <area target="" alt="" title="" href="than.html" coords="468,471,470,615,674,596,635,458" shape="poly">
    <area target="" alt="" title="" href="queen.html" coords="918,235,1016,288" shape="rect">
    <area target="" alt="" title="" href="vels.html" coords="1318,116,1359,155" shape="rect">
</map>


</body>
</html>

saveetha.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="orange">
  <header>
    <h1 align="center">Welcome to Saveetha University</h1>
    <h2>Empowering Students for a Brighter Future</h2>
  </header>
  <img src="saveetha.png" alt="Saveetha University Image" style="width:20%;height:auto;" align="center">
  <section>
    <h2>About Saveetha University</h2>
    <p>Saveetha University is a renowned institution committed to excellence in education, research, and innovation. Located in Chennai, it offers diverse courses in engineering, medicine, management, and more.</p>
  </section>
  
  <section>
    <h2>Courses Offered</h2>
    <ul>
      <li>B.Tech in Artificial Intelligence and Machine Learning</li>
      <li>B.Tech in Computer Science and Engineering</li>
      <li>B.Pharm and Pharm.D</li>
      <li>MBBS and Medical Sciences</li>
      <li>Management and Business Administration</li>
    </ul>
  </section>
  
  <section>
    <h2>Campus Facilities</h2>
    <p>Our campus boasts state-of-the-art labs, a digital library, sports facilities, hostels, and eco-friendly spaces for holistic student development.</p>
  </section>
  
  <footer>
    <p>Contact us: info@saveetha.ac.in | Phone: +91 44 1234 5678</p>
    <p>© 2025 Saveetha University. All rights reserved.</p>
  </footer>
</body>

</html>

than.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="green">
  <header>
    <h1 align="center">Welcome to Thandalam</h1>
    <p>A Beautiful Village in Tamil Nadu</p>
  </header>
  <img src="image.png" alt="Thandalam Image" style="width:20%;height:auto;">
  <section>
    
    <h2>About Thandalam</h2>
    <p>Thandalam is a peaceful village known for its rich cultural heritage, scenic landscapes, and welcoming community, located in the state of Tamil Nadu, India.</p>
  </section>
  
  <section>
    <h2>Local Highlights</h2>
    <ul>
      <li>Temples and Religious Sites</li>
      <li>Lush Agricultural Fields</li>
      <li>Traditional Festivals and Events</li>
      <li>Handicrafts and Local Artisans</li>
      <li>Community Markets and Cuisine</li>
    </ul>
  </section>
  
  <section>
    <h2>Visiting Thandalam</h2>
    <p>Thandalam offers a tranquil escape with opportunities to explore rural life, enjoy traditional food, and experience warm hospitality. Accessible by road from major cities nearby.</p>
  </section>
  
  <footer>
    <p>Contact us: info@thandalamvillage.in | Phone: +91 44 9876 5432</p>
    <p>© 2025 Thandalam Village. All rights reserved.</p>
  </footer>
</body>

</html>

vels.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    
</head>
<body bgcolor="lightblue">
  <header>
    <h1 align="center">Welcome to Vels Cinema Thandalam</h1>
    <p>Your Destination for the Latest Movies and Entertainment</p>
    <img src="vels.png" alt="Vels Cinema Thandalam" style="width:20%;height:auto;">
  </header>
  
  <section>
    <h2>About Vels Cinema</h2>
    <p>Vels Cinema Thandalam offers a state-of-the-art movie experience with comfortable seating, high-quality sound, and the latest releases, making it the favorite entertainment hub for movie lovers in Thandalam and nearby areas.</p>
  </section>
  
  <section>
    <h2>Now Showing</h2>
    <ul>
      <li>Latest Blockbusters in Tamil, English, and Hindi</li>
      <li>Family-Friendly Movies</li>
      <li>Special Weekend Premieres</li>
      <li>Matinee and Evening Shows</li>
    </ul>
  </section>
  
  <section>
    <h2>Facilities</h2>
    <ul>
      <li>Comfortable Recliner Seats</li>
      <li>Dolby Surround Sound</li>
      <li>Online Booking & Mobile Tickets</li>
      <li>Snack Bar with Popcorn and Drinks</li>
      <li>Ample Parking Space</li>
    </ul>
  </section>
  
  <section>
    <h2>Visit Us</h2>
    <p>Located in the heart of Thandalam, Vels Cinema is easily accessible by road and public transport. Open daily for all major releases and movie marathons.</p>
  </section>
  
  <footer>
    <p>Contact us: velscinema@thandalam.in | Phone: +91 44 2345 6789</p>
    <p>© 2025 Vels Cinema Thandalam. All rights reserved.</p>
  </footer>
</body>

</html>

queen.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="red">
  <header>
    <h1 align="center">Welcome to Queensland Theme Park</h1>
    <p>Experience Adventure and Fun for All Ages</p>
  </header>
  <img src="queenland.png" alt="Queensland Theme Park Image" style="width:20%;height:20%;">
  <section>
    <h2>About Queensland Theme Park</h2>
    <p>Queensland Theme Park is a premier destination for thrill-seekers and families alike, offering exhilarating rides, exciting attractions, and memorable entertainment in the heart of Queensland.</p>
  </section>
  
  <section>
    <h2>Featured Attractions</h2>
    <ul>
      <li>Heart-Stopping Roller Coasters</li>
      <li>Thrilling Water Rides</li>
      <li>Family-Friendly Carousels and Play Areas</li>
      <li>Live Shows and Parades</li>
      <li>Diverse Dining and Shopping Options</li>
    </ul>
  </section>
  
  <section>
    <h2>Plan Your Visit</h2>
    <p>Open daily from 10 AM to 8 PM. Tickets available online and at the gate. Parking and shuttle services provided for your convenience.</p>
  </section>
  
  <footer>
    <p>Contact us: info@queenslandthemepark.com | Phone: +61 7 1234 5678</p>
    <p>© 2025 Queensland Theme Park. All rights reserved.</p>
  </footer>
</body>

</html>

chem.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="silver">
  <header>
    <h1 align="center">Welcome to Chembarambakkam Lake</h1>
    <p>Chennai’s Major Water Reservoir and Nature Spot</p>
  </header>
  <img src="chem.png" alt="Chembarambakkam lake" style="width:20%;height:auto;">
  <section>
    <h2>About Chembarambakkam Lake</h2>
    <p>Chembarambakkam Lake is a vast freshwater reservoir located about 25 km from Chennai, serving as one of the city’s primary sources of drinking water and the origin of the Adyar River. Built during the Chola era, this lake is steeped in history and natural beauty.</p>
  </section>
  
  <section>
    <h2>Key Features</h2>
    <ul>
      <li>Capacity: 3645 million cubic feet, covering nearly 15 sq. km</li>
      <li>Provides drinking water to Chennai</li>
      <li>Birthplace of the Adyar River</li>
      <li>Scenic views, ideal for picnics and birdwatching</li>
      <li>Ancient Shiva Temple and Kanni Koil nearby</li>
      <li>Popular among nature lovers and photography enthusiasts</li>
    </ul>
  </section>
  
  <section>
    <h2>Visitor Information</h2>
    <p>Best time to visit is from October to March when the weather is pleasant. The lake can be accessed by road from Chennai and features a viewpoint walkway. Visitors enjoy peaceful surroundings and occasional sightings of migratory birds.</p>
  </section>
  
  <footer>
    <p>Contact: chennaimetrowater@tn.gov.in | Phone: +91 44 2220 0196</p>
    <p>© 2025 Chembarambakkam Lake. All rights reserved.</p>
  </footer>
</body>

</html>
```


## OUTPUT
<img width="1912" height="941" alt="Screenshot 2025-10-09 092332" src="https://github.com/user-attachments/assets/41a185fa-3178-423a-8ffe-6841496a79df" />
<img width="1887" height="971" alt="Screenshot 2025-10-09 092454" src="https://github.com/user-attachments/assets/eb25f0c1-cae2-4ce6-9882-626413c9af59" />

<img width="1884" height="951" alt="Screenshot 2025-10-09 092347" src="https://github.com/user-attachments/assets/928ddec4-0c16-4bcc-9011-b8c7fdb615f9" />

<img width="1893" height="958" alt="Screenshot 2025-10-09 092510" src="https://github.com/user-attachments/assets/e7e149e4-f09e-4440-bebd-5c1c8037927f" />

<img width="1907" height="942" alt="Screenshot 2025-10-09 092525" src="https://github.com/user-attachments/assets/6ea83b70-70f4-4038-bdc1-2025902b9835" />

<img width="1914" height="933" alt="Screenshot 2025-10-09 092423" src="https://github.com/user-attachments/assets/e1e134f0-6064-4b14-9b8b-c0317a0b83ac" />




## RESULT
The program for implementing image maps using HTML is executed successfully.
