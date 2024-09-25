# Code:You Intro Final Repo

## Instructions for Customizing Your Repo and Syncing to GitHub

### 1. **Fork the Repo**
1. Click the **Fork** button in the top right corner of the repository to create your own copy.
3. This will create a forked copy in your own GitHub account.

### 2. **Clone the Repo to Your Computer**
1. On your GitHub page, go to the newly forked repository.
2. Click the green **Code** button and copy the URL (either HTTPS or SSH).
3. Open **Git Bash** or **Terminal** and navigate to where you want to save the project:

   ```bash
   cd ~/Documents/Projects
   ```
4. Clone the repo to your local machine:

   ```bash
   git clone <URL you copied>
   ```

   Replace `<URL you copied>` with the repo URL.

### 3. **Open the Files in Your Code Editor**
1. Navigate to the project folder:

   ```bash
   cd <your-repo-name>
   ```

2. Open the project in **Visual Studio Code** (VS Code):

   ```bash
   code .
   ```

   - Alternatively, open the `index.html` file in **Notepad** (Windows) or **TextEdit** (macOS).

### 4. **Replace the Placeholder Image with Your Own Photo**
1. **Download** or use your own photo and save it in the project’s `img` folder.
   - Make sure the `img` folder exists. If not, create it:
     - In the project folder, create a folder named `img`.
     - Move your image file into this folder.

2. In `index.html`, replace the placeholder image (`https://via.placeholder.com/150`) with your own:
   ```html
   <img src="img/your-photo.jpg" alt="Your Name">
   ```
   - Replace `your-photo.jpg` with the actual filename of your image.

### 5. **Change the Button Color to Green**
1. Open the `styles.css` file in your editor.
2. Find the `.link-btn` class in the CSS file:
   ```css
   .link-btn {
       background-color: #007bff; /* current blue color */
   }
   ```
3. Replace `#007bff` (the blue color) with a green hex code. For example:
   ```css
   background-color: #28a745;
   ```
   - This changes the button to a green shade.

### 6. **Update Your Name and Bio**
1. In `index.html`, locate this section:
   ```html
   <h2>John Doe</h2>
   <p>Hi, I'm John, a passionate software developer...</p>
   ```
2. Replace `John Doe` with your own name and update the bio text to reflect your personal details.

### 7. **Add a Simple JavaScript Alert**
1. Open the `index.html` file and locate the `<body>` tag.
2. Just before the closing `</body>` tag, add the following JavaScript code to display an alert box:
   ```html
   <script>
       alert("Hello world");
   </script>
   ```
3. Save the file and open `index.html` in a browser. You should see a pop-up that says "Hello world".

### 8. **Modify the JavaScript Alert**
1. In the same `<script>` tag, change the alert text to display "Hello World, I'm a Developer":
   ```html
   <script>
       alert("Hello World, I'm a Developer");
   </script>
   ```
2. Save the file and refresh the browser to see the new alert.

### 9. **Sync Your Changes to GitHub**
1. After making the changes, open **Git Bash** or **Terminal**.
2. Make sure you are in the project folder:
   ```bash
   cd ~/Documents/Projects/<your-repo-name>
   ```
3. Check the current status of your changes:
   ```bash
   git status
   ```
4. Add the modified files:
   ```bash
   git add .
   ```
5. Commit the changes with a message:
   ```bash
   git commit -m "Updated bio, image, button color, and added JavaScript alert"
   ```
6. Push the changes to GitHub:
   ```bash
   git push origin main
   ```
   - This will sync your changes to your GitHub repository.

### 10. Turn In Assignment in Google Classroom.
1. Login to Google Classroom 
2. Turn in assignment.