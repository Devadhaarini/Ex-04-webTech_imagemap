# PLACES AROUND ME
DATE:20-11-2023

# AIM:
To develop a website to display details about the places around my house.

# DESIGN STEPS:
# STEP 1:
Create a Django admin interface.

# STEP 2:
Download your city map from Google.

# STEP 3:
Using tag name the map.

# STEP 4:
Create clickable regions in the image using tag.

# STEP 5:
Write HTML programs for all the regions identified.

# STEP 6:
Execute the programs and publish them.
# Code:
```
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Arakkonam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Devadhaarini D 23006001</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="742,465,896,312" href="home.html" title="My Home Town">
<area shape="rect" coords="1241,250,1418,138" href="place.html" title="Sakkaramanalur">
<area shape="rect" coords="1261,346,1490,439" href="road.html" title="Marudavallipuram">
<area shape="circle" coords="1296,653,87" href="building.html" title="Nagarkuppam">
<area shape="circle" coords="1421,528,84" href="temple.html" title="Murugan temple">
</map>
</center>
</body>
</html>

building.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="blue">
<h1 align="center"> 
<font color="red"><b>Nagarkuppam</b></font>
</h1>
<h3 align="center">
<font color="green"><b>Building</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
</html>
<font face="Georgia" size="5">
    According to Census 2011 information the location code or village code of Nagarikuppam village is 630603.
    Nagarikuppam village is located in Arakonam taluka of Vellore district in Tamil Nadu, India. 
    Vellore and Arakonam are the district & sub-district headquarters of Nagarikuppam village respectively. 
    As per 2009 stats, Nagarikuppam village is also a gram panchayat.
    The total geographical area of village is 482.29 hectares.
    Nagarikuppam has a total population of 807 peoples, out of which male population is 392 while female population is 415. 
    Literacy rate of nagarikuppam village is 58.86% out of which 66.33% males and 51.81% females are literate. 
    There are about 192 houses in nagarikuppam village. Pincode of nagarikuppam village locality is 631151.</font>
</p>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lavender">
<h1 align="center"> 
<font color="black"><b>Arakkonam</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>Home town</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
</html>
<font face="Georgia" size="5">
    Arakkonam is a railway town and suburb of Chennai within Chennai Metropolitan Area limit, 
    in the Indian state of Tamil Nadu, with a population of 78,395 per the census 2011. 
    It is in the newly created Ranipet district, about 54 kilometres (34 mi) from Ranipet headquarters and about 69 kilometres (43 mi) from the state capital of Chennai. 
    In October 2022 Arakkonam is a part of Chennai Metropolitan Area.
    Arakkonam is one of the hottest towns in India, where the temperature can exceed 43 °C (110 °F) for several peak days in summer. 
    The name 'Arakkonam' was derived from the word "Arunthamizhkundram" also later called "Aarukonam", meaning 'hexagon' which connects six important places around.
    The ancient name of the town was "Arumthamizh kundram" ("Arumtamil kunram") which is believed to have been derived 
    from the Tamil words aaru konam meaning "six angles" or hexagon, based on the fact that six important places exist on the town's six sides, 
    namely Kanchipuram, Thakkolam, Manavur, Thiruvalangadu, Thiruttani and Sholinghur.</font>
</p>
</body>
</html>

place.html

<html>
<head>
<title>My City</title>
</head>
<body bgcolor="yellow">
<h1 align="center"> 
<font color="red"><b>Sakkaramanalur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Place</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
</html>
<font face="Georgia" size="5">
Sankaramanalur is a panchayat town in Tirupur district in the Indian state of Tamil Nadu.
As of 2001 India census,[1] Sankaramanallur had a population of 9541.
Males constitute 50% of the population and females 50%.
Sankaramanallur has an average literacy rate of 58%, lower than the national average of 59.5%:
male literacy is 68%, and female literacy is 47%. 
In Sankaramanalur, 11% of the population is under 6 years of age.
</font>
</p>
</body>
</html>

road.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="green">
<h1 align="center"> 
<font color="red"><b>Marudavallipuram</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>road</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
</html>
<font face="Georgia" size="5">
    According to Census 2011 information the location code or village code of Marudavallipuram village is 628929.
    Marudavallipuram village is located in Tiruttani taluka of Thiruvallur district in Tamil Nadu, India. 
    Thiruvallur and Tiruttani are the district & sub-district headquarters of Marudavallipuram village respectively. 
    As per 2009 stats, Tholuthavur is the gram panchayat of Marudavallipuram village.
    The total geographical area of village is 454.08 hectares. Marudavallipuram has a total population of 2,082 peoples, 
    out of which male population is 1,057 while female population is 1,025. 
    Literacy rate of marudavallipuram village is 75.31% out of which 81.55% males and 68.88% females are literate. 
    There are about 519 houses in marudavallipuram village. Pincode of marudavallipuram village locality is 631210.
    Arakonam is nearest town to marudavallipuram for all major economic activities, which is approximately 10km away.
    </font>
</p>
</body>
</html>

temple.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="orange">
<h1 align="center"> 
<font color="pink"><b>Murugan temple</b></font>
</h1>
<h3 align="center">
<font color="green"><b>Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
</html>
<font face="Georgia" size="5">
    The Visit to this Sri Subramaniya Swamy Temple at Pagasalai was a part of Temples Visit in Tiruvallur District, 
    before attending the Uzhavarapani at Janamejaya Eswarar temple at Panambakkam and Palalayam function at Senji Panambakkam Sri Kailasanathar Temple. 
    I was not aware of this Murugan temple before my visit. This is one of the Thirupugazh Paadal Petra Sthalam.
    Some of the salient features of this temple are…The temple is facing east with a 3 tier Rajagopuram. 
    Kodimaram, Balipeedam, Vahana Peacock are in front of maha mandapam entrance. 
    Bas reliefs of Murugan with his vahana peacock and Vinayagar are on both sides of sanctum sanctorum. 
    Moolavar Lord Muruga is in standing posture holding akka mala and Kamandalam  in the upper hands and lower hands are in abhaya varada hastam.</font>
</p>
</body>
</html>
```


# Output:
![Alt text](<../Screenshot 2023-11-22 105041.png>)
![Alt text](<../Screenshot 2023-11-23 084648.png>)
![Alt text](<../Screenshot 2023-11-23 084712.png>)
![Alt text](<../Screenshot 2023-11-23 084818.png>)
![Alt text](<../Screenshot 2023-11-23 084857.png>)
![Alt text](<../Screenshot 2023-11-23 085238.png>)

# Result:
The program implementing image maps using HTML is executed successfully.
