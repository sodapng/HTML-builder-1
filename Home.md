## HTML Builder Cross-Check

The check is carried out on the current **LTS** version of Node, and <u>without</u> executing the `npm install` command in the cloned repository, as any external modules are prohibited.

[Video guide on starting the cross-check of this task](https://www.youtube.com/watch?v=zBgZmJeIpRo)

### Cross-Check Steps

1. Клонируйте [репозиторий с заданием](https://github.com/EvgeniiMal/HTML-builder) и откройте корневую папку с заданием в среде разработки
2. Откройте страницу с репозиторием задания проверяемого студента
3. Откройте папку с соответствующей задачей, затем откройте файл index.js и скопируйте код задачи
4. В среде разработки найдите папку с соответствующей задачей и откройте в ней файл index.js для редактирования
5. Вставьте туда ранее скопированный код проверяемого студента и сохраните изменения.
6. Обратите внимание на то какой метод импорта использует проверяемый. В случае если используются es6 modules(import/export) для корректной работы вам нужно внести правки в ваш **package.json** файл. Добавьте строку ```"type": "module",``` в **package.json** сразу после строки ```"description": "html-builder task for RSSchool",```
7. Для каждого из заданий выполните проверку согласно описанному ниже порядку действий. Перед проверкой следующего студента приведите локальный репозиторий в исходное состояние. Задания должны проверяться строго в порядке от 01 до 06:

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
