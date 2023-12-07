Description of the cross-check process **04-copy-directory**:

#### [Video with the example of cross-check](https://www.youtube.com/watch?v=SIcfroM-QwA)

1. Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**. If synchronous methods or a timer are used, the task is considered not completed - **0 points**.
2. Check the `index.js` file for the presence of the experimental function **fsPromises.cp()**. If this function is used, the task is considered not completed - **0 points**.
3. Open the `files` folder and make sure it is not empty. Otherwise, create several files at your discretion.
4. <u>In the root directory of the repository</u>, execute the command `node 04-copy-directory`.
5. After the script execution is complete, check the `04-copy-directory` folder for the presence of the created `files-copy` folder with an exact copy of the content of the original `files` folder.  
If this folder is missing or its content does not match the content of the `files` folder, the task is considered not completed - **0 points**.
6. Add several new files to the `files` folder and delete one of the previously existing ones. Run the command `node 04-copy-directory`.
7. Ensure that the content of the `files-copy` folder is updated and corresponds to the content of the `files` folder. If an error occurred during execution or the state of the `files-copy` folder was not updated, the task is considered not completed - **0 points**.

If all points are successfully checked, **20 points** are awarded for the task.
