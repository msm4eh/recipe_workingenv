## Recipe to make Working Project Environment
1. create new repository in github (name it something relevant to the project) and choose a license
2. from this repository, create a new codespace.
3. connect to this codespace in VS code and select the correct python interpreter.
4. create and activate a virtual environment using these commands: python3 -m venv venv and source venv/bin/activate
5. create a .gitignore file to keep repository cleaner
6. install any needed extensions in the codespace
7. create a requirements.txt file and add the correct libraries and versions for the project. Then, install the requirements.txt file and any other packages you need via the terminal.
8. create any files (such as .py or .ipynb) or code/folders that your project needs.
9. push changes to github