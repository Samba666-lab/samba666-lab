<!DOCTYPE html>
<html>
<head>
<title>Register Form</title>
<style>
body{background-color:pink;}

h1{color:red ; 
      background-color:green
      ; text-align:center ; 
       padding:5px}
p1{color:white ; 
    font-size:20px ;
    font-weight:600}
ul{color:white ;
     font-size:20px ;
     font-weight:600}
p2{color:yellow ; 
    font-size:20px ;
    font-weight:600}
</style>
</head>
<body>
<h1><i>REGISTER FORM</i></h1>  
<br>  
<br>  
<form>  
  
<label> Firstname </label>         
<input type="text" name="firstname" size="15"/> <br> <br>  
<label> Middlename: </label>     
<input type="text" name="middlename" size="15"/> <br> <br>  
<label> Lastname: </label>         
<input type="text" name="lastname" size="15"/> <br> <br>  
  
<label>   
<h2><p style="color: red;">Course:</p></h2>
</label>   
<select>  
<option value="Course">Course</option>  
<option value="BCA">BCA</option>  
<option value="BBA">BBA</option>  
<option value="B.Tech">B.Tech</option>  
<option value="MBA">MBA</option>  
<option value="MCA">MCA</option>  
<option value="M.Tech">M.Tech</option>  
</select>  
  
<br>  
<br>  
<label>   
Gender :  
</label><br>  
<input type="radio" name="male"/> Male <br>  
<input type="radio" name="female"/> Female <br>  
<input type="radio" name="other"/> Other  
<br>  
<br>  
  
<label>   
Phone :  
</label>  
<input type="text" name="country code"  value="+91" size="2"/>   
<input type="text" name="phone" size="10"/> <br> <br>  
Address  
<br>  
<textarea cols="80" rows="5" value="address">  
</textarea>  
<br> <br>  
Email:  
<input type="email" id="email" name="email"/> <br>    
<br> <br>  
Password:  
<input type="Password" id="pass" name="pass"> <br>   
<br> <br>  
Re-type password:  
<input type="Password" id="repass" name="repass"> <br> <br>  
<input type="button" value="Submit"/>  
</form>  
</body>  
</html>  
<a href="https://m.facebook.com">Connecter vous</a>
