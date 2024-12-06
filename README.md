# auto generate version & CHANGELOG

## a recap

Here’s a **cheat sheet of Conventional Commit keywords** with clear, professional purposes to guide your commits effectively:

---

### **Core Keywords**

| **Keyword** | **Purpose**                                               | **Example Commit**                            |
| ----------- | --------------------------------------------------------- | --------------------------------------------- |
| `feat`      | Adds a new feature to the codebase.                       | `feat(auth): add JWT-based authentication`    |
| `fix`       | Fixes a bug in the code.                                  | `fix(ui): resolve button alignment issue`     |
| `perf`      | Improves performance without changing functionality.      | `perf(api): optimize query execution time`    |
| `refactor`  | Changes the code structure without altering its behavior. | `refactor(utils): simplify date parser logic` |
| `test`      | Adds or updates tests in the codebase.                    | `test(auth): add unit tests for login`        |

---

### **Documentation Keywords**

| **Keyword** | **Purpose**                                          | **Example Commit**                        |
| ----------- | ---------------------------------------------------- | ----------------------------------------- |
| `docs`      | Updates or adds documentation.                       | `docs(readme): add setup instructions`    |
| `docs`      | Fixes typos or improves formatting in documentation. | `docs(api): correct typo in endpoint doc` |

---

### **Code Quality Keywords**

| **Keyword** | **Purpose**                                                                   | **Example Commit**                            |
| ----------- | ----------------------------------------------------------------------------- | --------------------------------------------- |
| `style`     | Makes code style changes (e.g., formatting, linting) without affecting logic. | `style(css): format header styles`            |
| `chore`     | Performs maintenance tasks such as updating dependencies or config files.     | `chore: update ESLint to v8.0.0`              |
| `build`     | Changes build tools, dependencies, or configurations.                         | `build: update Webpack config for production` |

---

### **Continuous Integration / Deployment Keywords**

| **Keyword** | **Purpose**                                | **Example Commit**                          |
| ----------- | ------------------------------------------ | ------------------------------------------- |
| `ci`        | Updates CI/CD pipelines or configurations. | `ci: add GitHub Action for test automation` |
| `deploy`    | Triggers a deployment process.             | `deploy: deploy new version to production`  |

---

### **Breaking Changes**

| **Keyword** | **Purpose**                                          | **Example Commit**                            |
| ----------- | ---------------------------------------------------- | --------------------------------------------- |
| `feat!`     | Adds a new feature that introduces breaking changes. | `feat!(auth): migrate to OAuth2`              |
| `refactor!` | Refactors code, introducing breaking changes.        | `refactor!(api): remove deprecated endpoints` |

---

### **Other Keywords**

| **Keyword** | **Purpose**                            | **Example Commit**                          |
| ----------- | -------------------------------------- | ------------------------------------------- |
| `revert`    | Reverts a previous commit.             | `revert: revert feat(ui): add dark mode`    |
| `merge`     | Merges branches or resolves conflicts. | `merge: integrate feature branch into main` |

---

### **Best Practices**

1. **Use Imperative Descriptions**:  
   Write commit messages as if you’re giving a command.

   - ✅ `feat(ui): add toggle for dark mode`.
   - ❌ `feat(ui): added toggle for dark mode`.

2. **Keep it Concise**:

   - ✅ `fix(api): resolve timeout issue on /users`.
   - ❌ `fix(api): fixed a problem where the /users endpoint would occasionally timeout`.

3. **Add Scopes for Clarity**:
   - **Good**: `feat(homepage): add carousel`.
   - **Better**: `feat(homepage/ui): add image carousel with autoplay`.

---

This cheat sheet ensures your commits are clear, professional, and suitable for automated workflows. Let me know if you need printable formatting!





## nice docs : [Conventional Commit Messages](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)