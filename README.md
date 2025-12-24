# Ex04 Places Around Me
# Date:
24-11-2025
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
    INDEX.HTML
    {% load static %}
    
    
    <!DOCTYPE html>
    <head>
        <title>Places</title>
    
    </head>
    <body>
    <h1 align="center">Places around my house</h1>
    <img src="{% static 'map.png' %}" usemap="#image-map">
    
    <map name="image-map">
        <area target="_blank" alt="" title="" href="/restaurant/" coords="1333,608,64" shape="circle">
        <area target="_blank" alt="" title="" href="/paradise/" coords="1536,690,63" shape="circle">
        <area target="_blank" alt="" title="" href="/sb/" coords="216,402,72" shape="circle">
        <area target="_blank" alt="" title="" href="/dmart/" coords="748,220,73" shape="circle">
        <area target="_blank" alt="" title="" href="/hospital/" coords="1161,164,80" shape="circle">
    </map>
    
    </body>
    </html>
    
    DMART.HTML
    
    <!DOCTYPE html>
    <html>
        <head>
            <title>
                DMART KATTUPAKKAM
            </title>
        </head>
        <body>
            <h1 align="center">DMART KATTUPAKKAM</h1>
            <p>
                DMart is a well-known retail supermarket located in Kattupakkam, Chennai. 
                It provides a wide range of products including groceries, clothing, household 
                items, and daily essentials at affordable prices.
            </p>
    
            <p><b>KEY INFORMATION</b></p>
            <ul>
                <li>Type: Supermarket</li>
                <li>Address: Kattupakkam, Chennai, Tamil Nadu.</li>
                <li>Products: Groceries, vegetables, clothing, kitchen items.</li>
                <li>Highlights: Budget-friendly shopping and wide product variety.</li>
            </ul>
        </body>
    </html>

    HOSPITAL.HTML

    <!DOCTYPE html>
    <html>
        <head>
            <title>
                DIVINE MERCY WOMEN HOSPITAL
            </title>
        </head>
        <body>
            <h1 align="center">DIVINE MERCY WOMEN HOSPITAL</h1>
            <p>
                Divine Mercy Women Hospital is a healthcare center located in Kattupakkam, Chennai. 
                The hospital specializes in women’s health services including maternity care, 
                gynecology, and general medical consultation.
            </p>
    
            <p><b>KEY INFORMATION</b></p>
            <ul>
                <li>Type: Women’s Hospital</li>
                <li>Address: Kattupakkam, Chennai, Tamil Nadu.</li>
                <li>Services: Maternity care, gynecology, health checkups.</li>
                <li>Highlights: Experienced doctors and patient-friendly care.</li>
            </ul>
        </body>
    </html>



# OUTPUT
# RESULT
The program for implementing image maps using HTML is executed successfully.
