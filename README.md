# GroupProject
🌐 Project: “Team Portfolio Website”

Goal:
Create a simple website that shows each teammate’s name, photo, and short bio — all on one page.

Each teammate adds their own profile card (so everyone gets practice using GitHub).

🧱 Step 1: Create the repository

Go to https://github.com/new

Name it something like:

team-portfolio


✅ Check “Add a README file”

Click Create repository

👥 Step 2: Add teammates

Go to your repo → Settings → Collaborators

Click Add people

Enter each teammate’s GitHub username → click Add

They’ll get an invite link (they must accept)

🧠 Step 3: Open in GitHub Codespaces (no install needed)

Each person:

Go to the repo

Click the green “Code” button → select Codespaces tab

Click “Create codespace on main”

This opens a full browser-based editor (no need for pull/push or setup).

💾 Step 4: Add the website files

Inside your Codespace, create three files:

index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Our Team Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>🌟 Meet Our Team 🌟</h1>

  <div class="team">
    <!-- Example member card -->
    <div class="card">
      <img src="images/timothy.jpg" alt="Timothy">
      <h2>Timothy Kijjambu</h2>
      <p>Java developer, enjoys learning recursion and GitHub!</p>
    </div>

    <!-- Each teammate adds their own card below -->
  </div>
</body>
</html>

style.css
body {
  font-family: Arial, sans-serif;
  text-align: center;
  background: #f4f6f9;
}

.team {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

.card {
  background: white;
  padding: 20px;
  border-radius: 15px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.2);
  width: 200px;
  transition: 0.3s;
}

.card:hover {
  transform: scale(1.05);
}

.card img {
  width: 100%;
  border-radius: 10px;
}

README.md
# 🌐 Team Portfolio Website

A simple website showing our amazing team members.

## How to contribute
1. Open in GitHub Codespaces.
2. Add your photo in `/images`.
3. Add your `<div class="card">` section in `index.html`.
4. Commit and push changes.

## Team Members
- Timothy Kijjambu
- (Add your names here)

🖼 Step 5: Add your photo

In your Codespace, make a folder called images

Upload your picture:
Right-click → Upload…
(Name it something like timothy.jpg)

🧩 Step 6: Add yourself to the page

Each teammate edits index.html, copies a card, and changes the name, image, and bio.
Then commit your changes:

Go to the Source Control icon (on the left)

Type a short message, like Added Timothy’s card

Click Commit & Push

🌎 Step 7: View it live

You can turn it into a live website using GitHub Pages:

Go to your repo → Settings → Pages

Under “Branch,” select main and click Save

After a minute, your site appears at:

https://<your-username>.github.io/team-portfolio/
