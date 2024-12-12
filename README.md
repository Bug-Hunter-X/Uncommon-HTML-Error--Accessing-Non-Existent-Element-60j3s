# Uncommon HTML Bug: Accessing a Non-Existent Element

This repository demonstrates a common yet easily overlooked error in HTML and JavaScript: attempting to access and modify a DOM element that doesn't exist.  The error occurs silently in the browser, causing unexpected behavior unless developer tools (the browser's console) are used to find it.

## The Bug
The `bug.html` file contains an attempt to change the text of an element with the ID `'nonExistentElement'`.  However, no such element exists in the HTML.  This results in a runtime error.

## The Solution
The `bugSolution.html` file corrects this by checking for the element's existence before attempting to modify it.  This prevents errors and enhances the robustness of the script.

This simple example highlights the importance of thorough error checking and validation in web development, particularly when dealing with dynamic content and user interactions.