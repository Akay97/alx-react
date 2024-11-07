# 0x03. React Component

## Project Overview
This project focuses on understanding and implementing React components, both functional and class-based, and learning essential concepts such as lifecycle methods, higher-order components (HOC), event handling, and performance optimization.

## Learning Objectives
By the end of this project, you will be able to:
- Differentiate when to use a class versus a function to create a component.
- Understand and explain the lifecycle of a class component.
- Test React components effectively.
- Utilize Jest spies to verify function calls.
- Create and apply higher-order components (HOC).
- Optimize performance and control component rendering.

## Project Requirements
- **Operating System**: Ubuntu 18.04 LTS
- **Node Version**: 12.x.x
- **NPM Version**: 6.x.x
- **Editors**: vi, vim, emacs, Visual Studio Code
- All files should end with a new line.
- A `README.md` file is mandatory.

## Tasks Overview
### 0. Commence with Class Components
- **Convert the App function into a React class** and ensure tests pass.

### 1. Lifecycle Methods
- Add a `logOut` prop and attach an event listener for `control + h` keypress. Test the component to ensure the `logOut` function and alert are called.

### 2. Handling Events
- Convert `Notifications` component to a class, add `markAsRead` function, and pass it to `NotificationItem`. Ensure appropriate tests are written.

### 3. Reusable Components
- Create a `BodySection` component that displays a title and children content.

### 4. Specialization with BodySectionWithMarginBottom
- Create `BodySectionWithMarginBottom` with specific styling and ensure prop types are defined.

### 5. Integrate New Components
- Modify `App.js` to wrap components with `BodySectionWithMarginBottom` and add a new section with `BodySection`.

### 6. Testing Components
- Write tests to verify `BodySection` and `BodySectionWithMarginBottom` render correctly with their props.

### 7. Create a Higher-Order Component (HOC)
- Implement `WithLogging` to log mount and unmount lifecycle methods of wrapped components.

### 8. HOC Tests
- Write tests to ensure `WithLogging` logs appropriate messages for both pure HTML and a `Login` component.

### 9. Pure Components
- Update `NotificationItem` to be a pure component for better performance.

### 10. Optimize Notification Updates
- Implement `shouldComponentUpdate` in `Notifications` to prevent unnecessary re-renders.

### 11. Advanced Tests
- Add tests to check if `Notifications` component does not re-render with the same list and re-renders with an updated list.

## How to Run the Project
1. Clone the repository.
2. Navigate to the project directory and install dependencies using `npm install`.
3. Run the project with `npm start`.
4. Run tests with `npm test`.

## Repository Structure
- **GitHub repository**: `alx-react`
- **Main Directory**: `0x03-React_component`
