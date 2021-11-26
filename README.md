<!DOCTYPE html>
<html>
<body>

<h2>HTML Forms</h2>

<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" ><br><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value=""><br><br>
  <label for="gender">Gender:</label><br>
  <input type="radio" name="gender" value="male"> Male<br>
  <input type="radio" name="gender" value="female"> Female<br><br>
  <label for="birthday">Birthday:</label><br>
  <input type="date" id="birthday" name="birthday"><br><br>
  <label for="username">Username:</label><br>
  <input type="text" id="username" name="username"><br><br>
  <label for="pwd">Password:</label><br>
  <input type="password" id="pwd" name="pwd"><br><br>
  <label for="pin">PIN:</label><br>
  <input type="number" id="pin" name="pin" maxlength="4" ><br><br>
  <label for="phone">Enter your phone number:</label><br>
  <input type="tel" id="phone" name="phone"  maxlength="10" size="10"><br><br>
  <label for="email">Email:</label><br>
  <input type="email" id="email" name="email" autocomplete="off"><br><br>
</form> 


</body>
</html>


