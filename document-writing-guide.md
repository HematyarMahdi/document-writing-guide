# Document Writing Guide

To write a document on your GitHub account you have to follow steps below:
1. Create New Repository:
   
    After you've logged in to your account, create a new repository and name it like "document-writing-guide". Notice, choose the option to initialize a repository 
    with a README file.
2. Clone the Repository:

    - On the GitHub repository page, click on the green "Code" button and copy the repository URL
    - Open Git CMD
    - Navigate to the directory where you want to clone the repository
    - Run the following command to clone the repository:
        ```
            git clone https://github.com/your-username/document-writing-guide.git        
        ```
3. Open the Repository in Visual Studio Code:
    - Click on "File" then "Open Folder" and select the "document-writing-guide" folder
4. Create a MD(markdown) file:
    - In visual studio code click on "New File" and create a file like "document-writing-guide.md"
5. Write the Document:
    - In the "document-writing-guide.md" file, use markdown syntax to write the content of your document
6. Commit and Push Changes:
    - In Git CMD or your command-line interface, navigate to the repository directory.
    - Run the following commands to stage and commit your changes:
        ```
            git add .
            git commit -m "Add basic steps of writing a document"
        ```
    - Push your committed changes to GitHub using the following command:
        ```
            git push origin main
        ```
7. View and Verify the Document on GitHub:
    - Now you can open your repository on GitHub to visit the "document-writing-guide.md" file listed