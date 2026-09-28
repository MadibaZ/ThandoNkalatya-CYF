
# ThandoNkalatya-CYF
Deploying my first webpage for Code Your Future step 6 of given exercises.
This is my first website deployment on GitHub. It has a short description of things I like and beautiful pictures I got from the internet.

<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8">
    <title>CYF AI Thing</title>
    <link rel="stylesheet" href="./style.css">

  </head>
    
  <body>
  <!DOCTYPE html>
<html lang="en">

<head>
  <meta charsets="UTF-8">
  <link rel="stylesheet" href="./style.css">
                                          <meta name="viewport" content="width-device-width, initial-scale=1.0">
  
  <title>
    Animals
  </title>
</head>

<body>
  <section>
   <div class="parent">
      <div class="child">bird</div>
      <div class="child">cat</div>
      <div class="child">dog</div>
      <div class="child">ferret</div>
      <div class="child">fish</div>
      <div class="child">gerbil</div>
   <div class="child">guinea pig</div>
      <div class="child">hamster</div>
      <div class="child">lizard</div>
      <div class="child">mouse</div>
     <div class="child">rabbit</div>
      <div class="child">rat</div>
      <div class="child">snake</div>
      <div class="child">turtle</div>
     <div class="child">alpaca</div>
      <div class="child">cow</div>
     <div class="child">chicken</div>
    <div class="child">donkey</div>
     <div class="child">goat</div>
      <div class="child">hen</div>
      <div class="child">orse</div>
      <div class="child">llama</div>
      <div class="child">mule</div>
      <div class="child">ox</div>
      <div class="child">pig</div>
      <div class="child">rooster</div>
      <div class="child">sheep</div>
    </div>
    
           </section>
  </body>
</html>
    
  </body>
  
</html>

[index.html](https://github.com/user-attachments/files/32713724/index.html)

[style.css](https://github.com/user-attachments/files/32713735/style.css).parent{
  display: grid;
  justify-content: center;
  grid-template-columns: repeat(auto-fit, minmax(90px,1fr));
  gap: 3px;
  max-width: 1200px;
  margin: 0 auto;
  border: 3px blue dotted;
}

.child{
  background-color: orange;
  border: 2px solid #f0f4f8;
  border-radius: 12px;
  padding: 15px 5px;
  text-align: center;
  font-family: New Times Roman;
  box-sizing: border-box;
  font-size: 14px;
  justify-content: center;
}

@media(max-width: 1201px){
  .parent{
    grid-template-columns: repeat(12, 1fr);
    justify-content: center
  }
  .child:nth-child(25){
    grid-column-start: 5;
    justify-content: center
  }
  
  }

@media(max-width:1080px){
  .parent{
    grid-template-columns: repeat(6, 1fr);
    justify-content: center
  }
  .child:nth-child(25){
    grid-column-start: 1;
    justify-content: center
  }
}

@media (max-width: 650px){
  .parent{
    grid-template-columns: repeat(3, 1fr);
    justify-content: center
  }
  .child:nth-child(27 ){
    grid-column-start: 1;
    justify-content: center
  }
}

