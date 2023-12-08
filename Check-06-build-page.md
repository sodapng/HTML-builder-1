Description of the cross-check process **06-build-page**:

[Video with the example of cross-check](https://www.youtube.com/watch?v=bdWQyl6nXFA)

1. Check the code for the presence of synchronous methods of the **fs module** (you can use the `ctrl/cmd + f` key combination and enter `Sync` in the search field that appears) and **setTimeout()**.  
If synchronous methods or a timer are used, the task is considered not completed - **0 points**.

2. Check the `index.js` file for the presence of the experimental function **fsPromises.cp()**.  
If this function is used, the task is considered not completed - **0 points**.

3. <u>In the root directory of the repository</u>, execute the command `node 06-build-page`.

4. After the script terminates its execution, a `project-dist` folder should be created in the `06-build-page` directory, containing the `index.html` and `style.css` files, as well as the `assets` folder.  
If this does not happen, the task is considered not completed - **0 points**.

5. Ensure that the `index.html` file contains markup from the `template.html` file with the replacement of template tags with the markup of similarly named component files from the `components` folder. The markup of component files should be strictly in the places corresponding to the template tags. There should be no template tags themselves in the `index.html` file.  
If this is not the case, the task is considered not completed - **0 points**.

6. Check the `style.css` file for the correct assembly of styles from the `styles` folder. Similar to the task **05-merge-styles**, styles should maintain formatting and not interfere with each other.  
If the styles are assembled incorrectly, the task is considered not completed - **0 points**.  

   Note that when using **liveServer**, you may notice minor styling issues in the footer. <u>This case is not considered an error</u>.

7. Open the `assets` folder. Ensure that its content and the content of subfolders inside it exactly match the content of the `assets` folder in `06-build-page/assets`.  
If this is not the case, the task is considered not completed - **0 points**.

8. Add the test files from the `test-files` folder to the project:
   - `06-build-page/test-files/components/about.html` -> `06-build-page/components/about.html`
   - `06-build-page/test-files/images/squirrel-2.jpg` -> `06-build-page/assets/img/squirrel-2.jpg`
   - `06-build-page/test-files/styles/about.css` -> `06-build-page/styles/about.css`

   Don't forget to specify the new template tag in the `template.html` file. Then, repeat steps 3-7.

If all points are successfully checked, **50 points** are awarded for the task.
