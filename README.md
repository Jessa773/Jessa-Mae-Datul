<!DOCTYPE html>
<html>
<body>

    <h1>Professional Networking Platform</h1>
    <h2> Create Profile </h2>
<form>
        <label for="lastname">Last Name:</label>
        <input type="text" id="lastName" name="lastname" required><br>
   
        <label for="fname">First Name:</label>
        <input type="text" id="firstName" name="firstname" required><br>
    
        <label for="mname">Middle Name:</label>
        <input type="text" id="middleName" name="middlename" required><br>
    
    <div class = "form_group">
        <label for = "Suffix">Suffix:</label>
        <select suffix="" id="Suffix">
            <option value = "None">None</option>
            <option value = "Jr.">Jr.</option>
            <option value = "I">I</option>
            <option value = "II">II</option>
            <option value = "III">III</option>
            <option value = "IV">IV</option>
            <option value = "V">V</option>
            <option value = "VI">VI</option>
            <option value = "VII">VII</option>
            <option value = "VIII">VIII</option>
            <option value = "IX">IX</option>
            <option value = "X">X</option>
            <option value = "XI">XI</option>
            <option value = "XII">XII</option>
            <option value = "XIII">XIII</option>
            <option value = "XIV">XIV</option>
            <option value = "XV">XV</option>
            <option value = "XVI">XVI</option>
        </select>
    </div>
    <h2>Profile Photo</h2>
    <p>Please upload a recent profile photo (JPG, PNG, or JPEG format only):</p>
    <input type ="submit" value="Choose File">
    <label for="text">No file chosen</label> 

    <h2>Personal Statement</h2>
    <p>Please provide a brief personal statement about yourself(up to 250 words):</p>
    <textarea id="personal_statement" name="personal_statement" rows="5" cols="40" maxlength="250" placeholder="Write your personal statment here..." required></textarea>
    <p>Word Limit: 250 words (Maximum: 1000 characters)</p><br>

    <p>Gender:</p>
    <input type="radio" id="M" value="Male">
    <label for="M">Male</label>
    <input type="radio" id="F" value="Female">
    <label for="F">Female</label><br>
</select>
    <div class="form_group">
        <label for="csname">Civil status:</label>
        <select id="csname" name="csname">
            <option value="Single">Single</option>
            <option value="married">Married</option>
            <option value="widowed">Widowed</option>
            <option value="Sepparated">Sepparated</option>
        </select>
    </div>
    <div class="form_group"><br>
        <label for="religion">Religion</label>
        <select id="religion" name="religion">
            <option value="christianity">Christianity</option>
            <option value="islam">Islam</option>
            <option value="Hinduism">Hinduism</option>
            <option value="buddhism">Buddhism</option>
            <option value="sikhism">Sikhism</option>
            <option value="Judaism">Judaism</option>
            <option value="bahai">Bahai</option>
            <option value="jainism">Jainism</option>
            <option value="None">None(Atheist)</option>
        </select><br><br>
    </div>
    <h2>Summary of Work Experience (Start from most recent)</h2>
    <table border="1" frame="box">
    <tr>
    <th> Designation/Appointment</th>
    <th>Company/Institutions</th>
    <th>Location</th>
    </tr>
    <tr>
    <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
     <tr>
    <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
     <tr>
    <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
     <tr>
    <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
     <tr>
    <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
    </table><br>
    
    <h2>Educational Background (Start form most recent)</h2>
      <table border="1" frame="box">
      <tr>
      <th>Degree</th>
    <th>Specializations</th>
    <th>School</th>
    <th>Year Graduated</th>
    </tr>
    <tr>
     <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
    <tr>
     <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
     <tr>
     <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
     <tr>
     <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
     <tr>
     <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
    </table><br>
    
    <h2>Certification Acquired</h2>
    <table border="1" frame="box">
    <tr>
    <th>Certification Name</th>
    <th>Issuing Organization</th>
    <th>Year Acquired</th>
    </tr>
     <tr>
     <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
     <tr>
     <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
     <tr>
     <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
     <tr>
     <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
     <tr>
     <td><input type= "" id="" name=""></td><td><input type="" name=""></td><td><input type="" id="" name=""></td><td><input="YYYY-YYYY" id="YYYY-YYYY" name="YYYY-YYYY" value="YYYY-YYYY"></td>
    </tr>
    </table><br>
    
    <h2>General Skills (Rate Yourself)</h2>
    <p>Please rate yourself on the following general skills (1:Novice, 2:Basic, 3:Intermediate, 4:Advance, 5:Expert):<p>
    <table border="1" frame="box">
    <tr>
    <th>Skills</th>
    <th>Rating(1-5)</th>
    </tr>
    <tr>
    <td>Communication</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Problem Solving</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Teamwork</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Adaptibility</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Creativity</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Leadership</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Time Management</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Emotional Intelligence</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Critical Thinking</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Conflict Resolution</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Decision making</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Networking</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Negotiation</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Attention to Deatail</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    <tr>
    <td>Collaboration</td><td><input type="number" mins="1" max="5"></td>
    </tr>
    </table>
    <p>Attachments:<input type="file" id="MyFile" name="Choose File"></p>
    <input type="submit" value="Submit">   
</form>

</body>
</html>
