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
  <title>Contact List and Registration</title>
</head>
<body>
  <!-- Ordered list with Roman numerals -->
  <section>
    <h2>Steps to Follow</h2>
    <ol type="I">
      <li>Register an account</li>
      <li>Verify email</li>
      <li>Login to dashboard</li>
      <li>Complete profile</li>
      <li>Enjoy the services</li>
    </ol>
  </section>

  <!-- External image from Pexels -->
  <section>
    <h2>Sample Image</h2>
    <img src="https://images.pexels.com/photos/414171/pexels-photo-414171.jpeg" alt="Sample from Pexels">
  </section>

  <!-- Table of 5 contacts -->
  <section>
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
          <td>John Doe</td>
          <td>123 Main St, Springfield</td>
          <td>555-1234</td>
          <td>john.doe@example.com</td>
        </tr>
        <tr>
          <td>Jane Smith</td>
          <td>456 Elm St, Metropolis</td>
          <td>555-5678</td>
          <td>jane.smith@example.com</td>
        </tr>
        <tr>
          <td>Bob Johnson</td>
          <td>789 Oak St, Gotham</td>
          <td>555-9012</td>
          <td>bob.johnson@example.com</td>
        </tr>
        <tr>
          <td>Alice Brown</td>
          <td>321 Pine St, Star City</td>
          <td>555-3456</td>
          <td>alice.brown@example.com</td>
        </tr>
        <tr>
          <td>Charlie Davis</td>
          <td>654 Cedar St, Central City</td>
          <td>555-7890</td>
          <td>charlie.davis@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Registration form -->
  <section>
    <h2>Registration Form</h2>
    <form action="#" method="post">
      <!-- Personal Information -->
      <fieldset>
        <legend>Personal Information</legend>

        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Full Name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="you@example.com" required>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="At least 8 characters" required minlength="8">

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
      </fieldset>

      <!-- Preferences -->
      <fieldset>
        <legend>Preferences</legend>

        <label for="country">Country:</label>
        <select id="country" name="country" required>
          <option value="">Select your country</option>
          <option value="usa">USA</option>
          <option value="canada">Canada</option>
          <option value="uk">United Kingdom</option>
          <option value="australia">Australia</option>
        </select>

        <p>Gender:</p>
        <label><input type="radio" name="gender" value="male" required> Male</label>
        <label><input type="radio" name="gender" value="female"> Female</label>
        <label><input type="radio" name="gender" value="other"> Other</label>

        <p>Interests:</p>
        <label><input type="checkbox" name="interests" value="coding"> Coding</label>
        <label><input type="checkbox" name="interests" value="music"> Music</label>
        <label><input type="checkbox" name="interests" value="sports"> Sports</label>
      </fieldset>

      <button type="submit">Register</button>
    </form>
  </section>
</body>
</html>


