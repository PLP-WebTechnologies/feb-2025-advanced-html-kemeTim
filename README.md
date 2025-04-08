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
    <title>HTML5 Elements Demo</title>
   
</head>
<body >
    <!-- Header Section -->
    <header >
        <h1>Welcome to the HTML5 Showcase</h1>
        <p>Featuring lists, tables, multimedia, and forms with validation</p>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>My Favorite Activities</h2>
        <ol type="I">
            <li>Playing Saxophone</li>
            <li>Learning Programming</li>
            <li>Reading about Logistics</li>
            <li>Exploring Mechatronics</li>
            <li>Trading Forex</li>
        </ol>
    </section>

    <!-- External Image -->
    <section>
        <h2>Inspirational Image</h2>
        <img src="https://images.pexels.com/photos/3408744/pexels-photo-3408744.jpeg" alt="Nature Inspiration" width="600">
    </section>

    <!-- Contact Table -->
    <section>
        <h2>Contact List</h2>
        <table border="1" cellpadding="8" cellspacing="0">
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
                    <td>Jane Doe</td>
                    <td>12 abuja Street</td>
                    <td>+234095678456</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>John Smith</td>
                    <td>45 bassey umoh Avenue</td>
                    <td>+23477654321</td>
                    <td>john@example.com</td>
                </tr>
                <tr>
                    <td>Mary Lee</td>
                    <td>78 uyo Lane</td>
                    <td>+23492334455</td>
                    <td>mary@example.com</td>
                </tr>
                <tr>
                    <td>David Kim</td>
                    <td>32 Barracks Road</td>
                    <td>+23977889900</td>
                    <td>david@example.com</td>
                </tr>
                <tr>
                    <td>Ana Silva</td>
                    <td>65 Elima Street</td>
                    <td>+23988776655</td>
                    <td>ana@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Register Here</h2>
        <form action="#" method="post">
            <!-- Name Field -->
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

            <!-- Email Field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email address" required><br><br>

            <!-- Password Field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Create a password" minlength="6" required><br><br>

            <!-- Date of Birth -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

            <!-- Dropdown -->
            <label for="course">Select a Course:</label>

            <select id="course" name="course" required>
                <option value="">--Choose an option--</option>
                <option value="logistics">Logistics</option>
                <option value="mechatronics">Mechatronics</option>
                <option value="programming">Programming</option>
            </select><br><br>

            <!-- Radio Buttons -->
            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br><br>

            <!-- Checkboxes -->
            <label>Interests:</label><br>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label><br>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label><br>
            <input type="checkbox" id="trading" name="interests" value="trading">
            <label for="trading">Trading</label><br><br>

            <!-- Submit Button -->
            <input type="submit" value="Register">

        </form>
    </section>
    <!-- Multimedia Section -->
    <section>
        <h2>Listen and Watch</h2>

        <!-- Audio -->
        <h3>Relaxing Saxophone Music</h3>
        <audio controls>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>

        <!-- Video -->
        <h3>Motivational Video</h3>
        <video width="600" controls>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 HTML5 Demo by KT Programmer</p>
    </footer>
</body>
</html>



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

