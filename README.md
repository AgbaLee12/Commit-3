# 1. Add a README file
echo '# Project Title

A short description of your project.
(Add more details as your project grows!)
' > README.md
git add README.md
git commit -m "Add basic README.md with project description"

# 2. Create a .gitignore file
echo 'node_modules/
.env
logs/
*.log
.DS_Store
' > .gitignore
git add .gitignore
git commit -m "Add .gitignore to exclude common files"

# 3. Update documentation
echo '# Project Title

A short description of your project.

## Setup

1. Clone the repository
2. Run `npm install`
3. Start the project with `npm start`
' > README.md
git add README.md
git commit -m "Update documentation with setup instructions"

# 4. Add a sample config file
echo '{
  "apiKey": "YOUR_API_KEY_HERE",
  "port": 3000
}
' > config.example.json
git add config.example.json
git commit -m "Add example config file"

# 5. Refactor code formatting (sample for index.js)
echo 'function greet(name) {
  console.log(`Hello, ${name}!`);
}

greet("World");
' > index.js
git add index.js
git commit -m "Refactor code: improve formatting in index.js"
