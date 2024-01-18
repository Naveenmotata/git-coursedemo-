# Git Demo Project

Welcome to the Git Demo Project! This project is designed to help you get familiar with basic Git commands and workflows. Let's walk through the steps to run the demo on your local machine.

## Getting Started


```

Replace `your-username` with your actual GitHub username.

### Run the Demo

Explore and run the provided Git commands in the terminal to understand fundamental Git workflows.

```bash
# Initialize a new Git repository
git init

# Create a new file
echo "Hello, Git!" > hello.txt

# Stage the changes
git add hello.txt

# Commit the changes
git commit -m "Initial commit"

# Create a new repository on GitHub

# Add the GitHub repository as a remote
git remote add origin https://github.com/your-username/git-demo.git

# Push changes to GitHub
git push -u origin master

# Create a new branch
git checkout -b feature-branch

# Make changes in the new branch
echo "Feature in progress" > feature.txt

# Commit changes in the new branch
git add feature.txt
git commit -m "Add feature"

# Push the new branch to GitHub
git push origin feature-branch
```

### Create a Pull Request

- Go to your repository on GitHub.
- Switch to the `feature-branch`.
- Click on "New Pull Request" to create a pull request.

## Contributing

Feel free to experiment with Git commands and workflows. If you encounter any issues or have suggestions for improvement, create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Happy coding! 🚀
