# mondrian-project[index.html](https://github.com/user-attachments/files/22324290/index.html)
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mondrian Project</title>
  <style>
    /* 
    Write your CSS here 
    Gap Colour: #000
    White: #F0F1EC
    Red: #E72F24
    Black: #232629
    Blue: #004592
    Yellow: #F9D01E

    For dimensions, see dimensions.png image.
    HINT: Remember you can't change the properties of grid lines.
    But grid lines are transparent!
    */

    .container{
      display: grid;
      background-color: #000;
      grid-template-columns: 320px 198px 153px 50px;
      grid-template-rows: 414px 130px 155px 20px;
      gap: 9px;
      height: 748px;
      width: 748px;
    }

    .white1{
      background-color: #F0F1EC;
      grid-area: 1 / 2 / 2 / 5;
    }

    .red{
      background-color: #E72F24;
    }

    .black{
      background-color: #232629;
    }

    .blue{
      background-color: #004592;
      border-bottom: 10px solid black;
    }

    .yellow{
      background-color: #F9D01E;
      border-radius: 50%;
    }

    .white2{
      background-color: #F0F1EC;
      grid-area: 2 / 1 / 4 / 2;
    }

    .white3{
      background-color: #F0F1EC;
      grid-area: 2 / 2 / 4 / 4;
    }

    .white4{
      background-color: #F0F1EC;
      grid-area: 3 / 4 / 5 / 5;
    }

    .white5{
      background-color: #F0F1EC;
    }

    .header{
      display: inline-block;
      color: blue;
      font-weight: bold;
    }
  </style>
</head>

<body>
  <!-- Write your HTML here -->
  <h1>Michael's <span class="header">Mondrian</span> Project</h1>
   <div class="container">
    <div class="red"></div>
    <div class="white1"></div>
    <div class="white2"></div>
    <div class="white3"></div>

    <div class="blue"></div>
    <div class="white4"></div>
    
    <div class="white5"></div>
    <div class="yellow"></div>
    <div class="black"></div>

   </div>
</body>

</html>
