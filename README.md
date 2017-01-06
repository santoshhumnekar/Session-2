<!DOCTYPE html>
<html>
<body>
<title>Forms</title>
<form action="http://www.example.com/review.php"method="get">
  
<fieldset>
    <legend>Your Details:</legend>
    <label>Name:<input type="text" name="name" size="30" maxlength="100"></br>
    <label>email:<input type="email" name="email" size="30" maxlength="100"></br>
</fieldset>

<fieldset>
<legend>Your Review</legend>
<p>How did you hear aobut us?
<select> <option value="Google">Google</option></select></br>

<P>Would you visit again?<p>
  <input type="radio" name="gender" value="Yes">Yes
  <input type="radio" name="gender" value="No">No 
  <input type="radio" name="gender" value="Maybe">Maybe </br> 

<label>Comment</br><input type="text" name="Comment:" size="100"></br>

<input type="checkbox" name="checkbox" value="checkbox"> Sign me up for email updates<br>
<button type="button">Submit review!</button>

</fieldset>
</body>
</form>
</html>
