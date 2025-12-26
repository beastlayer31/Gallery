
# Date:13-12-2025
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
    <title>Image Gallery</title>
</head>

<body>

    <h2 id="title">Picture Gallery</h2>

    <div id="gallery">
        <img src="img1.jpg" width="300" onclick="opening(this.src)">
        <img src="img2.jpg" width="300" onclick="opening(this.src)">
        <img src="img3.jpg" width="300" onclick="opening(this.src)">
    </div>

    <div id="preview" style="display:none;">
        <button onclick="closeimg()">X</button><br><br>
        <img id="bigimg" width="400">
    </div>

    <script>
        function opening(src) {
            document.getElementById("title").style.display = "none";
            document.getElementById("gallery").style.display = "none";
            document.getElementById("preview").style.display = "block";
            document.getElementById("bigimg").src = src;
        }

        function closeimg() {
            document.getElementById("preview").style.display = "none";
            document.getElementById("title").style.display = "block";
            document.getElementById("gallery").style.display = "block";
        }
    </script>

</body>
</html>
```
# OUTPUT:
<img width="1241" height="641" alt="image" src="https://github.com/user-attachments/assets/d5dc95b1-1cb9-49b4-a50e-9b278a4c894d" />
<img width="921" height="677" alt="image" src="https://github.com/user-attachments/assets/3e994445-7b78-45c7-b73d-01177b584b22" />
<img width="777" height="464" alt="image" src="https://github.com/user-attachments/assets/f659c942-5592-4e33-a378-048d782556d0" />


# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
