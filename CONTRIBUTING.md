# Contributing Guidelines

Welcome to the [xxxxx](<[xxxxxxx](https://github.com/Ali-Hammoud-DevOps/Test_Github_Skills)>) repository! We're excited that you're interested in contributing. Please take a moment to review this document to ensure a smooth collaboration process.

## How to Contribute

### Reporting Issues

If you find a bug or have a suggestion for an enhancement :

- Please make sure it was not asked before here [issues](https://github.com/Ali-Hammoud-DevOps/Test_Github_Skills/issues).
- Make sure it is not work in progress here [pull requests](https://github.com/Ali-Hammoud-DevOps/Test_Github_Skills/pulls).
- Make sure there is a Jira task of it here (Link)
- You can then [create an issue](https://github.com/Ali-Hammoud-DevOps/Test_Github_Skills/issues/new/choose) with the following information:
  - a short but descriptive title.
  - a detailed description of the issue or suggestion (if it is a bug include the steps to reproduce it).
- Ensure that the details provided align with the same criteria used in Jira for consistency and completeness.

### working on issues

- The software engineer (SE) begins work on the task that has been assigned to them.
- The SE creates a new branch for their task, following the appropriate naming conventions to ensure organization and traceability.
- After fixing the issue change the state of the task on Jira.
- QA tests those changes.

### Submitting Pull Requests

1. Fork the repository and create your own branch from `release` branch.
2. Follow this format for naming branches:
   - `9.2.0/Features/new-profile-page`
   - `9.2.0/Fix/login-validation-bug`
3. Make sure your code follows our [Coding Guidelines](#coding-guidelines).
4. Commit your changes using clear and descriptive commit messages .
5. Push your changes to your forked repository.
6. Submit a pull request to the `release` branch of this repository. Please include a detailed description of your changes.

We'll review your pull request as soon as possible. Feedback and suggestions are always welcome.

### Commit Guidelines

1. Reference the corresponding Jira task or issue key at the beginning of the commit message.
2. Each task or issue is addressed in a single commit, with a clear and traceable commit message.
3. **Use a Consistent Format**:
   - Start with the **key** followed by a colon (`:`).
   - Include a **type descriptor** (e.g., Feature, Fix, Enhancement).
   - Provide a **brief description** of the change.
   - ex: For a feature:"Key: Feature Name-Task Name”: PROJ-123: user login: Added user login functionality
         For a bug fix: "Key: Fix - Task Name”: PROJ-456: Fix: Fixed crash on login button click
         For a UI/UX enhancement: Key: enhancement - task Name”: PROJ-789: enhancement - Updated styles for login button

### Coding Guidelines

- Use consistent coding style and follow best practices for readability.
- Write clear and concise code comments.
- Don't update dependencies (example of dependencies) as it might break the project(we will update all dependencies soon).
- Do not include changes that are not related to the issue at hand.
- Ensure your code has no conflicts and follows existing patterns.

### Questions

If you have any questions, feel free to reach out by contacting xxxx

Thank you for contributing to [xxxx repo](https://github.com/Ali-Hammoud-DevOps/Test_Github_Skills)
