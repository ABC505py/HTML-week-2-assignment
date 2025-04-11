# HTML-week-2-assignment

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Complete Web Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.6;
        }

        img {
            max-width: 100%;
            height: auto;
            margin-bottom: 30px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 30px;
        }

        table, th, td {
            border: 1px solid #999;
            padding: 10px;
            text-align: left;
        }

        form {
            max-width: 600px;
            padding: 20px;
            border: 1px solid #ccc;
        }

        form label {
            font-weight: bold;
        }

        form input, form select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            margin-bottom: 15px;
        }

        .form-group {
            margin-bottom: 15px;
        }
    </style>
</head>
<body>

    <!-- Heading -->
    <h1>My Web Page</h1>

    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List (Roman Numerals)</h2>
    <ol type="I">
        <li>Learn HTML</li>
        <li>Practice CSS</li>
        <li>Understand JavaScript</li>
        <li>Build Projects</li>
        <li>Deploy Website</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/34950/pexels-photo.jpg" alt="Nature Scene from Pexels">

    <!-- Table of Contacts -->
    <h2>Contact List</h2>
    <table>
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
                <td>John Kamau</td>
                <td>106, Runda Drive</td>
                <td>123-456-789</td>
                <td>jk@example.com</td>
            </tr>
            <tr>
                <td>James Mwangi</td>
                <td>111, Runda Grove</td>
                <td>102-112-131</td>
                <td>jm@example.com</td>
            </tr>
            <tr>
                <td>Pastor Nganga</td>
                <td>888, Safiee Park Karen</td>
                <td>415-161-171</td>
                <td>pn@example.com</td>
            </tr>
            <tr>
                <td>Inside Man</td>
                <td>999, Woodvale Grove</td>
                <td>819-202-122</td>
                <td>im@example.com</td>
            </tr>
            <tr>
                <td>Hakuna Matata</td>
                <td>1724, Forest Hills Drive</td>
                <td>224-252-627</td>
                <td>hm@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <!-- Name Field -->
        <div class="form-group">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        </div>

        <!-- Email Field -->
        <div class="form-group">
            <label for="email">Email Address:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
        </div>

        <!-- Password Field -->
        <div class="form-group">
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Choose a password" minlength="6" required>
        </div>

        <!-- Date Field -->
        <div class="form-group">
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
        </div>

        <!-- Dropdown Field -->
        <div class="form-group">
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select your country</option>
                <option value="us">United States</option>
                <option value="uk">United Kingdom</option>
                <option value="ca">Canada</option>
                <option value="au">Australia</option>
            </select>
        </div>

        <!-- Radio Buttons -->
        <div class="form-group">
            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female" required>
            <label for="female">Female</label><br>
            <input type="radio" id="other" name="gender" value="other" required>
            <label for="other">Other</label>
        </div>

        <!-- Checkboxes -->
        <div class="form-group">
            <label>Interests:</label><br>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label><br>
            <input type="checkbox" id="reading" name="interests" value="reading">
            <label for="reading">Reading</label><br>
            <input type="checkbox" id="traveling" name="interests" value="traveling">
            <label for="traveling">Traveling</label>
        </div>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>

</body>
</html>
