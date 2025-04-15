# Custom Instructions for GitHub Copilot

This guide is intended to help you provide better context for GitHub Copilot when working on programming-related tasks. Use this template to define your goals, preferences, and any specific guidelines you'd like Copilot to follow.

---

## Project Overview
Provide a brief overview of your project. Include the purpose, key technologies, and any specific goals.

- **Project Purpose**: [Describe the purpose of your project. Example: "Developing a web application for e-commerce."]
- **Key Technologies**: [List the primary languages, frameworks, or tools. Example: "JavaScript, React, Node.js, MongoDB."]
- **Current Focus**: [Mention what part of the project you're currently working on. Example: "Implementing user authentication."]

---

## Coding Preferences
Share your coding style and preferences to guide Copilot in generating code that aligns with your standards.

- **Code Style**: [Example: "Follow Airbnb's JavaScript Style Guide."]
- **Commenting Style**: [Example: "Use JSDoc for function documentation and inline comments sparingly."]
- **Error Handling**: [Example: "Always handle errors explicitly with try/catch blocks."]
- **Testing**: [Example: "Write tests using Jest and aim for 80% code coverage."]

---

## Task-Specific Context
Provide guidance for specific tasks you need help with.

- **Task**: [Describe the task. Example: "Write a function to validate email addresses."]
- **Inputs**: [Specify any inputs. Example: "A string containing the email address."]
- **Outputs**: [Specify any outputs. Example: "Return true if valid, false otherwise."]
- **Constraints**: [Mention any constraints. Example: "Do not use regex."]

---

## Examples and References
Provide examples of desired output or references to existing code.

- **Example Code**: [Include a code snippet. Example: "Here's how we handle form validation:"]
  ```javascript
  function validateForm(data) {
      if (!data.email) {
          throw new Error('Email is required');
      }
  }
  ```
- **Documentation Links**: [Link to relevant documentation. Example: "Refer to the React docs for component lifecycle methods: https://reactjs.org/docs/react-component.html"]

---

## Special Instructions
Include any other instructions or details that may help Copilot assist you effectively.

- **Known Issues**: [Example: "Avoid using library X due to licensing concerns."]
- **Preferred Libraries**: [Example: "Use Axios for HTTP requests instead of Fetch."]
- **Performance Goals**: [Example: "Optimize for low memory consumption."]

---

## Communication Style
Tell Copilot how to communicate with you about its suggestions.

- **Detail Level**: [Example: "Provide detailed inline comments for complex code."]
- **Clarity**: [Example: "Use simple and clear variable names."]
- **Feedback**: [Example: "Be concise but explain the reasoning behind code patterns."]

---

Feel free to customize this template further to suit your specific needs. The more context you provide, the better Copilot can assist you!