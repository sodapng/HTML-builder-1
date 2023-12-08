Description of the cross-check process **02-write-file**:

[Video with the example of cross-check](https://www.youtube.com/watch?v=zfH0VhWGyi0)

1. Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**.  
If synchronous methods or a timer are used, the task is considered not completed - **0 points**.

2. Make sure that there is only one file named `index.js` in the `02-write-file` folder. If not, remove all unnecessary files from the task folder.

3. <u>In the root directory of the repository</u>, execute the command `node 02-write-file` and ensure that a prompt for entering text appears in the console, and a text file has been created in the `02-write-file` directory.  
In case of errors or instant completion of the task execution, it is considered not completed - **0 points**.

4. After entering the text, make sure that the input is correctly recorded in the created text file.  
If this does not happen or the process ends without expecting further input, the task is considered not completed - **0 points**.

5. Use the `ctrl/cmd + c` key combination. A farewell phrase should be displayed in the console with subsequent process termination.  
If the process does not end or a farewell phrase is not displayed, **10 points are deducted**.

6. Run the script and enter `exit`. A farewell phrase should be displayed in the console with subsequent process termination.  
If the process does not end or a farewell phrase is not displayed, **10 points are deducted**.

If all points are successfully checked, **20 points** are awarded for the task.  
Minimum score - **0 points**.
