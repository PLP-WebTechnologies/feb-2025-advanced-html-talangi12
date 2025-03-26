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

    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Elements and Form</title>
</head>
<body>

    <header>
        <h1>HTML Elements Demo</h1>
    </header>

    <main>
        <section>
            <h2>Ordered List (Roman Numerals)</h2>
            <ol type="I">
                <li>Item One</li>
                <li>Item Two</li>
                <li>Item Three</li>
                <li>Item Four</li>
                <li>Item Five</li>
            </ol>
        </section>

        <section>
            <h2>External Image</h2>
            <img src="https://images.pexels.com/photos/1103970/pexels-photo-1103970.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Cityscape at night" width="500">
        </section>

        <section>
            <h2>Contact Table</h2>
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
                        <td>Talangi Chalvine</td>
                        <td>567 Kirinyaga</td>
                        <td>0798959954</td>
                        <td>talangichalvine@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Ruth Gacheri</td>
                        <td>456 Kerugoya</td>
                        <td>0700989976</td>
                        <td>ruthgacher@gmail.com</td>
                    </tr>
                    <tr>
                        <td>David Lee</td>
                        <td>789 Pine Ln</td>
                        <td>0789909675</td>
                        <td>david.lee@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Emily Chen</td>
                        <td>101 Elm Rd</td>
                        <td>0700088976</td>
                        <td>emily.chen@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Michael Brown</td>
                        <td>202 Maple Dr</td>
                        <td>0756789670</td>
                        <td>michaelbrown@gmail.com</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section>
            <h2>Registration Form</h2>
            <form action="/register" method="post">
                <fieldset>
                    <legend>User Registration</legend>

                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

                    <label for="password">Password:</label>
                    <input type="password" id="password" name="password" required><br><br>

                    <label for="dob">Date of Birth:</label>
                    <input type="date" id="dob" name="dob"><br><br>

                    <label for="country">Country:</label>
                    <select id="country" name="country">
                        <option value="usa">USA</option>
                        <option value="canada">Canada</option>
                        <option value="uk">UK</option>
                        <option value="kenya">Kenya</option>
                    </select><br><br>

                    <p>Gender:</p>
                    <input type="radio" id="male" name="gender" value="male">
                    <label for="male">Male</label><br>
                    <input type="radio" id="female" name="gender" value="female">
                    <label for="female">Female</label><br>
                    <input type="radio" id="other" name="gender" value="other">
                    <label for="other">Other</label><br><br>

                    <p>Interests:</p>
                    <input type="checkbox" id="sports" name="interests" value="sports">
                    <label for="sports">Sports</label><br>
                    <input type="checkbox" id="music" name="interests" value="music">
                    <label for="music">Music</label><br>
                    <input type="checkbox" id="reading" name="interests" value="reading">
                    <label for="reading">Reading</label><br><br>

                    <input type="submit" value="Register">
                </fieldset>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 HTML Elements Demo</p>
    </footer>

</body>
</html>

Happy Coding! 💻✨
