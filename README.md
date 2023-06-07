# AIM:
To design a website to perform mathematical calculations in server side.

# DESIGN STEPS:
# Step 1:
Create a new django project and app.

# Step 2:
Make on changes in settings and create templates folder.

# Step 3:
Create a code for fronted of calculation using html and css and save it in templates.

# Step 4:
Give an url mapping an give a python code for calculating in views.

# Step 5:
Take a screenshot of the site and uploat it.

# Step 6:
Publish the website in the given URL.

## PROGRAM :

html
```
math.html
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of Rectangle</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body 
{
background-color:red;
}
.edge {
width: 1440px;
margin-left: auto;
margin-right: auto;
padding-top: 250px;
padding-left: 300px;
}
.box {
display:block;
border: Thick dashed lime;
width: 500px;
min-height: 300px;
font-size: 20px;
background-color:blue;
}
.formelt{
color:orange;
text-align: center;
margin-top: 7px;
margin-bottom: 6px;
}
h1
{
color:rgb(255, 0, 179);
text-align: center;
padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
<div class="box">
<h1>Area of a Rectangle</h1>
<form method="POST">
{% csrf_token %}
<div class="formelt">
Length : <input type="text" name="length" value="{{l}}"></input>(in m)<br/>
</div>
<div class="formelt">
Breadth : <input type="text" name="breadth" value="{{b}}"></input>(in m)<br/>
</div>
<div class="formelt">
<input type="submit" value="Calculate"></input><br/>
</div>
<div class="formelt">
Area : <input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/>
</div>
</form>
</div>
</div>
</body>
</html>
```

## OUTPUT:
![WhatsApp Image 2023-06-07 at 21 23 18](https://github.com/vijayarajv1704/mathserver/assets/121303741/224f6947-0ddc-435d-a3e3-ef8cab268d17)

### Home Page:
![WhatsApp Image 2023-06-07 at 21 23 38](https://github.com/vijayarajv1704/mathserver/assets/121303741/b1b0b65b-9b94-42bf-aa85-075823044f9e)


## Result:
The program to design a website to perform mathematical calculations in server side has been successfully created.
