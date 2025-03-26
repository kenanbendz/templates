## 📋 **PR Validation Checklist**

| **Section**                | **Details**                                                                                                                                                   |
|:----------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **General Information**     |                                                                                                                                                                                                                                                           |
| **Linked Issue**            | [Link to the ClickUp issue or task related to this PR]                                                                                                                |                                                                                                                                                      |
| **Description of Changes**   | [Briefly explain what this PR is doing, what feature it implements or what bug it fixes.]                                                                    |
| **Dependencies**            | [Mention if this PR depends on other changes or needs special setup]                                                                                        |

---
### Preview
Preview of Feature change (if applicable)

| **Before**                                  | **After**                                   |
|---------------------------------------------|---------------------------------------------|
| ![Screenshot of the feature before change]  | ![Screenshot of the feature after change]   |


---

### ✅ **Testing Checklist**
#### 1. **Code Functionality**
- [ ] Does the code behave as expected locally?
- [ ] Does the code implement the described feature correctly?
- [ ] Have you added tests for this change? (Unit tests, E2E tests, etc.)
- [ ] Do the tests pass successfully in CI?

#### 2. **Manual Testing**
- [ ] Have you tested the feature manually across different devices? (Simulator, Android, iOS, etc.)
- [ ] Have you tested edge cases (e.g., empty inputs, boundary values)?
- [ ] Have you verified all possible user flows that might be affected by this change?
- [ ] Have you tested on mobile, tablet, and desktop (if applicable)?

#### 5. **UI/UX**
- [ ] Does the UI match the design specifications (if applicable)?
- [ ] Are there any UI inconsistencies or visual bugs?
- [ ] Is the app accessible (screen readers, keyboard navigation)?
  
#### 6. **Cross-browser/Device Testing**
- [ ] Have you tested the app in multiple browsers? (Chrome, Firefox, Safari, Edge)
- [ ] Have you checked for mobile responsiveness on all relevant devices?

#### 7. **Error Handling & Logging**
- [ ] Are there proper error messages when things go wrong?
- [ ] Is the logging in place for debugging in production? 

---

### ✅ **Code Quality**
- [ ] Is the code well-commented and easy to understand?
- [ ] Are all functions and methods properly named and organized?
- [ ] Did you follow the coding standards (e.g., linting, formatting)?
- [ ] Are there any dead or commented-out code snippets?

---

### ✅ **Review Checklist**
- [ ] Have you assigned the appropriate reviewer(s)?
- [ ] Does the code have an appropriate test coverage?

