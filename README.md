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
