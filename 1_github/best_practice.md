1. create your first repository (on server)
    - create a new repo "test"
    - remember your repository address

2. initialize git locally
    - create a test folder
    ```
    mkdir test
    ```
    - enter the folder
    ```
    cd test
    ```
    - initiate git
    ```
    git init
    ```

2. Adding a file
    - create a README file
    ```
        echo "# test" >> README.md
    ```
    - add readme file to git
    ```
        git add README.md
    ```
    - commit the change
    ```
        git commit -m "add readme file"
    ```
    - name the branch
    ```
        git branch -M main
    ```
3. Connect to github repo
    - add a remote origin (replace "git remote add origin git@github.com:zhqingit/test.git" by your repository address)
    ```
        git remote add origin git@github.com:zhqingit/test.git
    ```

4. Push your code to github
    - git push -u origin main

