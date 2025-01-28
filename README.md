# sre-project-reishell

In this repository you are going to learn how to apply the best practices for version controls with Git in collaboration groups and also practice for improve your habilities.

## Table of Contents
  - [Getting Started](#getting-started)
  - [Contribution Guidelines](#contribution-guidelines)
  - [Features](#features)
  - [License](#license)


## Getting started:

  ### Prerequisites:
  Ensure that you have the following installed:

  * Git(for version control).
  * Visual Studio Code(or another editor).

  ### Dependences:
  You have to be sure that all necessary dependences are installed. 

## Contribution Guidelines:

Here are the steps to get started:
1. Fork the repository to your GitHub account.
2. Clone the forked repository to your local machine.
4. Create a new feature branch for your changes.
6. Make your changes and commit them with clear and descriptive message.
9. Push the changes to your fork.
11. Create a pull request on the original repository with a description of the changes made.

## Features:

* Permission Control : Define what each role can or cannot do.
  
  ### Fork the Repository:

  * Click the Fork button at the top-right corner of this repository's page.
  * Create a forked copy in your GitHub account.

  ### Clone your Fork in your Machine:

  ```bash
    git clone https://github.com/<your-username>/<your-repo-name>.git
    cd <your-project-name>
  ```
  ### Create a New Branch:
  1.Create and switch to a new branch:

   ```bash
   git checkout -b feature/<your-feature-name>
   ```
  ### Create a Commit:

   ```bash
   git commit -m "Your commit message"
   ```

  ### Push the changes to your fork:

   ```bash
   git push origin feature/<your-feature-name>
   ```

  ### Create an Issue:
  * Go to issues in GitHub and click on new issue.
  * Write the recomendation, problem or improve that you want to make with a title and description.
  * Add labels, person assigned, deadlines if your consider that is necessary.

  ### Create a Pull Request:
  After pushing your changes, create a pull request to merge them into the original repository:
  * Go to Pull Requests in Github.
  * Click on new Pull Request.
  * Write a description of your changes, and it's important that if you are fixing a bug reference the related issue for example(Fixes #145).

## Run the main Script:
Once that you have forked or cloned the repository, you can run a main script, for example:
   ```bash
     python main.py
   ```

## License:

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
