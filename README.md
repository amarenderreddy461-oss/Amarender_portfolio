# Initialize git
git init

# Rename the file to index.html (required for hosting)
mv amarender_portfolio.html index.html

# Stage and commit
git add .
git commit -m "Initial portfolio commit"

# Connect to your GitHub repo (paste your actual repo URL)
git remote add origin https://github.com/YOUR_USERNAME/amarender-portfolio.git

# Push it
git branch -M main
git push -u origin main
