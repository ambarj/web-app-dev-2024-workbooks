# Web Application Development - Fall 2024

Welcome to the Web Application Development course! 

In this course we will use NodeJS notebooks for hands-on experience and in class activities to practice and implement various concepts you learn in class. This README file will guide you through the setup of Visual Studio Code (VS Code) and the use of .nnb files.

**Note**: Not all code snippets will work in notebook environment. When this happens, try code in your local setup or online playgrounds. We will be using notebook environment only for academic purposes and book keeping. For actual implementation use standard recommended methods.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en/download/) (LTS version recommended)
- [Visual Studio Code](https://code.visualstudio.com/)

## Setting Up Visual Studio Code

Follow these steps to set up Visual Studio Code for using .nnb files:

### 1. Install Visual Studio Code

Download and install Visual Studio Code from the [official website](https://code.visualstudio.com/).

### 2. Install Node.js

Download and install Node.js from the [official website](https://nodejs.org/en/download/). Make sure you download the LTS version.

### 3. Install the Node.js Extension for VS Code

1. Open VS Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X` or `Cmd+Shift+X` on Mac.
3. In the Extensions view, search for "Node.js Notebooks (REPL)" and install the extension.

### 4. Install Jupyter Extension (if needed)

If you plan to use Jupyter notebooks within VS Code, you should install the Jupyter extension:

1. In the Extensions view, search for "Jupyter" and install the extension.

### 5. Clone the Course Repository

Clone the course repository to your local machine using Git. Open a terminal and run the following command:

```bash
git clone https://github.com/ambarj/web-app-dev-2024-workbooks.git
```

### 6. Open the Repository in VS Code

1. Open VS Code.
2. Click on `File` > `Open Folder...` and select the cloned repository folder.

## Using .nnb Files in VS Code

Follow these steps to use .nnb files in VS Code:

### 1. Open a .nnb File

1. In VS Code, navigate to the folder where your .nnb files are located.
2. Click on the .nnb file you want to open.

### 2. Run the Notebook

1. Once the .nnb file is open, you should see a toolbar at the top of the notebook.
2. To execute a cell, click on the cell and press `Shift+Enter` or click on the `Run` button.

### 3. Install Required Packages

Some notebooks may require specific Node.js packages. You can install these packages using `npm`. For example, if a notebook requires `express`, you can install it by running:

```bash
npm install express
```

### 4. Save Your Work

Make sure to save your work frequently by clicking `File` > `Save` or by pressing `Ctrl+S`.

## Troubleshooting

If you encounter any issues, consider the following steps:

- Ensure Node.js and VS Code are correctly installed.
- Verify that the required extensions are installed in VS Code.
- Check the terminal output for any error messages and address them accordingly.
- Reach out to the course instructor or teaching assistants for help.

## Additional Resources

- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Visual Studio Code Documentation](https://code.visualstudio.com/docs)
- [Jupyter Extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

Happy coding!