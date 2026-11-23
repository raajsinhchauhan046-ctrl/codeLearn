CODELEARN — BEGINNER SETUP
==========================

WHAT'S INCLUDED
---------------
- index.html: website structure and page content
- style.css: responsive layout, colors, typography and dark mode
- app.js: course lessons, navigation, search, quiz, progress and live editor

HOW TO RUN ON WINDOWS
---------------------
1. Download and extract CodeLearn.zip.
2. Open the extracted CodeLearn folder.
3. Double-click index.html.
4. It should open in Google Chrome.
5. Click HTML, CSS, JavaScript, Python or SQL in the top navigation.
6. Edit the code in the practice editor and click "Run code".

RECOMMENDED EDITOR
------------------
Install Visual Studio Code if you want to edit the project:
1. Open VS Code.
2. Choose File > Open Folder.
3. Select the extracted CodeLearn folder.
4. Open index.html, style.css or app.js to edit.
5. Save with Ctrl + S, then refresh Chrome.

OPTIONAL LOCAL SERVER
--------------------
For a more realistic development workflow, install the "Live Server" extension
in VS Code. Right-click index.html and choose "Open with Live Server".

FEATURES
--------
- Responsive desktop and mobile layout
- HTML, CSS, JavaScript, Python and SQL tutorial sections
- Eight starter lessons per course
- Lesson navigation and search
- Live HTML preview using a sandboxed iframe
- Dark/light mode
- One quick knowledge-check question per course
- Completion tracking saved in browser localStorage

IMPORTANT LIMITATIONS
---------------------
This is a front-end starter project. It does not include a real user account
system, cloud database, server-side code execution, certificates or payments.
The Sign in button is a demo dialog. Lesson progress is stored only in the
current browser on this device.

The editor previews HTML in a sandboxed iframe. It is not a secure server-side
Python, SQL or JavaScript execution environment. The examples for Python and
SQL are learning snippets, not runnable in this HTML preview.

NEXT DEVELOPMENT STEPS
----------------------
To turn this into a production learning platform, add:
- Backend authentication and user profiles
- Database-backed lesson progress
- More detailed lessons and exercises
- Separate safe code execution services for programming languages
- Admin tools to create and update courses
- Accessibility testing and security review
