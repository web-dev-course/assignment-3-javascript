# Assignment 3: To-Do App

## Objective
Build a responsive To-Do app that fetches, displays, adds, and manages tasks using JavaScript, DOM manipulation, and the Fetch API. 

## Features and Requirements

1. **Initial Setup:**
   - Fetch the first 10 to-dos from the [DummyJSON API](https://dummyjson.com/todos).
   - Filter the to-dos based on their `completed` status and append them to the "Completed" and "Not Completed" lists.

2. **Task Management:**
   - **Mark as Completed:** If a user clicks the checkbox on a to-do in the "Not Completed" list, it should move to the "Completed" list and be removed from the "Not Completed" list.
   - **Mark as Not Completed:** If a user unchecks a to-do in the "Completed" list, it should move back to the "Not Completed" list.
   - **Delete To-Do:** Each to-do should have a delete button to remove it from the list.
   - **Add New To-Do:** The user can enter a new to-do in the input box, and it should be added to the "Not Completed" list.

3. **Responsive Design:**
   - Use Bootstrap to ensure the app is responsive and looks good on both web and mobile views, following the provided Figma design. (You must follow the Figma design file)

4. **Dynamic Updates:**
   - Use JavaScript DOM manipulation to perform all dynamic tasks (e.g., adding, moving, and deleting to-dos).
   - Use the Fetch API to get the initial list of to-dos.

5. **Assets:**
   - If you require any assets, make sure to download them from the provided Figma file and add them to the `assets/images` folder given in the boilerplate template.

## Implementation Instructions

1. **Accept the Assignment from GitHub:**
   - Click on the link provided in Slack to accept the assignment.
   - Clone the repository to your local machine using the following command:
     ```bash
     git clone <your-assignment-link>
     ```

2. **HTML Structure:**
   - Create the basic HTML structure for the to-do app, including input fields, buttons, and lists for "Completed" and "Not Completed" tasks.
   
3. **CSS and Bootstrap:**
   - Use the provided Figma design to style your app. Make sure you follow the designs.
   - Ensure responsiveness using Bootstrap classes for layout and design.

4. **JavaScript Functionality:**
   - Fetch the initial 10 to-dos from the DummyJSON API.
   - Append to-dos to the appropriate lists based on their `completed` status.
   - Add event listeners for the checkboxes and delete buttons to update the lists dynamically.
   - Handle new to-do input and append it to the "Not Completed" list.

## Deadline
- **Submission Deadline:** 5th August, 7:45 PM.

## Additional Notes
- If you require any assets, make sure to download them from the provided Figma file and add them to the `assets/images` folder given in the boilerplate template.

## Helpful Resources
- [JavaScript Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- [JavaScript DOM Manipulation](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

## Submission
- Submit your completed project by committing your changes and pushing them to the GitHub repository:
  ```bash
  git add .
  git commit -m "<your commit message>"
  git push origin


## Add you documentation here ...
