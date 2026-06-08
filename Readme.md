Project 1:-

Step 1: Build Your Website Locally
Before dealing with GitHub, you need the actual files for your website.
	1. Create a folder on your computer named something like my-portfolio.
	2. Create your core files inside that folder. At a minimum, you will need:
		○ index.html: The main structure and content of your website (your experience, bio, and contact info).
		○ style.css: The design, fonts, and layout to make it look professional.
	3. Write your HTML structure. Make sure your main file is exactly named index.html (all lowercase), as GitHub looks for this file by default to display your website.

Step 2: Set Up GitHub and Git
To save your code to GitHub, you need a GitHub account and Git installed on your computer.
	1. Create a GitHub Account: Go to GitHub and sign up if you haven't already.
	2. Create a New Repository: * Click the + icon in the top right corner of GitHub and select New repository.
		○ Repository name: Use the format yourusername.github.io (replace yourusername with your actual GitHub username). Note: Naming it exactly this way unlocks GitHub's automatic free hosting.
		○ Set the visibility to Public.
		○ Leave "Initialize this repository with a README" unchecked and click Create repository.

Step 3: Push Your Code to GitHub
Now, you will link your local project folder to your online GitHub repository using your computer's terminal (Mac/Linux) or Command Prompt/Git Bash (Windows).

	1. Open your terminal and navigate to your project folder:
Bash

cd path/to/your/my-portfolio
	2. Initialize Git in your local folder:
Bash

git init
	3. Add all your files to be tracked:
Bash

git add .
	4. Commit the files with a message:
Bash

git commit -m "Initial commit: Added portfolio structure"
	5. Link your local folder to GitHub (replace the URL with the link provided on your GitHub repository page):
Bash

git remote add origin https://github.com/yourusername/yourusername.github.io.git
	6. Rename your main branch to main and push your code:
Bash

git branch -M main
git push -u origin main

Step 4: Make Your Website Live!
If you named your repository yourusername.github.io, your website will automatically go live within a few minutes.
	Check your live site: Open your browser and go to https://yourusername.github.io.
If you used a different repository name:
Don't worry! You can still host it easily:
	1. Go to your repository on GitHub.
	2. Click on Settings (the gear icon at the top).
	3. On the left sidebar, click on Pages.
	4. Under "Build and deployment", set the Source to Deploy from a branch.
	5. Under "Branch", change None to main (or master) and / (root), then click Save.
	6. GitHub will give you a live link at the top of that page after a minute.

