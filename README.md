<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Favourite Car: SUV</title>
</head>
<body>

  <h1>Welcome to My Multimedia Webpage</h1>
  <h2>My Favourite Car: SUV</h2>
  <img src="https://images.pexels.com/photos/104401/pexels-photo-104401.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="SUV Car" height="300" width="200">

  <h2>Listen to this Audio</h2>
  <audio controls>
    <source src="PRACTICE/Audio.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <h2>Watch this Video</h2>
  <video width="400" controls>
    <source src="https://videos.pexels.com/video-files/31543769/13444521_2560_1440_30fps.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <h2>TABLE</h2>
<table border="1">
    <caption>CONTACTS</caption>
    <thead>
        <tr>
            <th>Name</th>
            <th>Adress</th>
            <th>Mobile</th>
            <th>email</th>

        </tr>
    </thead>
    <tbody>
    <tr>
      <td>Maureen</td> 
      <td>kisumu</td> 
      <td>0725461287</td> 
      <td>5maureen@gmai.com</td>  
    </tr>
    <tr>
        <td>Maur</td> 
        <td>Nandi</td> 
        <td>0715791287</td> 
        <td>10maur@gmai.com</td>  
      </tr>
      <tr>
        <td>King</td> 
        <td>Nairobi</td> 
        <td>07178943287</td> 
        <td>King195r@gmai.com</td>  
      </tr>
      <tr>
        <td>vish</td> 
        <td>Nandi</td> 
        <td>07145896487</td> 
        <td>vishi20@gmai.com</td>  
      </tr>
      <tr>
        <td>prine</td> 
        <td>elgeyo</td> 
        <td>074561231287</td> 
        <td>prinez385@gmai.com</td>  
      </tr>

    </tbody>
    <tfoot>
        <tr>
            <th>Name</th>
            <th>Adress</th>
            <th>Mobile</th>
            <th>email</th>

        </tr>
    </tfoot>
    
</table>

  <h2>Registration Form</h2>
  <form>
    <label for="fullname">Full Name:</label>
    <input type="text" id="fullname" name="fullname" required>
    <br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
    <br><br>

    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required minlength="6">
    <br><br>

    <label for="DOB">Date of Birth:</label>
    <input type="date" id="dob" name="dob" required>
    <br><br>
    <label for="languages">Languages</label>
    <input type="checkbox" name="languages" value=" swahili">swahili
    <input type="checkbox" name="languages" value=" English">English
    <input type="checkbox" name="languages" value=" french">French
    <br><br>
    <label for="country">country</label>
    <select name="country" id="country">

        <option>--selection country--</option>
        <option value="south africa">south africa</option>
        <option value="kenya">kenya</option>
        <option value="uganda">uganda</option>
        <option value="Tanzania">Tanzania</option>
        <option value="Rwanda">Rwanda</option>
    </select>
    <br><br>

    <input type="submit" value="Register">
    <button type="reset">cancel</button>
  </form>


  <h2>My Hobbies</h2>
  <ol type="I" start="1">
    <li>Reading</li>
    <li>Swimming</li>
    <li>Coding</li>
    <li>bike_riding</li>

  </ul>

</body>
</html>
