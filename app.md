## 📋 **PR Validation Checklist**

| **Section**                | **Details**                                                                                                                                                   |
|:----------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Summary of PR**     | [Briefly explain what this PR is doing, what feature it implements or what bug it fixes.]                                                                                            |
| **Linked Issue**            | [Link to the ClickUp issue or task related to this PR]                                                                                                                |                                                                                                                                                      |
| **Dependencies**            | [Mention if this PR depends on other changes or needs special setup]                                                                                        |

---
### Preview
Preview of Feature change (if applicable)

| **Before**                                  | **After**                                   |
|:---------------------------------------------|:---------------------------------------------|
| ![Screenshot of the feature before change]  | ![Screenshot of the feature after change]   |


---

### ✅ Checklist
#### Code Functionality
- [ ] Does the code behave as expected locally and show no errors?
- [ ] Does the code implement the described feature correctly?
- [ ] Have you added tests for this change? (Unit tests, E2E tests, etc.)
- [ ] Do the tests pass successfully in CI?
- [ ] Does the code pass successfully in DeepSource (Code analysis)

#### Manual Testing
- [ ] Have you tested the feature manually across different devices? (Simulator, Android, iOS, etc.)
- [ ] Have you tested edge cases (e.g., empty inputs, boundary values)?
- [ ] Have you verified all possible user flows that might be affected by this change?
- [ ] Have you tested on mobile, tablet, and desktop (if applicable)?

#### UI/UX
- [ ] Does the UI match the design specifications (if applicable)?
- [ ] Is the app accessible (screen readers, keyboard navigation)?
  
#### Simulator & Device Testing
- [ ] Have you tested the app in multiple browsers? (Chrome, Firefox, Safari, Edge)
- [ ] Have you checked for mobile responsiveness on all relevant devices?

