# About Light Ideas Labs

## Light Ideas Labs coding style guide

This style guide will cover every aspect of our engineering cycle from naming repositories, files, and folders to code layout and best practices to our git workflow.
Style Guide Note
The goal of this style guide is to provide consistency all across our projects. Consistency will improve the quality of code we write, increase readability and make it easy for us to onboard new developers.
Some of these guides are peculiar to a particular language while others will cut across the entire engineering workflow. A lot of the guide if not all follows industry standards making it easy for new developers joining the team to adapt to these standards.

## Naming Repositories, Folders and Files

- Repositories should be all lowercase, and a repository with a compound word should be separated by a dash i.e light-ideas.
- Folders within a repository also should be all lowercase, a folder with a compound word should be separated by an underscore i.e smart_contracts.
- Files should use camelCase convention i.e citizenSmart

## General Code Layout

- Use 4 spaces i.e 1 tab per indentation level (For typescript/javascript projects with a formatter such as prettier, ensure it is set to 4 spaces rather than 2 spaces).
- Write only one statement per line.
- Write only one declaration per line.
- Ensure each source file is wrapped.
- Functions should use camelCase and should describe exactly what actions they perform i.e function() getUserData and not function() userData.
- Classes, Structs, Interfaces, Events, and Contracts should use PascalCase i.e struct UserData, not struct userData.
- Variables should follow camelCase.
  
## Commenting Code

- Code should be commented to make it more readable and understandable to other developers. Comments should be concise and explain what the code is doing or why it's necessary.
- Use comments to explain any non-obvious or complex code, including any hacks or workarounds.
- Use comments to describe function parameters and return values.
- Use comments to document any assumptions or limitations of the code.
- For more information on commenting code, see <https://www.codingame.com/playgrounds/2487/how-to-write-a-comment-in-code>.
- For a more exhaustive standard guide, check out <https://docs.soliditylang.org/en/v0.8.15/style-guide.html>.
  
## Tools and Frameworks

- Developers should use specific tools and frameworks required for the development process, such as IDEs or version control software.
- For TypeScript and JavaScript projects, we encourage the use of Prettier for style formatting.
- For more information on using specific tools and frameworks, see the relevant documentation or ask other developers for guidance.

## Git WorkFlow

- Always work in a branch named to describe what feature you are implementing and branches should be named similar to repositories i.e trading-fees.
- After working on a feature and updating a branch, create a pull request to merge into the develop branch. Develop branch will merge the changes after testing that the code works correctly.
- Commit messages should always describe what changes were made to a code or what new features were added.
- Use templates or examples for pull requests and commit messages to ensure consistency across the development team.
- Master/Main should only contain WORKING, and PRODUCTION code and can ONLY BE UPDATED by develop branch after all aspects of the new changes have been reviewed properly.
- Bugs should be reported as issues in GitHub and may also be reported in Asana, the corresponding pull request should reference the parent issue or Asana task.