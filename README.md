# RepoGenie

RepoGenie is a command-line tool designed to streamline the process of creating GitHub repositories. With RepoGenie, you can quickly generate a new repository, complete with a `.gitignore` file and the essential `.git` folder, all in just a few simple steps.

**Link to project:** https://github.com/FinzyPHINZY/RepoGenie

![RepoGenie](image.png)

**Tech Used**

RepoGenie is built using **Node.js**.

## Features

- **Automated Repository Creation**: RepoGenie automates the creation of GitHub repositories, saving you time and effort.
- **Personal Token Authentication**: Utilize your GitHub personal access token for seamless authentication and repository creation.
- **Customizable `.gitignore`**: Choose from a variety of predefined `.gitignore` templates or create your own to tailor your repository setup.
- **Efficient Workflow**: With RepoGenie, you can focus on your code rather than setting up repositories manually.

## Optimizations

This project is not completed. I'm still trying to work around authentication issues based on the Octokit Auth-Basic now deprecated. It works if you create a personal access token and include it in the `.env` file. But my plan is to have users input the token on the command line. Just like they would with the Auth-Basic username and password. So all the activity is on the command line. No need to mess with the code.
I also need to make it available for global integration so users can use:

```javascript
repogenie <repo-name> <longer repo description>
```

## Installation

To install RepoGenie, follow these steps:

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/your-username/repo-genie.git
   ```

2. Navigate to the cloned directory:

   ```
   cd repo-genie
   ```

3. Install the necessary dependencies:

   ```
   npm install
   ```

4. Set up your GitHub personal access token. You can generate a token [here](https://github.com/settings/tokens) with the necessary permissions (repo scope is required).

5. Run RepoGenie and follow the prompts to create your repository:

   ```
   node index.js
   ```

## Contributions

Contributions to RepoGenie are welcome! If you have any suggestions for improvements or new features, feel free to open an issue or submit a pull request on [GitHub](https://github.com/your-username/repo-genie).

## License

This project is licensed under the MIT License.

---

**Disclaimer**: RepoGenie is a project created for convenience and productivity purposes. Use it responsibly and ensure that you have appropriate permissions when creating repositories. We are not responsible for any misuse of this tool.
