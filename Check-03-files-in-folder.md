Description of the cross-check process **03-files-in-folder**:

[Video with the example of cross-check](https://www.youtube.com/watch?v=fMJ4zE1DnD8)

1. Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**. If synchronous methods or a timer are used, the task is considered not completed - **0 points**.
2. <u>In the root directory of the repository</u>, execute the command `node 03-files-in-folder`. Information about files inside the `secret-folder` should be displayed in the console (<u>information about files in subfolders should not be displayed</u>). If you encounter an error during execution or receive incorrect information about files, the task is considered not completed - **0 points**.
3. Add one or more files of different sizes to the `secret-folder` (you can generate filler text, for example, [here](https://www.lipsum.com/)).
4. Add two folders to the `secret-folder`. In the name of one of the folders, specify a fake extension (e.g., `my-folder.js`).
5. Run the script with the command `node 03-files-in-folder` and check the correctness of the displayed data. If the information about added files is incorrect or if data about directories is displayed, the task is considered not completed - **0 points**.

If all points are successfully checked, **20 points** are awarded for the task.  
Minimum score - **0 points**.
