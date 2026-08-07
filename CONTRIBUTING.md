# Contributing to KeysPay

Thank you for your interest in contributing to KeysPay! We appreciate your help in making this project better. This document provides guidelines for contributing.

## 📋 Code of Conduct

- Be respectful and inclusive
- Focus on constructive feedback
- Help others learn and grow
- Report issues professionally

## 🐛 Reporting Bugs

When reporting a bug, please include:

1. **Clear, descriptive title** - What is the bug?
2. **Detailed description** - What were you trying to do?
3. **Steps to reproduce** - How can we recreate it?
4. **Expected behavior** - What should happen?
5. **Actual behavior** - What actually happened?
6. **Environment info:**
   - Operating System
   - Node.js version
   - npm version
   - Browser (if applicable)
7. **Screenshots/logs** - If applicable

### Example Bug Report
```
Title: Login button not responding on mobile

Steps to reproduce:
1. Open app on mobile device
2. Click login button
3. Form doesn't appear

Expected: Login form should appear
Actual: Nothing happens, no error shown

Environment: iOS 15, iPhone 12, Node 18.0.0
```

## 💡 Suggesting Features

For feature requests:

1. **Clear title** - What is the feature?
2. **Motivation** - Why is this needed?
3. **Description** - How should it work?
4. **Use cases** - Give real-world examples
5. **Additional context** - Any related info?

## 🔧 Development Setup

### 1. Fork and Clone
```bash
git clone https://github.com/YOUR-USERNAME/keyspay.git
cd keyspay
```

### 2. Add Upstream Remote
```bash
git remote add upstream https://github.com/babanla077/https-github.com-babanla077-keyspay.git
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Create Feature Branch
```bash
git checkout -b feature/your-feature-name
```

### 5. Start Development
```bash
npm run dev
```

## 📝 Making Changes

### Code Style
- Use consistent indentation (2 spaces)
- Write clear, descriptive variable names
- Add comments for complex logic
- Follow existing code patterns
- Keep functions small and focused
- Use ES6+ features

### File Naming
- Components: `PascalCase.jsx`
- Utilities: `camelCase.js`
- Styles: `kebab-case.css`
- Tests: `filename.test.js`

### Commit Messages
Write clear, descriptive commit messages:

```bash
# Good
git commit -m 'feat: Add multi-wallet support'
git commit -m 'fix: Resolve login timeout issue'
git commit -m 'docs: Update installation instructions'
git commit -m 'style: Format Admin.css'

# Avoid
git commit -m 'update'
git commit -m 'fix stuff'
git commit -m 'changes'
```

### Commit Types
- `feat:` - New feature
- `fix:` - Bug fix
- `docs:` - Documentation
- `style:` - Formatting (no code change)
- `refactor:` - Code refactoring
- `perf:` - Performance improvement
- `test:` - Adding/updating tests
- `chore:` - Maintenance

## 🧪 Testing

Before submitting:

1. **Test locally:**
   ```bash
   npm run dev
   ```

2. **Test production build:**
   ```bash
   npm run build
   npm run preview
   ```

3. **Manual testing checklist:**
   - [ ] Feature works as expected
   - [ ] No console errors
   - [ ] Responsive on mobile
   - [ ] Doesn't break existing features
   - [ ] Accessibility (keyboard navigation, screen readers)

## 📤 Submitting a Pull Request

### Before Submitting
1. Sync with upstream:
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. Ensure your branch is up to date

3. Test thoroughly

### PR Guidelines

1. **Title:** Be clear and descriptive
   ```
   ✓ Add transaction history filtering
   ✗ Update stuff
   ```

2. **Description:** Include:
   - What changes does this PR introduce?
   - Why are these changes needed?
   - How does this solve the problem?
   - Links to related issues
   - Screenshots (if UI changes)

3. **Example PR Description:**
   ```markdown
   ## Description
   Adds ability to filter transactions by date range and status.
   
   ## Motivation
   Users requested ability to view specific transactions easily.
   Fixes #123
   
   ## Changes
   - Added filter component in transaction history
   - Added date range picker
   - Added status filter dropdown
   - Updated transaction display logic
   
   ## Testing
   - Tested filter with various date ranges
   - Verified status filtering works
   - Tested on mobile devices
   
   ## Screenshots
   [Add screenshots here]
   ```

### PR Checklist
- [ ] Code follows style guide
- [ ] All tests pass
- [ ] Added/updated documentation
- [ ] No breaking changes
- [ ] Commit messages are clear
- [ ] PR description is detailed
- [ ] Changes are focused (one feature per PR)

## 🔄 Review Process

1. Maintainers will review your PR
2. You may be asked for changes
3. Discussion happens in PR comments
4. Once approved, PR will be merged

## 📚 Documentation

### Update These When Relevant
- `README.md` - For user-facing features
- `CONTRIBUTING.md` - For development info
- Code comments - For complex logic
- `.env.example` - For new environment variables

### Good Documentation Includes
- Clear explanations
- Code examples
- Common use cases
- Troubleshooting tips

## 🚀 Getting Help

- Check existing issues and discussions
- Ask in GitHub Discussions
- Comment on related issues
- Check documentation first

## 📋 Git Workflow Summary

```bash
# 1. Fork on GitHub

# 2. Clone locally
git clone https://github.com/YOUR-USERNAME/keyspay.git
cd keyspay

# 3. Add upstream
git remote add upstream https://github.com/babanla077/https-github.com-babanla077-keyspay.git

# 4. Create feature branch
git checkout -b feature/amazing-feature

# 5. Make changes and commit
git add .
git commit -m 'feat: Add amazing feature'

# 6. Keep in sync
git fetch upstream
git rebase upstream/main

# 7. Push to your fork
git push origin feature/amazing-feature

# 8. Create Pull Request on GitHub
```

## 💬 Questions?

Feel free to:
- Open an issue with your question
- Join the discussions
- Contact maintainers

Thank you for contributing to KeysPay! 🚀
