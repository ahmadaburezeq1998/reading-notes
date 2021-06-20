# css 
#### css stands cascading sheet with it we can decor our website by changing the colors of anything changing the text attributes like size color font family and many more as well as alligning the webpage content in an appropriate position that would allow thee user to get the best experience posissible as well as attractiong the user to keep on using the webpage and returning to it in the future 

### css is applicable in three forms 
1. inline 
2. internal 
3. external

### Inline css 
#### its called inline because we write it inside the ellement's tag like the following example 


#### we will change the color of the text inside this paragraph : 
    "<p style="color:red;">this paragraph text color will be red <p/>"


### internal css 
####  we use it when we want to style a specific single html page so in the head of the html we write the style tag and inside of it is the attributes like the following example 

#### <!DOCTYPE html>
    <html>
    <head>
    <style>
    body {background-color:powderblue;}
    h1   {color: pink;}
    p    {color: yellow;}
    </style>
    </head>
    <body>``

### External css 
#### its the most used from of css in the industry since its the most efficient way to keep your code cleas readable and  editable so you can modify it in an efficient way easily and fast without the confusions and the bluriness with all the unordered codes 

#### we create a css file and then go back to our html web page and link it to it  so that we can use all the rules in the external  css file in our html page as well as br=eing able to reuse the same css file as many times as you want with different html pages so it would take way much less coding work and time
#### here is an example 
1. first you create a new file with the extention .css
2. go to your html page head and type 
         <link rel="stylesheet" href="styles.css">

### an example to an external css file 
    body {color:red;
    font-size:30px}

### colors in css 
#### there is three tyypes we can use 
1. rgba(0-255,0-255,0-255,0-1.0) which stands for red green blue and alpha 
2. hex #2398df each color has its own id 
3. hsla(0-360,100%,100%,0-1.0) which is the most dynamic and customizable way of choosing the right color for you the first section is for chosing a color degree since everycolor has a degree and the second one is for the saturation amount of the color then the luminance of the image and finally the alpha channel for transparency an example :     `  {color: hsla(89, 43%, 51%, 0.6);}`