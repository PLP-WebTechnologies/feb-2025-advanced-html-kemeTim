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
    <title>Kemetech Logistics Hub - Registration</title>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to Kemetech Logistics Hub</h1>
        <p>Your trusted partner in logistics and supply chain solutions.</p>
    </header>
    
    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Our Core Services</h2>
        <ol type="I">
            <li>Just-in-Time Delivery</li>
            <li>Geographic Information Systems (GIS) in Logistics</li>
            <li>Advanced Logistics Technology</li>
        </ol>
    </section>
    
    <!-- External Image -->
    <section>
        <h2>Efficient Logistics Solutions</h2>
        <img src="https://images.pexels.com/photos/262353/pexels-photo-262353.jpeg" alt="Logistics Truck" width="600">
    </section>
    
    <!-- Contacts Table -->
    <section>
        <h2>Our Key Contacts</h2>
        <table border="1" cellpadding="5" cellspacing="0">
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>Oluwaseun Adeyemi</td>
                <td>Lagos, Nigeria</td>
                <td>+234 802 345 6789</td>
                <td>seun.adeyemi@example.com</td>
            </tr>
            <tr>
                <td>Chinaza Okeke</td>
                <td>Abuja, Nigeria</td>
                <td>+234 803 456 7890</td>
                <td>chinaza.okeke@example.com</td>
            </tr>
            <tr>
                <td>Emeka Eze</td>
                <td>Enugu, Nigeria</td>
                <td>+234 704 567 8901</td>
                <td>emeka.eze@example.com</td>
            </tr>
            <tr>
                <td>Fatima Bello</td>
                <td>Kano, Nigeria</td>
                <td>+234 705 678 9012</td>
                <td>fatima.bello@example.com</td>
            </tr>
            <tr>
                <td>David Ogundipe</td>
                <td>Ibadan, Nigeria</td>
                <td>+234 806 789 0123</td>
                <td>david.ogundipe@example.com</td>
            </tr>
        </table>
    </section>
    
    <!-- Registration Form -->
    <section>
        <h2>Register with Us</h2>
        <form action="#" method="post">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter a strong password" required minlength="6"><br><br>
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>
            
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="Male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="Female">
            <label for="female">Female</label><br><br>
            
            <label for="service">Preferred Service:</label>
            <select id="service" name="service" required>
                <option value="">Select a service</option>
                <option value="jit">Just-in-Time Delivery</option>
                <option value="gis">GIS in Logistics</option>
                <option value="tech">Advanced Logistics Technology</option>
            </select><br><br>
            
            <label>Interests:</label>
            <input type="checkbox" id="supply" name="interests" value="Supply Chain">
            <label for="supply">Supply Chain</label>
            <input type="checkbox" id="transport" name="interests" value="Transport">
            <label for="transport">Transport</label>
            <input type="checkbox" id="automation" name="interests" value="Automation">
            <label for="automation">Automation</label><br><br>
            
            <input type="submit" value="Register">
        </form>
    </section>
    
    <!-- Multimedia Elements -->
    <section>
        <h2>Explore Logistics Innovations</h2>
        <audio controls>
            <source src="audio-sample.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        <br>
        <video width="600" controls>
            <source src="video-sample.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>
    
    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Kemetech Logistics Hub. All rights reserved.</p>
        <p>Contact us at: <a href="mailto:info@kemetechlogistics.com">info@kemetechlogistics.com</a></p>
    </footer>
</body>
</html>

