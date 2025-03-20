<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Contact Page with Registration Form</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Main Content -->
    <header>
        <h1>Welcome to Our Contact Page</h1>
    </header>

    
    <section>
        <h2>Important Tasks</h2>
        <ol type="I">
            <li>Task One</li>
            <li>Task Two</li>
            <li>Task Three</li>
            <li>Task Four</li>
        </ol>
    </section>

    
    <section>
        <h2>Our Beautiful Office</h2>
        <img src="https://images.pexels.com/photos/1181263/pexels-photo-1181263.jpeg" alt="Office" width="600">
    </section>

    
    <section>
        <h2>Contacts</h2>
        <table border="1" cellpadding="10" cellspacing="0">
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
                    <td>John Doe</td>
                    <td>123 Main St, Cityville</td>
                    <td>123-456-7890</td>
                    <td>johndoe@gmail.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Elm St, Townburg</td>
                    <td>234-567-8901</td>
                    <td>janesmith@gmail.com</td>
                </tr>
                <tr>
                    <td>Michael Johnson</td>
                    <td>789 Oak St, Villageville</td>
                    <td>345-678-9012</td>
                    <td>michaelj@gmail.com</td>
                </tr>
                <tr>
                    <td>Amy Lee</td>
                    <td>321 Pine St, Citytown</td>
                    <td>456-789-0123</td>
                    <td>amylee@gmail.com</td>
                </tr>
                <tr>
                    <td>David Brown</td>
                    <td>654 Birch St, Metrocity</td>
                    <td>567-890-1234</td>
                    <td>davidbrown@gmail.com</td>
                </tr>
            </tbody>
        </table>
    </section>


    <section>
        <h2>Register Here</h2>
        <form action="#" method="POST" id="registrationForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email address" required><br><br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Create a password" required><br><br>

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

            <label for="gender">Gender:</label>
            <label><input type="radio" name="gender" value="male" required> Male</label>
            <label><input type="radio" name="gender" value="female"> Female</label><br><br>

            <label for="language">Preferred Language:</label>
            <select id="language" name="language" required>
                <option value="english">English</option>
                <option value="Germany">Germany</option>
                <option value="Lugnda">Lugnda</option>
                <option value="spanish">Spanish</option>
                <option value="french">French</option>
            </select><br><br>

            <label for="newsletter">Subscribe to Newsletter:</label>
            <input type="checkbox" id="newsletter" name="newsletter" value="yes"><br><br>

            <button type="submit">Submit</button>
        </form>
    </section>
</body>
</html>
