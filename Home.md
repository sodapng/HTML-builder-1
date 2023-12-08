## HTML Builder Cross-Check

The check is carried out on the current **LTS** version of Node, and <u>without</u> executing the `npm install` command in the cloned repository, as any external modules are prohibited.

[Video guide on starting the cross-check of this task](https://www.youtube.com/watch?v=zBgZmJeIpRo)

### Cross-Check Steps

1. Clone the [task repository](https://github.com/rolling-scopes-school/HTML-builder) and open the root folder with the task in your IDE/code editor.

2. Open the page with the repository of the student whose task you are checking.

3. Open the folder with the corresponding task, then open the `index.js` file, and copy the code of the task.

4. In your IDE, find the folder with the corresponding task and open the `index.js` file for editing.

5. Paste the previously copied code of the student to check into the file and save the changes.

6. Pay attention to the import method used by the student. In case **ES6 modules** (`import/export`) are used, you need to make changes to your `package.json` file.  
Add the line `"type": "module"`, to `package.json` <u>immediately after</u> the line `"description": "html-builder task for RSSchool",`.

7. For each of the tasks, perform the check according to the sequence of actions described below. Before checking the next student, restore the local repository to its original state. Tasks must be checked strictly in order from 01 to 06:

- [01 read file](https://github.com/rolling-scopes-school/HTML-builder/wiki/Check-01-read-file)
- [02 write file](https://github.com/rolling-scopes-school/HTML-builder/wiki/Check-02-write-file)
- [03 files in folder](https://github.com/rolling-scopes-school/HTML-builder/wiki/Check-03-files-in-folder)
- [04 copy directory](https://github.com/rolling-scopes-school/HTML-builder/wiki/Check-04-copy-directory)
- [05 merge styles](https://github.com/rolling-scopes-school/HTML-builder/wiki/Check-05-merge-styles)
- [06 build page](https://github.com/rolling-scopes-school/HTML-builder/wiki/Check-06-build-page)
