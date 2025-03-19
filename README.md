# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia Webpage</title>
</head>
<h1>SAJOMA FARMS</h1>
<body>
    <ol type="I">
        <li>Fresh dressed Chicken</li>
        <li>Day Old Broiler</li>
        <li>Old Layers</li>
    </ol>
    <h2>Internal Images</h2>
    <img src="poultry-farm.jpg" alt="Poultry Farm" width="400">
    <br><br>
    <h2>External Images</h2>
    <img src="https://images.pexels.com/photos/1562389/pexels-photo-1562389.jpeg?auto=compress&cs=tinysrgb&w=600" 
                alt="Image of Free Rearing Farm" height="400" width="400">
  <br>
  <br>
   <!-- Table of 5 contacts with; Name, Address, Mobile and Emails --> 

    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Adewale</td>
                <td>123 Victoria Island, Lagos</td>
                <td>+2348012345678</td>
                <td>ade@kmail.com</td>
            </tr>
            <tr>
                <td>Omobola</td>
                <td>45 Lekki Phase 1, Lagos</td>
                <td>+2348023456789</td>
                <td>bola@kmail.com</td>
            </tr>
            <tr>
                <td>Peter</td>
                <td>78 Maitama, Abuja</td>
                <td>+2348034567890</td>
                <td>peter@kmail.com</td>
            </tr>
            <tr>
                <td>Danladi</td>
                <td>12 Apapa, Lagos</td>
                <td>+2348045678901</td>
                <td>danladi@kmail.com</td>
            </tr>
            <tr>
                <td>Efe</td>
                <td>56 GRA, Benin City</td>
                <td>+2348056789012</td>
                <td>efe@kmail.com</td>
            </tr>
        </tbody>
    </table>
    
    <!-- Registration Form -->
    <h3>Registration Form</h3>
    <form>
        <!-- Name Field -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        <br><br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Create a password" minlength="6" required>
        <br><br>

        <!-- Date Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>

        <!-- Dropdown -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="nigeria">Nigeria</option>
            <option value="ghana">Ghana</option>
            <option value="kenya">Kenya</option>
            <option value="south_africa">South Africa</option>
        </select>
        <br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label>
        <br><br>

        <!-- Checkboxes -->
        <label>Hobbies:</label>
        <input type="checkbox" id="reading" name="hobbies" value="reading">
        <label for="reading">Reading</label>
        <input type="checkbox" id="traveling" name="hobbies" value="traveling">
        <label for="traveling">Traveling</label>
        <input type="checkbox" id="sports" name="hobbies" value="sports">
        <label for="sports">Sports</label>
        <br><br>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>
  
   
    
</body>
</html>
















