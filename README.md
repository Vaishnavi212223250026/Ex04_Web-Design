# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head> 
<title> Images </title>
</head>
<body> 
<h2>
CULTIVATOR:
<br>

<a href = "https://en.wikipedia.org/wiki/Cultivator">
<img src = "D:\vasan\1.jpg" height="250" width="250">
</a>
<br>
<br>
HORTICULTURE CROPS:
<br>
<a href = "http://www.agritech.tnau.ac.in/horticulture/horti_index.html">
<img src = "D:\vasan\6.jpg" height = "250" width="250">
</a>
<br> 
<br>
LIQUID FERTILIZERS:
<br>
<a href="https://www.liqui-grow.com/types-of-fertilizers/#:~:text=Liquid%20Fertilizers%20can%20be%20foliar,as%20a%20mid%2Dseason%20sidedress.">
<img src = "D:\vasan\7.jpg"height="250" width="250">
</a>
<br>
<br>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2024-04-25 230544.png>) 
![alt text](<Screenshot 2024-04-25 230446.png>) 
![alt text](<Screenshot 2024-04-25 230459.png>) 
![alt text](<Screenshot 2024-04-25 230509.png>) 
![alt text](<Screenshot 2024-04-25 230519.png>)


## RESULT
 Images as hyperlinks is implemented successfully.
