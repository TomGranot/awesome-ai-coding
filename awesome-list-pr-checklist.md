# Comprehensive Awesome List Pull Request Checklist

## 🚨 CRITICAL REQUIREMENTS (Often Missed)

### PR Process Requirements
- [ ] **DO NOT open a Draft/WIP pull request** - The PR must be complete and ready for review
- [ ] **Review at least 2 open pull requests BEFORE submitting yours**
  - ⚠️ **Priority**: Review PRs that haven't been reviewed yet
  - ⚠️ **Quality**: Must provide thorough, substantive reviews
  - ⚠️ **NOT ACCEPTABLE**: Simply commenting "looks good"
- [ ] **Comment "unicorn" on your PR** - This confirms you've read all guidelines
- [ ] **Read the "instructions for creating a list"** - Must understand all requirements

### PR Title Format (EXACT FORMAT REQUIRED)
- [ ] **Format: "Add Name of List"** (e.g., "Add Swift", "Add Software Architecture")
- [ ] **DO NOT include the word "Awesome" in the title**
- [ ] **Use proper capitalization** (not lowercase)
- [ ] **DO NOT use variations like**:
  - ❌ "Update readme.md"
  - ❌ "Awesome Swift"
  - ❌ "add swift" (lowercase)
  - ❌ "Add awesome-swift"

## 📝 PR Description Requirements

### Entry Description Format
- [ ] **First character MUST be uppercase**
- [ ] **MUST end with a period (.)**
- [ ] **Must be an objective description of the project/resource**
- [ ] **CANNOT describe the list itself** (e.g., don't say "A curated list of...")
- [ ] **CANNOT include the list's name in the description**

Example:
- ✅ CORRECT: "Language for iOS and macOS development."
- ❌ WRONG: "awesome list of Swift resources"
- ❌ WRONG: "Swift - Language for iOS development" (includes name)
- ❌ WRONG: "language for iOS development." (lowercase start)
- ❌ WRONG: "Language for iOS development" (no period)

## 📁 Repository Requirements

### Basic Repository Setup
- [ ] **Repository must be at least 30 days old**
- [ ] **Default branch MUST be named "main"** (not master, not anything else)
- [ ] **Repository name format: "awesome-name-of-list"** (all lowercase, hyphenated)
  - ✅ Example: "awesome-swift", "awesome-machine-learning"
  - ❌ Wrong: "Awesome-Swift", "awesome_swift", "AwesomeSwift"

### README.md Requirements
- [ ] **Heading format: "# Awesome Name of List"** (Title Case)
  - ✅ Example: "# Awesome Swift", "# Awesome Machine Learning"
  - ❌ Wrong: "# awesome swift", "# Awesome swift"
- [ ] **Must be a non-generated Markdown file**
- [ ] **Include the Awesome badge** at the top
- [ ] **Must have a "Contents" section** with proper navigation
- [ ] **Include a succinct description** of what the list is about

### GitHub Repository Settings
- [ ] **Add GitHub topics**: Must include both "awesome-list" AND "awesome"
- [ ] **Include an appropriate Creative Commons license** (typically CC0)
- [ ] **Include contribution guidelines** (CONTRIBUTING.md or section in README)

## ✅ Content Quality Requirements

### List Content Standards
- [ ] **Only include truly "awesome" items** - best in class resources
- [ ] **No unmaintained or deprecated items**
- [ ] **Not a duplicate** of existing awesome lists
- [ ] **No blockchain-related content** (explicitly forbidden)
- [ ] **Every entry MUST have a description**
- [ ] **Include project logos when possible**

### Formatting Requirements
- [ ] **Consistent formatting throughout**
- [ ] **No hard-wrapping** of text
- [ ] **No CI badges** (Travis, CircleCI, etc.)
- [ ] **No "Inspired by awesome-XYZ" links**

## 🔧 Technical Validation

### Linting Requirements
- [ ] **Run awesome-lint** on your repository
- [ ] **Fix ALL issues reported by awesome-lint**
- [ ] **Verify the lint passes without errors**

```bash
# Install and run awesome-lint
npm install -g awesome-lint
awesome-lint
```

## 📋 Pre-Submission Checklist

1. [ ] Repository is 30+ days old
2. [ ] Default branch is "main"
3. [ ] Repository name follows "awesome-name-of-list" format
4. [ ] README heading follows "# Awesome Name of List" format
5. [ ] awesome-lint passes without errors
6. [ ] GitHub topics include "awesome-list" and "awesome"
7. [ ] Creative Commons license included
8. [ ] Contribution guidelines included
9. [ ] Contents section with navigation
10. [ ] Awesome badge included
11. [ ] All entries have descriptions
12. [ ] No blockchain content
13. [ ] No CI badges
14. [ ] No "Inspired by" links
15. [ ] Reviewed 2+ open PRs with substantive feedback
16. [ ] PR title follows "Add Name of List" format
17. [ ] Entry description starts with uppercase and ends with period
18. [ ] Ready to comment "unicorn" on the PR

## ⚠️ Common Mistakes to Avoid

1. **Forgetting to review other PRs first** - This is mandatory
2. **Using "Awesome" in the PR title** - Never include this word
3. **Wrong branch name** - Must be "main", not "master"
4. **Missing the period** in the entry description
5. **Forgetting to comment "unicorn"** - This confirms you read guidelines
6. **Not running awesome-lint** - This catches many formatting issues
7. **Wrong repository name format** - Must be lowercase with hyphens
8. **Missing GitHub topics** - Both "awesome-list" AND "awesome" required
9. **Including the list name in the description** - Description should be objective
10. **Opening as draft PR** - Must be complete and ready

## 🎯 Final Verification

Before submitting:
1. Double-check every item in this checklist
2. Run awesome-lint one more time
3. Verify your PR title is EXACTLY "Add [Your List Name]"
4. Confirm you've reviewed 2 other PRs thoroughly
5. Prepare to comment "unicorn" immediately after creating the PR