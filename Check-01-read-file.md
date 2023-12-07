Description of the cross-check process **01-read-file**:

[Video with the example of cross-check](https://www.youtube.com/watch?v=xBkbVDd582g)

1. Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**. If synchronous methods or a timer are used, the task is considered not completed - **0 points**.
2. Make sure that a **ReadStream** is used to read the file. If a stream is not used for reading the file, the task is considered not completed - **0 points**.
3. <u>In the root directory of the repository</u>, execute the command `node 01-read-file` and make sure that the contents of the `text.txt` file are output to the console (the presence/absence of empty lines at the end of the file is <u>not checked</u>). In case of errors or empty output when there is text in `text.txt`, the task is considered not completed - **0 points**.
4. Change the contents of the `text.txt` file and run the command `node 01-read-file` again. The result should correspond to the current state of `text.txt`, otherwise, the task is considered not completed - **0 points**.

If all points are successfully checked, **20 points** are awarded for the task.
