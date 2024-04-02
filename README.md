# gym-page-using-html-css
hello everyone i am creating the gym login and registration page by using html and css 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rao's Fitness centre </title>
    <link rel="stylesheet" href="gymform.css">
</head>
<body>
     <form>
    <div class="head">
        <h1> Rao's Fitness centre </h1>
    </div><hr>
    <div class="main">
         <div class="resgister">
          <h2> Registration </h2>
           </div>
          <div class="gender">
          <input type="radio" name="gender" id="male"/>
          <label for="male"> Male</label>
          <input type="radio" name="gender" id="female"/>
          <label for="male"> Female</label>
          </div>
          </br>
         Name :
         <input type="text" placeholder="enter name " id="name" name="name"/></br>
         Mobile no. :
         <input type="number" placeholder="mobile number" id="mobile" name="mobile"/>
         </br>
         Address :
         <input type="text" placeholder="address" id="address" name="address"/>
         <br>
         Date :
         <input type="date" placeholder="select date" id="date" name="date">
         <br>
         weight:
         <input type="number" placeholderName="" id="name" name="name"/></br>
         Height :
         <input type="number" placeholderName="" id="name" name="name"/></br>
         Select the shift :
         <select name="shift" id="shift">
          <option value="select"> Select </option>
          <option value="morning"> Morning </option>
          <option value="evening"> Evening </option>
          </select>
          <br>
          <button class="button">Submit </button>
         </div>
     </form>  
     <hr>
     <div class="footer">
        <footer>
            Contact us.
            <br>
            Mobile no. +91 9758XXXXXX
             <br>
            gmail.-raosfitnesscentre@gmail.com
            <br>
            website- www.raofitnesscentre.com
        </footer>
     </div>
</body>
</html>


# Css code for this page 
.head :hover{
    color: rgb(247, 94, 11);
    text-shadow: 2px 2px 8px black;
    font-size: 230%;
    text-decoration: underline;
    text-shadow: 2px 2px 10px rgb(237, 228, 228);

}
.head{
    color: aqua;
    text-shadow: 3px 3px 8px red;
    font-size: 220%;
    text-align: center;
    text-decoration: underline;
    margin-left: 250px;
    margin-right: 250px;

}
.main{
    text-align: center;
    line-height: 1.5;
    color: rgb(71, 231, 212);
    font-size: 30px;
    color: aqua;
    background-color: brown;
    background: linear-gradient(to bottom right, rgb(16, 17, 17), rgb(62, 79, 235));
    box-shadow:
      8px 8px 10px 0px deeppink,
      -5px -5px 5px 0px blue,
      5px 5px 15px 0px yellow;
    padding: 0em 1em;
    border-radius: 16px;
    border-style: solid;
    margin-left: 10px;
    font: 24px sans-serif;
    line-height: 2;
    margin-right: 400px;
    margin-left: 400px;
    margin-bottom: 100px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.resgister{
    text-align: center;
    color: bisque;
    text-decoration: underline;
    text-shadow: red;
    margin-top: 1cm;
}
.gender{
    text-align: center;
    color: rgb(237, 237, 47);
    font-family: Arial, Helvetica, sans-serif;
    
}
.gender:hover{
    font-size: 130%;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.button{
    text-align: center;
    color: rgb(213, 213, 224);
    background-color: aqua;
    width: 3.5cm;
    height: 1.2cm;
    font-size: 100%;
    margin-top: 1cm;
    margin-bottom: 2cm;
    border-radius: 50px;
}
.button:hover{
    width: 4cm;
    height: 1.5cm;
    color: rgb(11, 10, 9);
    background-color:darksalmon ;
}
*{
    background-image: url('.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
    backdrop-filter: 10px;
}
#name{
    color: aliceblue;
    background-color: black;
    width: 5cm;
    height: 0.6cm;
    box-shadow: 2px 2px 8px red;
    border-radius: 50px;
    border-color: aqua;
    text-size-adjust: 200%;

}
#address{
    color: aliceblue;
    background-color: black;
    width: 5cm;
    height: 0.6cm;
    box-shadow: 2px 2px 8px red;
    border-radius: 50px;
    border-color: aqua;
    text-size-adjust: 200%;

}
#date{
    color: aliceblue;
    background-color: black;
    width: 5cm;
    height: 0.6cm;
    box-shadow: 2px 2px 8px red;
    border-radius: 50px;
    border-color: aqua;
    text-size-adjust: 200%;
}
#female{
    color: azure;
}
#male{
    color: beige;
}
#shift{
    color: aliceblue;
    background-color: black;
    width: 5cm;
    height: 0.6cm;
    box-shadow: 2px 2px 8px red;
    border-radius: 50px;
    border-color: aqua;
    text-size-adjust: 200%;

}
#mobile{
    color: aliceblue;
    background-color: black;
    width: 5cm;
    height: 0.6cm;
    box-shadow: 2px 2px 8px red;
    border-radius: 50px;
    border-color: aqua;
    text-size-adjust: 200%;

}
.footer{
    text-align: center;
    color: aqua;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
    font-style: italic;
    font-size: large;

}
body{
    background-image: url(background.jpg);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 100% 100%;
    backdrop-filter: 10px;
    background-position: ;
}
