<!DOCTYPE html>
<html>
<head>
  <title></title>
</head>
<body>
  <h1>REGISTER FORM</h1>
  <form>
    <h2>Student detail</h2>
    <label>First name :</label>
    <input type="text" name="fname" placeholder="First name" required><br><br>
    <label>Last name :</label>
    <input type="text" name="iname" placeholder="last name" required><br><br>
    <label>Reg no :</label>
    <input type="text" name="enter" placeholder="Enter the no" required><br><br>
    YEAR :
    <select>
      <option value="1st">1st</option>
      <option value="2nd">2nd</option>
      <option value="3rd">3rd</option>
      <option value="4th">4th</option>
    </select><br><br>
    SEMESTER :
    <select>
      <option value="1st">1st</option>
      <option value="2nd">2nd</option>
      <option value="3rd">3rd</option>
      <option value="4th">4th</option>
    </select><br><br>
     GENDER :<br><br>
    <input type="radio" id="Male" name="gender" value="male">
    <label for="Male">Male</label><br><br>
    <input type="radio" id="Female" name="gender" value="female">
    <label for="Female">Female</label><br><br>
    <input type="radio" id="Other" name="gender" value="other">
    <label for="Other">Other</label><br><br>
    DEPARTMENT :
    <select>
      <option value="IT">IT</option>
      <option value="CSE">CSE</option>
      <option value="EEE">EEE</option>
      <option value="AIDS">AIDS</option>
      <option value="CHEMICAL">CHEMICAL</option>
      <option value="CIVIL">CIVIL</option>
      <option value="BIOTECH">BIOTECH</option>
      <option value="ECE">ECE</option>
      <option value="MECHANICAL">MECHANICAL</option>
      <option value="OTHERS">OTHERS</option>
    </select>
    <select><br><br>
      DEGREE :<br><br>
      <option value="BTECH">BTECH</option>
      <option value="BE">BE</option>
      <option value="OTHERS">OTHERS</option>
    </select><br><br>
    <label>Phone no:</label>
    <input type="tel" name="Enter the no" placeholder="91" pattern=[0-9]{5}-[0-9]{5}><br><br>
    CURRENT ADDRESS :<br><br>
    <label>ADDRESS: </label>
    <input type="text" name="Enter the address" placeholder="Enter the address"><br><br>
    <label>EMAIL :</label>
    <input type="text" name="E-mail" placeholder="E-mail">
    <br>
    <br>
    <input type="Submit">
  </form>
</body>
</html>
