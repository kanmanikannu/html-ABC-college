# html-ABC-college

One Home page that leads to other pages. The Home page should contain the name of the City as heading along with a logo. There should be a tab with the following links:
 Home;
 Heritage;
 Hotel Booking;
 Gallery.
There should be an appropriate description of the college on the home page.
### PROGRAM
#### INDEX.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img  src="logo1.png" alt="College Logo" height="50">
        
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Welcome to College Name</h2>
            <p>Welcome to our college, where we provide top-notch education and a vibrant campus life. Explore our academic programs, meet our distinguished faculty, and become part of our thriving community.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
#### ACADEMICS.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academics - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="logo1.png" alt="College Logo" height="50" >
        
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Academics</h2>
            <ul>
                <li>Science
                    <ul>
                        <li><a href=""></a>Computer Science</a></li>
                        <li><a href=""></a>Mathematics</a></li>
                    </ul>
                </li>
                <li>Arts
                    <ul>
                        <li><a href=""></a>English</a></li>
                        <li><a href=""></a>Sociology</a></li>
                    </ul>
                </li>
                <li>Commerce
                    <ul>
                        <li><a href=""></a>Economics</a></li>
                        <li><a href=""></a>Business Management</a></li>
                    </ul>
                </li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
#### ADMISSION.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="logo1.png" alt="College Logo" height="50">
        
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Admission Form</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br>

                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br>

                <label for="phone">Phone:</label>
                <input type="tel" id="phone" name="phone" required><br>

                <label for="address">Address:</label>
                <textarea id="address" name="address" required></textarea><br>

                <label for="course">Course Interested:</label>
                <select id="course" name="course" required>
                    <option value="computer-science">Computer Science</option>
                    <option value="mathematics">Mathematics</option>
                    <option value="english">English</option>
                    <option value="sociology">Sociology</option>
                    <option value="economics">Economics</option>
                    <option value="business-management">Business Management</option>
                </select><br>

                <input type="submit" value="Submit">
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
#### GALLERY.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <img src="logo1.png" alt="College Logo" height="50">
        
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Gallery</h2>
            <div>
                <img src="image1.png" alt="Gallery Image 1" height="200" width="300">
                <img src="image2.png" alt="Gallery Image 2" height="200" width="300"><br>
                <img src="image3.png" alt="Gallery Image 3" height="200" width="300">
                <img src="image4.png" alt="Gallery Image 4" height="200" width="300">
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 College Name. All rights reserved.</p>
    </footer>
</body>
</html>
```
### OUTPUT
#### INDEX.HTML
![image](https://github.com/user-attachments/assets/3baeada3-8d9d-47fc-82ad-6241b6f751b2)
#### ACADEMICS.HTML
![image](https://github.com/user-attachments/assets/18c98ee7-80e4-46e9-8b64-1a0ad5925242)
#### ADMISSION.HTML
![image](https://github.com/user-attachments/assets/fba815a0-e282-4a7b-b746-5d92fdd51ad8)
#### GALLERY.HTML
![image](https://github.com/user-attachments/assets/4595bff8-3350-49e8-b870-42deef9377a5)

