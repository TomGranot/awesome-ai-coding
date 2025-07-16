# Awesome List Resubmission Reminder

## Important Dates
- **Repository Created**: July 15, 2025
- **30-Day Mark**: August 14, 2025
- **Resubmit After**: August 15, 2025

## Pre-Submission Checklist

Before resubmitting to sindresorhus/awesome, ensure:

### Repository Requirements
- [ ] Repository is 30+ days old (check after August 14, 2025)
- [ ] Default branch is named `main` ✅
- [ ] GitHub topics: `awesome` and `awesome-list` ✅
- [ ] CC0 license in LICENSE file ✅
- [ ] contributing.md exists ✅
- [ ] code-of-conduct.md exists (needs manual completion)
- [ ] Run `npx awesome-lint` and fix ALL issues ✅

### Pull Request Requirements
- [ ] Review 2 other open PRs with meaningful feedback FIRST
- [ ] PR title: "Add AI Coding" (no "awesome" in title)
- [ ] PR description: "AI-powered coding assistants and development tools."
- [ ] After creating PR, comment "unicorn" on it

### Content Requirements
- [ ] 30+ high-quality items ✅
- [ ] Entry format: `[Name](link) - Description.` ✅
- [ ] Descriptions start with capital, end with period ✅
- [ ] No duplicate links ✅
- [ ] Curated content (quality over quantity) ✅

## Resubmission Steps

1. **August 14, 2025**: Verify repository age
   ```bash
   gh repo view TomGranot/awesome-ai-coding --json createdAt
   ```

2. **Review 2 PRs**: Go to https://github.com/sindresorhus/awesome/pulls and review 2 open PRs

3. **Final Checks**:
   ```bash
   npx awesome-lint
   ```

4. **Fork and Submit**:
   ```bash
   gh repo fork sindresorhus/awesome --clone
   cd awesome
   # Add entry to Development Environment section
   gh pr create --title "Add AI Coding" --body "AI-powered coding assistants and development tools."
   ```

5. **Post-submission**: Comment "unicorn" on your PR

## Notes
- The previous PR #3543 was closed due to the 30-day age requirement
- All technical issues have been resolved
- Only the age requirement and PR process steps remain