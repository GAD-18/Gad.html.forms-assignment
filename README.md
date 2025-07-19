# Personal Information Survey Form 📝

![Form Preview](/screenshots/form-preview.png)  
A responsive HTML form collecting personal information with validation

## 🌐 Live Demo
[View Live Form](https://GAD-18.github.io/forms-assignment/GDA.html)  
(GitHub Pages link - enable in repository settings)

## 🛠 Project Details
- *Repository*: [GAD-18/forms-assignment](https://github.com/GAD-18/forms-assignment)
- *Main File*: GDA.html
- *Technologies*: HTML5, CSS3, Form Validation

## 📋 Form Features
```html
<!-- Text Inputs -->
<label for="fname">First Name:</label>
<input type="text" id="fname" name="fname" required>

<label for="lname">Last Name:</label>
<input type="text" id="lname" name="lname" required>

<!-- Password with Length Restriction -->
<label for="password">Password:</label>
<input type="password" id="password" name="password" maxlength="12">
