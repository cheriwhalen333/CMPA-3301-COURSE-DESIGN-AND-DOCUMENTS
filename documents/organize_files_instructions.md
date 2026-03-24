GITHUB FOLDERS AND FILE ORGANIZATION

In GitHub, "folders" work a little differently than they do on your computer's desktop. GitHub **does not allow you to create an empty folder.** A folder only "exists" on GitHub if there is at least one file inside it.

Here is the quickest way to create a documents folder directly on the GitHub website.

**## The "New File" Shortcut**

You can create a folder and a file at the same time using this trick:

# 1. Navigate to the main page of your repository (e.g., CMPA\_3301\_Dashboards).
# 2. Click the Add file button and select Create new file.
# 3. In the box where it asks for the File name, type the name of the folder followed by a forward slash:
- Type: documents/
# 4. The slash tells GitHub to create a folder. Now, give your first document a name immediately after the slash:
- Example: documents/README.md or documents/instructions.html
# 5. Add some text to the file (like "This folder contains project documentation").
# 6. Scroll down and click Commit changes.

**## Using GitHub Desktop (Easier for many files)**

If you have several documents (like PDFs, Word docs, or extra HTML files) ready to go on your computer, use the Desktop app:

# 1. Open your repository folder on your computer (Right-click the repo in GitHub Desktop and select Show in Finder/Explorer).
# 2. Create a new folder named documents just like you normally would on your PC or Mac.
# 3. Move your files into that folder.
# 4. Go back to GitHub Desktop. You will see the new files listed on the left.
# 5. Type a summary (e.g., "Add documents folder"), click Commit to main, and then click Push origin.

**## Important: Linking to these documents**

Now that your files are in a folder, their "address" has changed. If you want to link to a file inside that folder from your index.html, you must include the folder name in the link:

**Correct Link:** <a href="documents/instructions.html">View Instructions</a>

**Incorrect Link:** <a href="instructions.html">View Instructions</a> (This will break because the file is no longer in the "root" folder).

**## Pro-Tip: Organizing by Module**

Since you are working through a course, many students find it helpful to create folders for each week:

- Module\_01/
- Module\_02/

This keeps your main "root" folder from getting cluttered with dozens of files.
