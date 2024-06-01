# CONTRIBUTING TO ZDOCS

## Prerequisites

- Text editor of your choice e.g. VSCode
- Basic knowledge on Markdown. Read about [basic formatting and syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
- Git or GitHub Desktop(for users not familiar with git commands).

## Contribution Workflow

Follow these steps to contribute to this project:

1.  **Fork** repository.

2.  **Clone the forked repository** to your computer. First make a new folder called zdocs-help.

    ```bash
    cd zdocs-help
    ```

    ```bash
    git clone https://github.com/your_username/zdocs.git
    ```

    Replace `your_username` with your GitHub username.

3.  **Create a new branch** for the change you wish to make. For example, to add a new branch(use any name,here we use `dvpt_branch`) run:

    ```
    git checkout -b dvpt_branch
    ```

    This command also switches the working branch from `main` to `dvpt_branch`.

4.  **Make changes.**

    - Use this [website](https://products.aspose.app/words/conversion/jpg-to-md) to convert screenshots to markdown files
    - Edit the markdown files in a text editor like VSCode.
    - Preview your work before making a commit using [this extension](https://marketplace.visualstudio.com/items?itemName=searKing.preview-vscode).

5.  **Stage your changes.**

    ```bash
    git add Science.md
    ```

6.  **Commit your changes.** Ensure to include a descriptive commit message.

    ```bash
    git commit -m "adding Science.md"
    ```

7.  **Push your commit** to GitHub:

    ```bash
    git push origin sciencebranch
    ```

8.  **Create a pull request**
    - Open the forked repository in GitHub.
    - Click in "Pull Requests" and then "New Pull Request".
    - Watch [this video](https://youtu.be/jRLGobWwA3Y?si=WRMe1bC_drgrcCIo) which explains how make a pull request.

#### Additional resources

[Learn Markdown Syntax](https://www.markdownguide.org/extended-syntax/)

[Create tables in Markdown](https://www.tablesgenerator.com/markdown_tables#)

[Math Notation in Markdown](https://www.upyesp.org/posts/makrdown-vscode-math-notation/)

[Using commit messages for communication](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/)
