Description of the cross-check process **05-merge-styles**:

[Video with the example of cross-check](https://www.youtube.com/watch?v=MHz_1ExMRPU)

1. Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**. If synchronous methods or a timer are used, the task is considered not completed - **0 points**.
2. Ensure that only the `index.html` file is present in the `project-dist` folder. If there are any extraneous files, delete them.
3. <u>In the root directory of the repository</u>, execute the command `node 05-merge-styles`. For a better understanding of the script's operation, you can open the `index.html` file using the **Live Server** extension. If there are errors during the script's execution, the task is considered not completed - **0 points**.
4. Check the content of the `bundle.css` file. The content of the file and the styling format in it should match the source files, and styles should not be merged. <u>The sequence of styles is not checked!</u> If `bundle.css` contains incorrect styles, the task is considered not completed - **0 points**.
5. Change the content of the `styles` folder by removing one or more style files, or replace the `styles` folder and `project-dist/index.html` with the content of the `test-files` folder (the previously generated `bundle.css` file should remain in `project-dist`).
6. In the `styles` folder, add a file with an extension other than `css` and content like `ext-test-string` (or any other string of your choice).
7. Run the script and ensure that the `bundle.css` file is overwritten and contains up-to-date and correct styles. If this does not happen, the task is considered not completed - **0 points**.
8. Search for the string `ext-test-string` (or the string written in a file with an extension other than `css`) in the `bundle.css` file using the `ctrl/cmd + f` key combination. If the string is present in the file, the task is considered not completed - **0 points**.

If all points are successfully checked, **20 points** are awarded for the task.
