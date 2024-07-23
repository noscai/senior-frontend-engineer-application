### Task Description for Senior Frontend Developer

#### Overview
You will be tasked with creating the admin interface for managing anamnesis forms within the ClinicOS system. This interface will include features for listing, creating, updating, and deleting anamnesis forms, sections, and questions. You will use Vite, React, TailwindCSS, and TypeScript, along with specific libraries for handling drag-and-drop functionality and table displays.

#### Technologies and Libraries
- **Vite** for building the application
- **React** for the user interface
- **TailwindCSS** for styling
- **TypeScript** for type safety
- **DndKit** for drag-and-drop functionality
- **React-Table** for displaying tables

#### Task Requirements
1. **Project Setup**
   - Initialize a new Vite project with React and TypeScript.
   - Set up TailwindCSS for styling.

2. **Pages and Functionality**
   - Create the following pages with the specified functionalities:

   **1. List of All Anamnesis Forms**
   - Use `react-table` to display a list of all anamnesis forms.
   - Include columns for form title, description, creation date, and actions (view, edit, delete).
   - Implement pagination, sorting, and searching functionalities.
   - For searching, add debounce functionality and simulate an async search.

   **2. Anamnesis Form Detail Page**
   - Display the details of a selected anamnesis form.
   - Show the sections and questions within the form.
   - Use `DndKit` to allow drag-and-drop reordering of sections and questions.

   **3. Create Anamnesis Form Page**
   - Provide a form to create a new anamnesis form with fields for the title and description.
   - Allow adding multiple sections, and within each section, allow adding multiple questions.
   - Use `DndKit` for drag-and-drop functionality to reorder sections and questions.

   **4. Update Anamnesis Form Page**
   - Similar to the create page, but pre-populate the form with the existing data of the selected anamnesis form.
   - Allow updating the form, sections, and questions.
   - Use `DndKit` for drag-and-drop functionality to reorder sections and questions.

3. **Deletion Functionality**
   - Implement the ability to delete an anamnesis form from the list page.
   - Implement the ability to delete a section from a form or a question from a section on the detail and update pages.

4. **Debounced Search Functionality**
   - Implement a search input with debounce functionality.
   - Simulate an asynchronous search to fetch and display results.

#### Detailed Page Descriptions
**1. List of All Anamnesis Forms**
   - Create a React component to fetch and display anamnesis forms using `react-table`.
   - Include action buttons for viewing, editing, and deleting each form.
   - Example Columns: 
     - Title
     - Description
     - Created At
     - Actions (View, Edit, Delete)
   - Implement search with debounce and simulate an async search call.

**2. Anamnesis Form Detail Page**
   - Create a React component to display details of the selected anamnesis form.
   - Fetch and display form sections and questions.
   - Implement drag-and-drop for reordering sections and questions using `DndKit`.

**3. Create Anamnesis Form Page**
   - Create a form to input the title and description of a new anamnesis form.
   - Allow dynamically adding sections and questions.
   - Implement drag-and-drop for reordering sections and questions using `DndKit`.

**4. Update Anamnesis Form Page**
   - Similar to the create page, but with fields pre-populated with existing data.
   - Allow editing the form details, sections, and questions.
   - Implement drag-and-drop for reordering sections and questions using `DndKit`.

#### Additional Requirements
- Use TypeScript for all components and ensure type safety.
- Do not use any other component libraries outside of the specified ones.
- Ensure the UI is responsive and user-friendly.
- Provide clear and concise documentation for setting up and running the project.

#### Submission
- Provide a GitHub repository link with your Vite + React + TailwindCSS project.
- Include a README.md with instructions on how to set up and run your project.
- Document your design decisions, especially for the data flow and state management approach.

### Evaluation Criteria
- **Functionality**: The interface works as intended, with proper CRUD operations for forms, sections, and questions.
- **Code Quality**: Clean, readable, and maintainable code.
- **Design**: User-friendly and responsive UI design.
- **Usage of Libraries**: Effective use of `react-table` and `DndKit`.
- **TypeScript Usage**: Proper use of TypeScript for type safety.
- **Debounced Search**: Implementation of search with debounce and async simulation.
- **Documentation**: Clear instructions and well-documented code.

Good luck, and we look forward to reviewing your submission!
