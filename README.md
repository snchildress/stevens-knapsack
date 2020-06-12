# Steven's Knapsack

Steven's Knapsack is a collection of useful VSCode extension. Its contents are focused on efficient and clean coding with beautiful colors in mind. The highlights include the following:

- Beautiful dark theme
- Python syntax highlighting, linter, and autoformatting
- Golang syntax highlighting, linter, and autoformatting
- CSV syntax highlighting
- Bracker pair highlighting
- Indentation highlighting
- Official GitHub extension
- In-line Git information
- Official Docker extension
- Character position navigation and information

## Publishing

1. Create a Personal Access Token in [Azure DevOps](https://dev.azure.com/snchildress/_usersSettings/tokens) with permission to perform all actions in all organizations
2. Install the package to manage VSCode extensions: `npm install -g vsce`
3. Log into the organization where the extension is published: `vsce login snchildress` and specify the Personal Access Token created in step 1
4. Run `vsce publish`
5. Revoke the Personal Access Token from the DevOps dashboard that was created in step 1
