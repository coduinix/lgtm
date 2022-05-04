## How to request a review?

vvv

### Describe goal
- What is the code supposed to do?
- Provide links to context

Note:
For context: think about issue tracker

vvv

### Draft PRs
- Request early feedback
- Minimize rework

vvv

### Keep them small
- Quick to review
  - Less context-switching
  - Less merge conflicts
- Removes barrier to start
- Keeps energy high

vvv

### Keep them focussed
- Try to do refactors in separate PRs
- Do style changes in separate PR

vvv

### Keep them updated
- Rebase (or merge) regularly
- Don't rebase after inital review
- Only squash/rebase before actual merge

Note:
- Rebasing after initial review, makes it harder for the reviewer to spot the differences with last review

vvv

### Be open to feedback
- Comments are about "the code"
  - ... not about you
- When unclear: discuss things synchronously

Note:
- Don't take it personal
- Discuss in person or via video/audio call

===

## How to review?

vvv

### Automate
- Code style check
- Compilation
- Tests

Note:
- in short: automate the boring parts

vvv

### High-level to low-level
- Understand the goal of the change
- Scan code first
- Read tests to verify understanding
- Work through code

Note:
Sometimes it works best to checkout the code and try things out

===

## How to comment?

vvv

### Be polite
- Use "we" instead of "you"
- "Request" instead of "demand"
- Give "praise"

vvv

### Be constructive
- Provide ready-to-apply suggestions
  - Try them out yourself
- Link to reference material

vvv

### Respect scope
- Only request changes related to the change at hand
- Keep other opportunities in the same area for a different PR
