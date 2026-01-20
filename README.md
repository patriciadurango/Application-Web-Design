# Application-Web-Design

## Student Information
- **Name:** Patricia Valentina Durango Bravo
- **Student ID:** Al03091690
- **Course Name:** Application Web Design
- **Professor:** Ricardo Zapata

---

## What is Markdown?

Markdown is a lightweight markup language created by John Gruber in 2004. It allows writing in an easy-to-read plain text format that converts to HTML.

**Main Features:**
- Simple syntax using `#`, `*`, `-`, etc.
- Readable even without processing
- Used for documentation, READMEs, blogs, and wikis
- Portable across all platforms

---

## Markdown Syntax Guide

### Headers
````markdown
# H1 Header
## H2 Header
### H3 Header
````

### Text Formatting
````markdown
*italic* or _italic_
**bold** or __bold__
~~strikethrough~~
````

### Lists
````markdown
- Unordered item
1. Ordered item
````

### Links & Images
````markdown
[Link text](https://example.com)
![Alt text](image.jpg)
````

### Code
````markdown
`inline code`
```language
code block
``` 
````

### Tables
````markdown
| Header 1 | Header 2 |
|----------|----------|
| Data     | Data     |
````

---

## Git Commands Reference

### 1. Check Repository Status
````bash
git status              # Show repository status
git status -s           # Short format
````

### 2. Add Files to Staging
````bash
git add filename.txt    # Add specific file
git add .               # Add all files
git add -A              # Add all (including deleted)
````

### 3. Commit Changes
````bash
git commit -m "message"              # Commit with message
git commit -am "message"             # Add and commit
git commit --amend -m "new message"  # Modify last commit
````

### 4. Push to Remote Repository
````bash
git push -u origin main    # First push
git push                   # Subsequent pushes
git push origin branch     # Push specific branch
````

### 5. Branch Management

**Create:**
````bash
git branch branch-name           # Create branch
git checkout -b branch-name      # Create and switch
````

**Navigate:**
````bash
git checkout branch-name    # Switch to branch
git branch                  # List local branches
git branch -a               # List all branches
````

**Delete:**
````bash
git branch -d branch-name              # Delete local
git push origin --delete branch-name   # Delete remote
````

### 6. Rollback to Specific Commit

**View History:**
````bash
git log                # Full history
git log --oneline      # Compact history
````

**Rollback:**
````bash
# Safe (creates new commit)
git revert HEAD
git revert commit-hash

# Rewrite history (use carefully)
git reset --soft commit-hash   # Keep changes staged
git reset --mixed commit-hash  # Keep changes unstaged
git reset --hard commit-hash   # Discard all changes
````

---

## Additional Commands
````bash
# Clone repository
git clone https://github.com/username/repo.git

# Remote management
git remote -v                    # List remotes
git remote add origin URL        # Add remote

# Pull changes
git pull                         # Fetch and merge
git pull origin branch-name      # Pull specific branch

# Merge branches
git merge branch-name            # Merge branch
````

---

## Resources
- [Markdown Guide](https://www.markdownguide.org/)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com)


