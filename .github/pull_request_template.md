## 📝 Description
<!-- Provide a clear, concise summary of the changes you made and why. -->
- Implemented the `LoginPage` Object class with robust locators.
- Added comprehensive E2E tests covering successful login and validation of error messages.
- Cleaned up root directory structures by removing legacy template files.

## 🎯 Purpose / Context
<!-- What problem does this solve? Link to a Jira ticket, Udemy lesson, or issue if applicable. -->
- Resolves: Lesson #42 (Handling Login Framework Architecture)
- This establishes the core security boundary testing layout for the entire suite.

## 🛠️ Type of Change
- [ ] 🐛 Bug fix (non-breaking change which fixes an issue)
- [x] ✨ New feature (non-breaking change which adds functionality)
- [ ] 💥 Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [x] 🧹 Chore / Refactor (code cleanup, configuration tweaks, no logic changes)

## 🧪 How Has This Been Tested?
<!-- Describe the tests that you ran to verify your changes. Provide instructions so we can reproduce. -->
- Run the login spec file locally using Playwright UI mode:
  ```bash
  npx playwright test login.spec.ts --ui
  ```
- Verified cross-browser compatibility across Chromium, Firefox, and WebKit (all passing).

## 📸 Screenshots / Recordings (If applicable)
<!-- Add a screenshot or a GIF of your passing test execution/report here to save your reviewer time. -->
- [Link or drop image here for the HTML Test Report]

## 📋 PR Checklist
- [x] My code follows the style guidelines of this project
- [x] I have performed a self-review of my own code
- [x] My changes generate no new TypeScript compiler errors
- [x] New and existing unit/E2E tests pass locally with my changes
