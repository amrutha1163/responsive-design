# responsive-design
<!DOCTYPE html>  
<html>  
<head>  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<style>  
body{  
  font-family: Calibri, Helvetica, sans-serif;  
  background-color:blue;  
}  
.container {  
    padding: 50px;  
  background-color:aqua;  
  border-radius:50px;
}  
  
input[type=text], input[type=password], textarea {  
  width: 100%;  
  padding: 15px;  
  margin: 5px 0 22px 0;  
  display: inline-block;  
  border: none;  
  background: #f1f1f1;  
}  
input[type=text]:focus, input[type=password]:focus {  
  background-color:white;  
  outline: none;  
}  
 div {  
            padding: 10px 0;  
         }  
hr {  
  border: 1px solid #f1f1f1;  
  margin-bottom: 25px;  
}  
.registerbtn {  
  background-color:gold;  
  color: white;  
  padding: 16px 20px;  
  margin: 8px 0;  
  border: none;  
  cursor: pointer;  
  width: 100%;  
  opacity: 0.9;  
}  
.registerbtn:hover {  
  opacity: 1;  
}  
</style>  
</head>  
<body>  
<form>  
  <div class="container">  
  <center>  <h1> <b> STUDENT REGISTRATION FORM </b></h1> </center>  
  <hr>  
<h1><i> Registration of a student for an online TCS exam</i></h1>
  <i><label> Firstname </label>   
<input type="text" name="firstname" placeholder= "Ex:Kolla" size="15" required />   
<label> Middlename: </label>   
<input type="text" name="middlename" placeholder="Ex:Gnana" size="15" required />   
<label> Lastname: </label>    
<input type="text" name="lastname" placeholder="Ex:Prasanna" size="15"required /> 
<label> Roll.no: </label>    
<input type="text" name="roll.no" placeholder="Ex:20NN1A05E3" size="15"required />   
<label> Father name: </label>    
<input type="text" name="father name" placeholder=" Father name" size="15"required />   
<label> Mother name: </label>    
<input type="text" name="mother name" placeholder="Mother name" size="15"required /> 
 < label> Aadhar number: </label>    
<input type="text" name="aadhar number" placeholder="Aadhar number" size="15"required /> 

  
  

<div>  
<label>   
Qualification :  
</label>   
  
<select>  
<option value="Qualification">Qualification</option>  
<option value="BCA">BCA</option>  
<option value="BBA">BBA</option>  
<option value="B.Tech">B.Tech</option>  
<option value="MBA">MBA</option>  
<option value="MCA">MCA</option>  
<option value="M.Tech">M.Tech</option>  
</select>  
</div>  
<div>
<label>
CGPA:
</label>
<input type="text" name="X -CGPA"placeholder="X-CGPA"size="3"/>
<input type="text" name="XII-CGPA"placeholder="XII-CGPA"size="3"/>
</div>
<div>
<label for ="file">resume file to upload</label>
<input type="file" id ="file" name="file" multiple>
</div>
<div>
<button>Submit</button>
</div>
<div>  
<label>   
Gender :  
</label><br>  
<input type="radio" value="Male" name="gender" checked > Male   
<input type="radio" value="Female" name="gender"> Female   
<input type="radio" value="Other" name="gender"> Other  
  
</div>  
<label>   
Phone :  
</label>  
<input type="text" name="country code" placeholder="Country Code"  value="+91" size="2"/>   
<input type="text" name="phone" placeholder="phone no." size="10"/ required>   
Current Address :  
<textarea cols="80" rows="5" placeholder="Current Address" value="address" required>  
</textarea>  
 <label for="email"><b>Email</b></label>  
 <input type="text" placeholder="Enter Email" name="email" required>  
  
    <label for="psw"><b>Password</b></label>  
    <input type="password" placeholder="Enter Password" name="psw" required>  
  
    <label for="psw-repeat"><b>Re-type Password</b></label>  
    <input type="password" placeholder="Retype Password" name="psw-repeat" required>  
    <button type="submit" class="registerbtn">Register</button>    </i>
</form>  
</body>  
</html>
