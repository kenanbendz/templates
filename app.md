## 📋 **PR Validation Checklist**

| **Section**            | **Details**                                                                                              |
|:-----------------------|:---------------------------------------------------------------------------------------------------------|
| **PR Summary**          | [Briefly describe the purpose of this PR, the feature it implements, or the bug it fixes.]                |
| **Linked Issue**        | [Provide the link to the related ClickUp issue or task.]                                                  |
| **Dependencies**        | [List any dependencies or special setup required for this PR.]                                           |

---

### **Preview**

Preview of the feature change (if applicable)

| **Before**                                      | **After**                                       |
|:-----------------------------------------------|:-----------------------------------------------|
| ![Screenshot of the feature before change]     | ![Screenshot of the feature after change]       |

---

### ✅ **Testing Checklist**

#### **Code Functionality**
- [ ] Does the code behave as expected locally without errors?
- [ ] Does the code correctly implement the described feature?
- [ ] Have you added tests for this change (unit tests, E2E tests, etc.)?
- [ ] Do all tests pass successfully in CI?
- [ ] Does the code pass the DeepSource analysis (code quality check)?

#### **Manual Testing**
- [ ] Have you manually tested the feature across different devices? (Simulator, Android, iOS, etc.)
- [ ] Have you tested edge cases (e.g., empty inputs, boundary values)?
- [ ] Have you verified all impacted user flows?
- [ ] Have you tested on mobile, tablet, and desktop (if applicable)?

#### **UI/UX**
- [ ] Does the UI match the design specifications (if applicable)?
- [ ] Is the app accessible to users with assistive technology (screen readers, keyboard navigation)?

