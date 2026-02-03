## 📘 Learning Notes

### 1. Git commit author vs GitHub username

Before this project, I didn’t realize that Git commit authors are determined by
`user.name` and `user.email`, not the GitHub username.

**What I learned**
- Git stores author information locally
- GitHub displays commits based on commit metadata
- Inconsistent author names can affect GitHub profile appearance

**How I fixed it**
- Configured global Git user settings
- Rewrote commit history using `git filter-branch`

---

### 2. Why dark mode didn’t change the background color

When implementing dark mode, the icon toggled correctly, but the background color
did not update.

**Root cause**
- CSS variables were overridden by hard-coded color values later in the file

**Solution**
- Removed hard-coded colors
- Centralized theme values using CSS variables

---

### 3. Writing a production-ready README

This was my first time writing a README intended for GitHub portfolio display.

**Key takeaways**
- Clear project description matters more than long explanations
- Screenshots and structure greatly improve readability
- A good README makes a small project feel complete

---

### 4. GitHub workflow confidence boost

Through this project, I became comfortable with:
- Initializing repositories
- Writing meaningful commit messages
- Handling push conflicts and rebasing
