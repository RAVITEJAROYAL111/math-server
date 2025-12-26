# Ex.05 Design a Website for Server Side Processing
# Date:
# AIM:
To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side.

# FORMULA:
P = I2R
P --> Power (in watts)
 I --> Intensity
 R --> Resistance

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Create python programs for views and urls to perform server side processing.

## Step 5:
Create a HTML file to implement form based input and output.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
``
math.html
<html>
<head>
    <title>Mileage Calculator</title>
    <style>
        body 
        {
            background: grey;
       
        }
        .id1 
        {
            text-align: center;
            color: blue;
        }
        .box 
        {
            text-align: center;
            width: 40%;
            background-color: red;
            border: solid 6px black;
            padding: 25px;
            margin: 60px auto;
            position:fixed;
            top:80px;
            left:350px;
        }
        .result 
        {
            margin-top: 20px;
            font-weight: bold;
        }
    </style>
</head>
<body>
 
    <div class="box">
        <h1 ><u>The Mileage Calculator</u></h1>
        <h3>SIVA R(25007668)</h3>

        <form method="post">
            {% csrf_token %}
            <label>Distance Travelled (km)</label><br>
            <input type="number" name="distance"><br><br>

            <label>Liters Consumed (L)</label><br>
            <input type="number" name="liters"><br><br>

            <button type="submit">Calculate</button>
        </form>

        <div class="result">
            
                Mileage: {{ mileage }} km/L
            
        </div>
    </div>
    
</body>
</html>
`````
# SERVER SIDE PROCESSING:
<img width="780" height="548" alt="Screenshot 2025-12-25 204408" src="https://github.com/user-attachments/assets/89212839-1822-493f-aae0-bca997712273" />

# HOMEPAGE:
<img width="910" height="606" alt="Screenshot 2025-12-25 204442" src="https://github.com/user-attachments/assets/100fd3f1-08af-4a0d-9ab2-0882ec3a8c27" />

# RESULT:
The program for performing server side processing is completed successfully.
