<!DOCTYPE html>
<html lang="en">
    <head>
            <meta charset="UTF-16">
            <meta name="viewport" content="width=device-width, initial-scale=2.0">
            <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <link rel="stylesheet" href="usernameinput.css">
        <style type="text/css" media="screen">
        </style>
       <script type="text/javascript" src="usernameinput.js" ></script>
    </head>
    <body>
        <div id="myform">
           <br> Enter Your Name - <input type="text" id="firstName" placeholder="Name"> 
            <input type="submit" id="Submit"> </br>
            <br> Enter your Age : <input type="number" id="age" min="16" max="22"></br>
            <br> Enter your D.O.B : <input type="date" id="dob"></br>
            <br>Select Your Gender - <select id="Gender">
                <option tabindex="1" >Male</option>
                <option tabindex="2">Female</option>
            </select> </br>
            <br> What subscription you want - :
            options - <select id="subs">
                       <option>1 Month free trial then 59/- per month for 3 months</option>
                       <option>1 Month free trial then 49/- per month for 6 months</option>
                       <option>1 Month free trial then 39/- per month for 12 months</option>
                      </select> </br>   
            
        </div>    
        <div id="buttons" >
            <button id="store" class="btn" >STORE</button>
            <button id="signin" ><a href="https://google.com">Sign in</a></button>
            <button id="signUp"><a id="signup" href="signup.html">Sign up</a></button>
            <button id="goDown" onclick="document.getElementById('di').scrollIntoView();" >goDown</button> 
            
        </div>
        <div id="di">
            
        </div>
        
    </body>
</html>
