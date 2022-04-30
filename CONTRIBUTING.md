# Contributing

1. [Fork](https://help.github.com/articles/fork-a-repo/) the techpedia repository - [Click to fork](https://github.com/Yokozuna59/techpedia/fork).

2. Clone the repository to your device:

    ```bash
    git clone https://github.com/<username>/techpedia.git
    ```

3. Change directory to the cloned project:

    ```bash
    cd techpedia
    ```

4. Create your feature branch locally:

    ```bash
    git checkout -b <branch_name>
    ```

    For clarity, name
    your branch `update-xxx` or `fix-xxx`. The `xxx` is a short
    description of the changes you're making. Examples include `update-readme-en-md` or
    `fix-typo-in-contributing-md`.

5. Add your changes to git:
    Add specific file to git using:

    ```bash
    git add path/to/filename.ext
    ```

    Add all unstaged files using:

    ```bash
    git add *
    ```

6. Commit your changes using a descriptive commit message:

    ```bash
    git commit -sm "Brief Description of Commit"
    ```

   ...take note of that **-s**, it's important!

7. Push your commits to your GitHub Fork:

    ```bash
    git push origin <branch_name>
    ```

8. Submit a [pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork).
