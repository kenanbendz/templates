## 📋 **PR Validation Checklist**

### General Information
- **PR Title:** [Short and descriptive title]
- **Linked Issue:** [Link to the issue or task related to this PR]

---

### ✅ **Feature/Task Information**
- **Description of Change:**
  - [Briefly explain what this PR is doing, what feature it implements or what bug it fixes.]
- **Feature Flag (if any):**
  - [Specify if there’s a feature flag involved]
- **Screenshots/Designs (if applicable):**
  - [Add links to relevant designs or before/after screenshots]
- **Dependencies:**
  - [Mention if this PR depends on other changes or needs special setup]
  
---

### ✅ **Testing Checklist**
#### 1. **Code Functionality**
- [ ] Does the code behave as expected locally?
- [ ] Does the code implement the described feature correctly?
- [ ] Have you added tests for this change? (Unit tests, integration tests, etc.)
- [ ] Do the tests pass successfully in CI?

#### 2. **Manual Testing**
- [ ] Have you tested the feature manually across different environments? (Dev, Staging, etc.)
- [ ] Have you tested edge cases (e.g., empty inputs, boundary values)?
- [ ] Have you verified all possible user flows that might be affected by this change?
- [ ] Have you tested on mobile, tablet, and desktop (if applicable)?

#### 3. **Performance**
- [ ] Have you checked for performance regressions (loading times, memory usage, etc.)?
- [ ] Is the app responsive and optimized?

#### 4. **Security**
- [ ] Is there any sensitive data handled? Have you ensured it's protected?
- [ ] Are there any security concerns (e.g., XSS, SQL injection) introduced by this change?

#### 5. **UI/UX**
- [ ] Does the UI match the design specs (if applicable)?
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

---

### 📝 **Additional Notes**
- [ ] Any additional context or clarifications the reviewer should know?
